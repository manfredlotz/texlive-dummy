# texlive-dummy

A texlive dummy package for archlinux

Thanks to zhou13: The PKGBUILD is taken from https://github.com/zhou13/aur/blob/master/texlive-dummy/PKGBUILD


## Build the texlive-dummy package

Run `makepkg`


## Install the package

`sudo pacman -U texlive-dummy-0.0.5-2-any.pkg.tar.zst`


## pacman.conf


It is recommended to add 

```
IgnorePkg   = texlive-dummy
```

in section `[options]` in /etc/pacman.conf


