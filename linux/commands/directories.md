# Commands to work with directories
## \> pwd
> $ pwd

Shows your current working location
## \> cd
'CD' means Change Directory, use this command to navigate through filesystem

If path start from '/', then path is absolute and starts from root directory, else starts from directory you are in now

> $ cd

Moves you to root directory

> $ cd [directory]

Moves you to specified directory

> $ cd ..

Moves you to parent folder of current folder

## \> ls
> $ ls

Displays files (excluding hidden) in your current location

> $ ls -a

Parameter '<strong>-a</strong>' makes command display all files (including hidden) in your current location

> $ ls -l

Parameter '<strong>-l</strong>' makes command display additional information about the files

> $  ls -lh

Parameter '<strong>-lh</strong>' makes command display size of files, that you can read easily, while <strong>-l</strong> parameter shows you number of bits

## \> mkdir 
> $ mkdir [path to new dir]

Creates new directory in specified location

> $ mkdir -p [path to new dir]

Parameter '<strong>-p</strong>' makes command to create not only the last specified dir, but all mentioned non-existing too. 

For example we have filesystem 'home/user', command 'mkdir -p home/user/dir1/dir2' would work, but 'mkdir home/user/dir1/dir2' won't, because 'dir1' doesn't exist

## \> rmdir
> $ rmdir [path to dir]

Removes specified directory (works only with empty dirs)

> $ rmdir -p [path to dir]

Parameter '<strong>-p</strong>' here works same way as with 'mkdir'

[Go back](./..)