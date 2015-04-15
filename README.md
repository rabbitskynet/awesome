first you need to configure that awesome conf from nothing:
* apt-get install git
* apt-get install rxvt
* apt-get install rxvt-unicode
* apt-get install chromium-browser
* apt-get install awesome awesome-extra
* apt-get install lightdm-gtk-greeter
* apt-get install upower

if you see squares instead of russian text
add "FRAMEBUFFER=Y" to end of "/etc/initramfs-tools/initramfs.conf"
then exec "update-initramfs -u"
after that use "dpkg-reconfigure console-setup"

