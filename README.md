# New/Modified AUR packages

## Installation

Download the package files, then to compile and install just type

    makepkg -si

To create an AUR package, just type

    makepkg -S

If you modify one of these packages, change the md5sum in the PKGBUILD.
To get the new sum, just type

    makepkg -g

