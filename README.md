# xash3d-fwgs-build-instruction
## Required dependencies
### Linux
#### Debian/Ubuntu:
* install development tools \
`sudo apt install build-essential git python-is-python3 libsdl2-dev libfontconfig-dev libfreetype6-dev cmake` \
DO NOT INSTALL DEFAULT `libopus-dev` PACKAGE! This build of opus doesnt contains a custom modes support!!
#### Fedora Linux:
* Install development tools \
`sudo dnf install make automake gcc gcc-c++ kernel-devel SDL2-devel freetype-devel fontconfig-devel cmake opus-devel` 
#### Alpine Linux:
* Install development tools \
`doas apk add python3 alpine-sdk sdl2-dev freetype-dev fontconfig-dev opus-dev cmake` 
#### OpenSUSE:
* Install development tools \
`sudo zypper install git python patterns-devel-base-devel_basis SDL2-devel fontconfig-devel freetype-devel libopus-devel cmake`
