# LeftWM themes - arch-one-dark

![](https://github.com/jamesbaker1901/leftwm-arch-one-dark/blob/main/screenshot.png?raw=true)

A simple polybar theme for leftwm based on the one-dark color scheme.

Also included is my alacritty config with [one-dark colors](https://github.com/eendroroy/alacritty-theme/blob/master/themes/one_dark.yaml) and BlexMono Nerd Font (included and installed by the theme).

## Requirements
* [picom](https://wiki.archlinux.org/title/picom)
* [dunst](https://wiki.archlinux.org/title/dunst)
* [polybar](https://wiki.archlinux.org/title/Polybar)
* [playerctl](https://man.archlinux.org/man/community/playerctl/playerctl.1.en)
* [spotify (AUR)](https://aur.archlinux.org/packages/spotify)

Install them with:
```
$ sudo pacman -S picom dunst polybar playerctl

# you can build the spotify package from the AUR manually, or just use an AUR helper like yay

$ yay -S spotify
```


### Credit
This theme was initially a fork of the lovely port of [Forest](https://github.com/lex148/forest) to leftwm by [lex148](https://github.com/lex148), which in turn was heavily influenced by the great theme forest over at [adi1090x / polybar-themes](https://github.com/adi1090x/polybar-themes).

The main similarities lie in the polybar config. I changed it quite a bit to achieve the look and feel I wanted, but it's still largely based on what [lex148](https://github.com/lex148) ported from [adi1090x / polybar-themes](https://github.com/adi1090x/polybar-themes).
