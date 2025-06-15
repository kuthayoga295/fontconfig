# fontconfig
Arch Linux Font Configuration File
================================================
sudo pacman -S noto-fonts
sudo pacman -S noto-fonts-cjk
sudo pacman -S noto-fonts-emoji
sudo pacman -S noto-fonts-extra

/etc/profile.d/freetype2.sh

~/.config/fontconfig/fontconfig/fonts.conf

~/.config/fontconfig/conf.d/20-no-embedded.conf

~/.Xresources

~/.xsettingsd

~/.config/gtk-4.0/settings.ini

sudo fc-cache -fv

reboot
