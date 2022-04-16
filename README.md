# My xmonad config
### A custom [xmonad](https://xmonad.org) configuration for Arch Linux by Anapal.

![alt text](https://github.com/AnapalOne/xmonad/blob/main/2022-04-13_17-41.png "xmonad")
   **NOTES: This configuration installs a lot of packages and programs, see the [list of packages](https://github.com/AnapalOne/xmonad#list-of-packages).**

## Requirements
### xmonad
```
sudo pacman -S xmonad xmonad-contrib
```
- I recommend using [xinit](https://wiki.archlinux.org/title/Xinit) to automatically start xmonad
- Read the wiki for more details: https://wiki.archlinux.org/title/Xmonad

### git
``` 
sudo pacman -S git
```
  - Verify: `git --version`

### yay
```
git clone https://aur.archlinux.org/yay.git && cd yay
```
```
makepkg -si
``` 

### Any graphical display managers
- List of display managers: https://wiki.archlinux.org/title/Display_manager

## Setup
#### Download xmonad repo
``` 
git clone https://github.com/AnapalOne/xmonad && cd xmonad
``` 
#### Give permission to execute script that automatically installs packages and configures xmonad
```
chmod +x ./setup.sh
```
#### Run script
```
./setup.sh
```

- If you want to only apply the xmonad config to your xmonad, simply copy `xmonad.hs` to `~/.xmonad/`
- If you want to only apply xmobar, copy `xmobar` to `~/.xmobarrc/`

## List of packages
| Packages                                           | Description |
| ---------------------------------------------------|:-------------:|
| alacritty                                          | terminal emulator |
| xmobar                                             | status bar |
| picom                                              | compositor |
| libreoffice                                        | office suite |
| xf86-input-libinput, libinput-gestures             | input device handler, touchscreen, touchpad drivers |
| pulseaudio                                         | audio manager |
| pamixer                                            | volume control w/ gui |
| youtube-dl                                         | youtube video/audio downloader |
| nerd-fonts-complete, ttf-iosevka, ttc-iosevka-aile, 
   ttc-iosevka-curly, ttf-bitstream-vera | fonts |
| xdotool                                            | input emulator |
| htop                                               | program manager |
| ncdu                                               | disk usage analyzer |
| nnn                                                | file manager |
| iwctl                                              | internet manager |
| yay                                                | AUR helper |
| subl, nano, vim                                    | text editors |
| xprop                                              | shows information about a window |
| flameshot                                          | capture screen |
| tlp, tlpui                                         | battery manager |
| nitrogen                                           | wallpaper |
| chromium                                           | browser |
| krita                                              | drawing software |
| gimp                                               | image editor/drawing software |
| mpv, vlc                                           | video software |
| audacity                                           | audio software |
| mirage                                             | image viewer |
| spotify                                            | music |
| discord                                            | text and voice app |
| github-desktop                                     | github desktop |
