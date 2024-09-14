# Dependencies
- rofi
- i3gaps
- polybar
- my wallset patch (https://github.com/trurune/wallset-patch)
- picom
- xinit
# Installation
1. Copy i3 config to ~/.config/i3/config
2. Copy polybar config to ~/.config/polybar/config.ini
3. Copy picom config to ~/.config/picom/picom.conf
4. Clone wallset patch
5. cd wallset-patch && ./install.sh
6. cd .. && rm -r wallset-patch
7. Download wallpaper.mp4 (sample wallpaper, you can actually put any mp4 file for stage 8
8. mkdir ~/Wallpapers && cp wallpaper.mp4 ~/Wallpapers
9. echo "exec i3" >> ~/.xinitrc
10. startx
