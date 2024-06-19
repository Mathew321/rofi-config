# My rofi config (Stolen btw)

This my configuration for rofi!
<img align="center" width="49%" src="https://raw.githubusercontent.com/JaKooLit/screenshots/main/Hyprland-Dots-Showcase/rofi.png" />

## Instalation

For debian:
```bash
sudo apt install rofi
```
For fedora:
```bash
sudo dnf install rofi
```
For arch idk! search it up
==========================
After installing rofi run:
```bash
git clone https://github.com/Mathew321/rofi-config.git
sudo mv rofi-config/* ~/.config/rofi # NOTE: You first need to create the rofi folder in .config if it does not exist
cd ~/.config/rofi
ln -s {YOUR BACKGROUND FOLDER}/background.png ~/.config/rofi/.current_wallpaper # Creates a simlink for current wallpaper
```

### Final step

You could set a keybind to run rofi. I set a keybind for this command:
```bash
pkill rofi || rofi -show drun -modi drun,filebrowser,run,window
```

## Final NOTE

Use this at your own risk. But this should work for both Debian and Fedora! Don't know about Arch!
