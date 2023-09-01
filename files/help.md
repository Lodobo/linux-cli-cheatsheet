# HELP


#### `man [program]`
The man utility finds and displays online manual documentation pages. Man pages include descriptions, applicable options, flags, examples, and other informative sections.

#### `tldr [program]`
The tldr-project is a collection of community-maintained help pages for command-line tools, that aims to be a simpler, more approachable complement to traditional man pages. tldr pages are focused on practical examples. To use tldr you can install the [tealdear client](https://github.com/dbrgn/tealdeer).


### CORE-UTILS
---
#### `cd`
Change current working directory. If no directory is specified, the working directory is changed to the home directory of the current user.
#### `ls`
List the files in a directory. To list all files, including hidden files, in a detailed format, use `ls -lah`.
#### `rm`
Delete files and directories.
#### `mv`
Move or rename files.
#### `cp`
Copy a file or directory.
#### `ln`
Create a symbolic link.
#### `pwd`
Print (current) working directory
#### `touch`
Create files and update access/modification timestamps.
#### `mkdir`
Create directories
#### `realpath`
Return resolved physical path.

### SHELL-UTILS
---
#### `whoami`
Print the effective user ID 
#### `hostname`
Print the system's host name
#### `du`
Display disk usage on file systems. To print non-recursively in a human readable format, use `du -sh [file]`.
#### `df`
Display free disk space
#### `nohup`
Allow a command to continue running after logging out 

### ARCHIVE-UTILS
---
#### `zip`
Package and compress files into a ZIP archive.
#### `unzip`
Extract files from a ZIP archive.
#### `gzip`
Compress/uncompress files with gzip compression. By default, the input file is replaced. To keep the original file, use the '--keep' option.
#### `tar`
General purpose archiving utility.

### TEXT-UTILS
---
#### `cat`
Print file content to STDOUT. Name derived from concatenate.
#### `less [file]`
Display and navigate file content in a terminal pager.
#### `head`
Print the first lines of a file.
#### `tail`
Print the last lines of a file.

### FILE-UTILS
---
#### `mediainfo [file]`
Print information about a file.
#### `exiftool [file]`
Print information about a file.
#### `pandoc`
Convert from one markup format into another.


### SEARCH-UTILS
---
#### `find`
Find files or directories recursively in a specified root directory. To search for a filename, use `find /path/to/dir -name *[file-name]*`
#### `locate`
Find filenames quickly. `locate` searches in a database prepared by `locate updatedb`. `locate` does not check whether the files in the database still exist. `locate` cannot report files created after the most recent update of the database.
#### `grep`
Search for a pattern in files or strings using regular expressions.
#### `fzf`
Fuzzy Finder

### NET-UTILS
---
#### `ip`
Show and manipulate networking devices, interfaces and tunnels.
#### `ifconfig`
Configure network interfaces.
#### `ping`
send ICMP echo-requests to network hosts.
#### `rsync`
Transfer and synchronize files between local and remote hosts. 


### SYS-UTILS
---
#### `chgrp`
Change file group ownership.
#### `chown`
Change file ownership.
#### `chmod`
Change the permissions of a file or directory.
### `useradd`
### `usermod`
### `userdel`
### `groupadd`
### `groupmod`
### `groupdel`

#### `chgroup`
#### `chpasswd`
#### `chuser`
#### `lsuser`
#### `lsgroup`
#### `mkgroup`
#### `mkuser`
#### `rmgroup`
#### `rmuser`
#### `passwd`


## LIST USERS AND GROUPS.
User account information is stored in `/etc/passwd`. Group account information is stored in `/etc/group`. A list of users and groups can be found inside these files.


## MANAGE SOFTWARE
- debian/ubuntu : `apt`, `dpkg`
- fedora/centOS/RHEL : `dnf`
- arch : `pacman`, `yay`, `paru`
- openSuse : `zypper`

- cross-platform: snap, flatpak

## CLI PROGRAMS
- `htop` : task manaer
- `vim [file]` : text editor.
- `nano` : text editor
- `hx` : helix text editor
- `joshuto` : terminal file manager
- `ranger` : terminal file manager
- `disown` : similar to nohup. Launch a terminal application in the background.

- `yt-dlp` : download media from the internet.
- `ffmpeg` : audio and video converter.
- `musikcube` : music player.

## TROUBELSHOOTING
- `inxi -F` : print system information 
- `lscpu` : list cpu information.
- `lshw` : list hardware information
- `lspci`  : list PCI devices.
- `lsusb`  : list USB devices.
- `lsblk` : list block devices (storage).
- `lsusb` : List USB buses and devices.
- `lsscsi` : List scsi Devices
 
- `dmesg` : print kernel ring buffer

## DISPLAY LOGS
Logs are stored in `/var/log`, to display the logs, use the `less` command.


