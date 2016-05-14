# GCC 4.9 for Arch Linux/AUR

I have had trouble installing gcc 4.9 alongside gcc 6 on my computer, running Arch Linux. 
This is a working PKGBUILD for the [gcc49 package from AUR](https://aur.archlinux.org/packages/gcc49/). It compiles agains gcc6.

Just clone this repository and run `makepkg` followed by `pacman -U gcc49-4.9.3-1-x86_64.pkg.tar.xz` after the compilation finished
and it should install gcc 4.9.
