# Hollow Knight based GRUB theme 
## About theme
This is GRUB theme based on game Hollow Knight,<br>
especially on character Grub from this game<br>
This is a fork of my other repository with installation via `git clone`
## Installation
Clone this repository in GRUB directory
```
sudo git clone https://github.com/jvmho/GrubbyGrub-Theme.git /boot/grub/themes/GrubbyGrub
```
Then initialize theme in `/etc/default/grub`: <br>
Enter editor and change/add this line: <br>
```
GRUB_THEME="/boot/grub/grub-theme/theme.txt"
``` 
Then recreate GRUB config with this command:<br>  
```
sudo grub-mkconfig -o /boot/grub/grub.cfg
``` 
or `sudo update-grub` on Debian-based systems(Debian, Ubuntu, Mint, Pop!_OS)
