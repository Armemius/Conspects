# Commands to work with files' content
## \> head
> $ head [filename]

Displays 10 first lines of specified file

> $ head -[number] [filename]

Dispays N first lines of specified file

> $ head -c[number] [filename]

Dispays N first bytes of specified file

## \> tail
> $ tail [filename]

Displays 10 last lines of specified file

> $ tail -[number] [filename]

Dispays N last lines of specified file

> $ tail -c[number] [filename]

Dispays N last bytes of specified file

## \> xxd
> $ xxd [filename]

Shows specified file's bytecode in hexadecimal format

> $ xxd -b [filename]

Shows specified file's bytecode in binary format

## \> cat
> $ cat [filename]

Displays whole text file

> $ cat > [filename]

Creates new text file with specified name and then lets you write into it

> $ cat [filename] > [filename]

Copy text from first specified file to second

## \> tac
> $ tac [filename]

Displays whole text file backwards

## \> less
> $ less [filename]

Displays whole text file, but on separate pages, useful when file to display doesn't fit console (J/K to navigate, Q to exit)

## \> strings
> $ strings [filename]

Finds text in binary files and displays it

[Go back](./..)