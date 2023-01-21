# My build of dwm
- dwm is a window manager for X server on linux
# Applied Patches
- [bar height](https://dwm.suckless.org/patches/bar_height/)
- [movestack](https://dwm.suckless.org/patches/movestack/)
- [pertag](https://dwm.suckless.org/patches/pertag/)
- [rainbowtags](https://dwm.suckless.org/patches/rainbowtags/)
- [restartsig](https://dwm.suckless.org/patches/restartsig/)
- - keybinding: MOD+CTRL+SHIFT+Q to restart dwm
- [status2d](https://dwm.suckless.org/patches/status2d/)
- [statusbar on all monitors](https://dwm.suckless.org/patches/statusallmons/)
- [sticky](https://dwm.suckless.org/patches/sticky/)
- [systray](https://dwm.suckless.org/patches/systray/)
- [useless gap](https://dwm.suckless.org/patches/uselessgap/)
# Dependencies
## Arch Linux
```
sudo pacman -S base-devel libx11 libxft libxinerama freetype2 fontconfig
```
## Debian
```
sudo apt install build-essential libx11-dev libxft-dev libxinerama-dev libfreetype6-dev libfontconfig1-dev
```
## Void Linux
```
sudo xbps-install base-devel libX11-devel libXft-devel libXinerama-devel freetype-devel fontconfig-devel
```
***
# Installation
```
git clone https://github.com/karimhussein1/dwm.git
cd dwm
sudo make install

```
then add `exec dwm` to your /etc/X11/xinit/xinitrc file

