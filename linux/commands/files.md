# Commands to work with files
## \> file
> $ file [filename]

Provides info about file

## \> touch
> $ touch [filename]

If file exists, updates time label of file to current time and date, else creates empty file

> $ touch -t [date] [filename]

Sets time label of file to specified

## \> rm
> $ rm [filename]

Removes specified file (unable to delete directories)

> $ rm -r [filename]

Removes specified file or directory

> $ rm -f [filename]

Force removal of file

> $ rm -rf [filename]

Force removal of file or directory

## \> cp
> $ cp [filename...] [filename]

Copies files (you can specify multiple files) to specified location (if location is directory, copies file with same name to specified dir, else creates a copy file with specified name)

> $ cp -r [filename...] [filename]

If you want to copy dir, you shoud use '<strong>-r</strong>' parameter

> $ cp -i [filename...] [filename]

Activates interactive regime of copying (useful when new files override old ones)

## \> mv
> $ mv [filename] [filename]

Moves file or dir to specified location

> $ mv -i [filename] [filename]

Same as in 'cp' command

[Go back](./..)