# General commands
## \> man
> $ man [command]

This command is used to show information about other commands

## \> sudo
> $ sudo [command]

Grants superuser access to execute other commands

> $ sudo -s

Parameter '<strong>-s</strong>' makes you superuser permanently so you don't have to write 'sudo' if you want higher access level

## \> apt
Advanced Packaging Tool or APT is responsible for managing and installing packages
> $ apt search [package name]

Searches for available packages with matching name to download

> $ apt show [package name]

Shows info about specified package

> $ apt install [package name]

Installs specified package

> $ apt list [parameter | empty]

Shows list of all packages if parameter is not specified, else shows filtered based on parameter list

> $ apt list --installed

Shows list of all installed packages and their versions

> $ apt list --upgradeable

Shows list of all installed packages that can be upgraded

## \> cowsay
> $ cowsay [text]

Very important command: you write text, and cow says it

 < Your mom is gay >
 -----------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||

[Go back](./..)