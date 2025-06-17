# Navigation

In this file we are going to learn how to navigate the file system.

## Commands

```bash

pwd # Print name of current working directory
cd # Change directory
ls # List directory contents

```

## File System Tree

Files are organized in a tree-like pattern of directories. The first directory
in the file system is **root directory**
The directory we are standing in is called the current working directory, to 
display this we use **pwd** (print working directory).

We can use the **ls** command to list the contents of any directory

## Changing the Current Working Directory

We use the **cd** command followed  by the pathname.

### Absolute Pathnames

It begins with the root directory and follows the tree branch by branch until
the path to the desired directory.

```bash

cd /usr/bin
pwd
/usr/bin

```
### Relative Pathnames

It starts from the working directory

```bash

cd  /usr/bin
pwd
/usr/bin
cd ..
pwd
/usr

```

In almost of cases we can omit the "./". it is implied

## Helpful Shotcuts

```bash

cd 		# Changes the working directory to your home directory
cd - 		# Changes the working directory to the previous one
cd ~user_name 	# Changes the working directory to the home directory of 
user_name
