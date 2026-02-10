# Amd-GRUB

How to Install
Make sure you understand what you are doing. Installation of the theme can cause problems in your system if done incorrectly

Manual Installation
Clone the repo
git clone https://github.com/JeffreyYAJ/Amd-GRUB
Copy the entire Amd-GRUB/ directory to /boot/grub/themes/ or similar path depending on your distribution

Change the GRUB_THEME line in /etc/default/grub file:

GRUB_THEME="/boot/grub/themes/Amd-GRUB/theme.txt"

Update GRUB with sudo privileges.
For Arch based systems:

sudo grub-mkconfig -o /boot/grub/grub.cfg
For Debian based systems:

sudo update-grub

