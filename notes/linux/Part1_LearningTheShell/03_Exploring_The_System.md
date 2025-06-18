# Exploring The System

More useful commands

```bash

ls	 # List directory contents
file	 # Determine file type
less 	 # View file contents

```
## More about ls command

We can enter 'ls' to get a list of files contained in the current working directory
Also we can specify a directory to list 
```bash
ls /usr
```
We can even specify multiple directories
```bash
ls ~ /usr
```
We can also change the format to reveal more details

```bash
ls -l
```
## Options and Arguments

Commands are often followed by one or more options that modify the behavior
, and futher, by one or more arguments. Most commands look like this:

```bash
command -options arguments
```

Multiple commands allow multiple short options to be strung together.

In the following example, the ls command is given two options, *l* option
produce long format output, and the t option to sort the result by the file's
modification time,

```bash
$ ls -lt
```

## Common ls Options

```bash
-a 	# List all files, even those with names that begin with a period
-A	# Like the -a option  above except it does not list . and ..
-d 	# List the directory
-F 	# This append an indicator character to the end of each listed name.
-h	# Display file sizes in human readable format than in bytes.
-l	# Display results in long format
-r	# Display the results in reverse order
-s	# Sort results by file size.
-t	# Sort by modification time.
 ```

## Determining File`s Type with file

We use **file** command to determine a file's type. This command will print
a brief description of the file's content.

```bash
$ file picture.jpg
picture.jpg: JPEG image data, JFIF standard 1.01

```
## Viewing File Contents with less

The **less** command is a program to view text files

## Taking a Guided tour

Directories Found on Linux Systems

```bash
/		# The root directory. Everything starts here
/bin		# Contains binaries that must be present for the system to boot and run
/boot		# Contains the Linux kernel , initial RAM disk image, and the boot loader
/dev		# Special directory that contains device nodes.
/etc		# Contains all of the system-wide configurations files. It also 
		contains a collection of shell scripts that start each of the system
		services al boot time.
/home		# Each user is given a directory in /home. 
/lib		# Contains shared library files used by the core system programs
/lost+found   	# Each formatted partition or device using a Linux file system,
		will have this directory. It is used in case of a partial 
		recovery from a file system corruption event.
/media		# Will contain the mount points for removable media.
/mnt		# Contains mount points for ndevices that have been mounted
		manually.
/opt		# Is used to install "optional" software
/proc		# It is a virtual file system maintained by the Linux kernel
		The "files" it contains are peepholes into the kernel itself
/root		# This is the home directory for the root account
/run		# IS a temporaly fileSystem that stores runtime data
/sbin		# This directory contains "system" binaries.
/sys		# Contains information about devices that have been detected
		by the kernel
/tmp		# Is intended for the storage of temporary, transient files
		created by various programs
/usr		# It contains all the programs and support files used by
		 regularusers
/usr/bin	# Contains the executable programs installed by the Linux distribution.
/usr/lib	# The shared libraries  for the programs in /usr/bin
/usr/local	# si where programs that are not included with the distribution
 		but are intended for system-side use are installed
/usr/sbin	# Contains more system administration programs.
/usr/share	# Contains all the shared data used by programs in /usr/bin
/usr/share/doc	# We can find documentation files organized by package
/var		# Is where data that is likely to change is stored.
/var/log	# Contains log files, records of various system activity.
~/.config	# 
~/.local	# There 2 directories are located in the home directory of
		each desktop user. Used to store user-specific configuration data
```




