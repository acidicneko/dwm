OwO
Wanna install this?
Ok.

## Dependencies
Install `iw` and `upower` utilities on your distro.

Get Iosevka Nerd Font from [here](https://github.com/ryanoasis/nerd-fonts/blob/master/patched-fonts/Iosevka/Regular/complete/Iosevka%20Nerd%20Font%20Complete.ttf)

## Installation
For DWM
```
git clone https://github.com/ayush7788/dwm
cd dwm
make install
```
For DWMBlocks
```
cd dwmblocks
make install
```

Put this in your ~/.xinitrc
```
dwmblocks &
dwm
```

Install `xinit` on your distro. i.e `xorg-xinit` on Arch

Then from a TTY, do `startx`.

Enjoy!
