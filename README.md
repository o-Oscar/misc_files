# Ubuntu setup

To run the default ubuntu setup, you can run the following commands :

```
gesttings set org.gnome.shell.extensions.dash-to-dock dock-position 'BOTTOM'
gsettings set org.gnome.shell.extensions.dash-to-dock dock-fixed false
gesettings set org.gnome.shell.extensions.dash-to-dock extend-height false
sudo wget -O /usr/share/backgrounds/minimal_mountain.jpg https://unsplash.com/photos/_f2m3mEkaaU/download
gsettings set org.gnome.desktop.background picture-uri file:////usr/share/backgrounds/minimal_mountain.jpg

sudo apt install gnome-shell-extensions
sudo apt install gnome-shell-extension-autohidetopbar
# you may have to restart your computer here before the previous changes are taken into account
gnome-extensions enable hidetopbar@mathieu.bidon.ca
gnome-extensions prefs hidetopbar@mathieu.bidon.ca
gnome-extensions disable desktop-icons@csoriano
```