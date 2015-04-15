first you need to configure that awesome conf from nothing:
* git
* gnome-terminal
* chromium-browser
* awesome
* awesome-extra
* lightdm-gtk-greeter
* upower
*

if you see squares instead of russian text
add "FRAMEBUFFER=Y" to end of "/etc/initramfs-tools/initramfs.conf"
then exec "update-initramfs -u"
after that use "dpkg-reconfigure console-setup"

