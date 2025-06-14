# Space Isolation
A GRUB theme based on the main menu of the 2014 survival horror game Alien: Isolation™.

![Preview](preview.jpg "Space Isolation GRUB2 Theme Preview")

## ⚠️ Disclaimer
This theme currently **only supports 2560x1440** and it doesn't scale well on other resolutions.

## Installation
### Arch Linux
1. Rename the directory with your resolution to `space-isolation`
2. Copy this directory to `/boot/grub/themes`
    ```zsh
    # cp -r <theme_directory> /boot/grub/themes
    ```

2. Change the default GRUB theme by editing `/etc/default/grub`. Find `GRUB_THEME=<path>` and change the path to `/boot/grub/themes/space-isolation/theme.txt`

3. Update GRUB
    ```zsh
    # grub-mkconfig -o /boot/grub/grub.cfg 
    ```
