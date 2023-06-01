# fedora-i3-spin-tuning
This project is my own customization of fedora-spin-i3
## Table of Contents
[Change of wallpaper](#change-of-wallpaper)  
[Change of i3status](#change-of-i3status)  
<a name="#change-of-wallpaper"/>
## Change of wallpaper
In fedora the wallpaper is used from the login screen. "lightdm" is used for it.
<br />config:
````
/etc/lightdm/lightdm-gtk-greeter.conf
````
.
<a name="#change-of-i3status"/>
## Change of i3status
config:
````
/etc/i3status.conf
````
My changes:
- I removed ipv6 status.
- I removed ethernet status(i only use wifi).
- I removed disk info. 
- I changed memory status format to "U: %used | A" %available" (i added labels "U" and "A")
- I removed seconds from current time
My config is in "config/i3status/config". It should be copy to .config/i3status/config