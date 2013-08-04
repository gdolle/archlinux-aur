# New/Modified AUR packages

## Installation

Get the package files and just type

    makepkg -si


## Misc

To send the package on AUR, create it using the command

    makepkg -S

If you modify one of these packages, change the md5sum in the PKGBUILD.
To get the new sum, just type

    makepkg -g

## Links

[ArchWiki : howto create package](https://wiki.archlinux.org/index.php/Creating_Packages)


