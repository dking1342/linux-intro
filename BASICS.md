# Basics of the Terminal and Linux

## Commands
### man
man - format and display the on-line manual pages

```
man [-acdfFhkKtwW] [--path] [-m system] [-p string] [-C config_file] [-M
pathlist] [-P pager] [-B browser] [-H htmlpager] [-S section_list]
[section] name ...
```

### pwd
pwd – return working directory name

```
pwd [-L | -P]
```

### cd
cd - change directory

```
cd <directory>
```

### ls
ls – list directory contents

```
ls [-@ABCFGHILOPRSTUWabcdefghiklmnopqrstuvwxy1%,] [--color=when]
        [-D format] [file ...]
```

### mkdir
mkdir – make directories

```
mkdir [-pv] [-m mode] directory_name ...
```

### rmdir
rmdir – remove directories

```
rmdir [-pv] directory ...
```

### rm
rm, unlink – remove directory entries

```
rm [-f | -i] [-dIRrvWx] file ...
unlink [--] file
```

### file
file – determine file type

```
file [-bcdDhiIkLnNprsvz] [--exclude-quiet] [--extension]
    [--mime-encoding] [--mime-type] [-f namefile]
    [-m magicfiles] [-P name=value] [-M magicfiles] file
file -C [-m magicfiles]
file [--help]
```

### touch
touch – change file access and modification times

```
touch [-A [-][[hh]mm]SS] [-achm] [-r file]
      [-t [[CC]YY]MMDDhhmm[.SS]]
      [-d YYYY-MM-DDThh:mm:SS[.frac][tz]] file ...
```

### cp
cp – copy files

```
cp [-R [-H | -L | -P]] [-fi | -n] [-alpsvXx]
  source_file target_file
cp [-R [-H | -L | -P]] [-fi | -n] [-alpsvXx]
  source_file ... target_directory
```

### mv
mv – move files

```
mv [-f | -i | -n] [-hv] source target
mv [-f | -i | -n] [-v] source ... directory
```

### head
head – display first lines of a file

```
head [-n count | -c bytes] [file ...]
```

### tail
tail – display the last part of a file

```
tail [-F | -f | -r] [-q] [-b number | -c number | -n number]
    [file ...]
```

### cat
cat – concatenate and print files

```
cat [-belnstuv] [file ...]
```

### echo
echo – write arguments to the standard output

```
echo [-n] [string ...]
```

### less
less - opposite of more

```
less -?
less --help
less -V
less --version
less [-[+]aABcCdeEfFgGiIJKLmMnNqQrRsSuUVwWX~]
    [-b space] [-h lines] [-j line] [-k keyfile]
    [-{oO} logfile] [-p pattern] [-P prompt] [-t tag]
    [-T tagsfile] [-x tab,...] [-y lines] [-[z] lines]
    [-# shift] [+[+]cmd] [--] [filename]...
```

### open
open – open files and directories

```
open [-e] [-t] [-f] [-F] [-W] [-R] [-n] [-g] [-j] [-h] [-u URL] [-s sdk]
    [-b bundle_identifier] [-a application] [--env VAR] [--stderr PATH]
    [--stdin PATH] [--stdout PATH] file ... [--args arg1 ...]
```

### nano
nano - edits file
pico - simple text editor in the style of the Alpine Composer

```
pico [ options ] [ file ]
```

## System info
### uptime
uptime – show how long system has been running
### free (not on macos)
free - amount of free space on hard disk
### ps
ps – process status
### kill
kill – terminate or signal a process
### df
df – display free disk space
### fdisk
fdisk – DOS partition maintenance program
### top
top – display sorted information about processes


## Networking
### ifconfig
ifconfig – configure network interface parameters
### ipconfig
ipconfig – view and control IP configuration state

## Folder structure
### bin
where your binary files are stored
### boot
all the needed files for boot up are stored
### cdrom
where your cd drive is stored
### dev
where your physical devices are mounted
### etc
where the config files are stored. common to have files with extension .conf
### home
where all the user files are stored
### lib
where binaries are stored. they are libraries that are needed for the os to work properly. lib32 or lib64 just tell the bit size
### media
where external devices like usb drive, etc are stored
### mnt
placeholder folder for mounting external drives, remote drives, etc.
### opt
optional software for the system
### proc
where systems information is stored. where kernal is processed
### root
home directory for the home account. permissions for that account
### run 
drives are automounted. relevant to desktops
### sbin
similar to bin, but dedicated to run certain commands by home account
### tmp
where temporary files are stored
### snap
way to download files 
### usr
files and utilities that are shared between users and system
### var
where variable files are stored.

## Software package manager
### sudo
sudo, sudoedit - execute a command as another user
### apt (linux based)
advanced package management used to install linux programs
### brew (macos)
brew - The Missing Package Manager for macOS (or Linux)
