# snis-live
A bootable live image based of ArchLinux x86_64 customised to run the game Space Nerds In Space by smcameron.
https://github.com/smcameron/space-nerds-in-space

## Requirements (for building from source in ArchLinux)
* [archiso](https://wiki.archlinux.org/index.php/Archiso)
* git
* base-devel
* portaudio
* libvorbis
* gtk2
* gtkglext
* openscad
* lua
* glew
* openssl

## Building
###### NOTE: Building the ISO requires an x86_64 pc running ArchLinux. If you do not run arch linux then there is [this project](https://github.com/tokland/arch-bootstrap) which creates an ArchLinux chroot enviroment which you can build the iso from.
To build from source run

`git clone https://github.com/HUg0005/snis-live`
`cd snis-live`
`sudo sh ./autobuild`

`./autobuild` has to be run as root script as **root** (because of [false permission problems later](https://wiki.archlinux.org/index.php/Archiso#Setup)). The script will clone and build space nerds in space, then build the ISO. Once it has completed, an ISO file will have be created in the `./out` directory.

## Prebuilt Images
There are prebuilt images avaliable from my [Dropbox](https://www.dropbox.com/sh/whqpu99a5e7dxf5/AADMQn8EGs9YcpAsxDXzcIW7a?dl=0).
Please note that these images are probably using old versions (check the build date). 
