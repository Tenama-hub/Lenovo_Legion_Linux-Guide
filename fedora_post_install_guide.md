# Fedora post-install guide
If you are lazy and you want to build your own install script, [click here](https://nattdf.streamlit.app/)\
A secondary option is the [install app by LinuxGamerLife](https://github.com/linuxgamerlife/lgl-system-loadout). Avoid installing the CachyOS kernel unless you absolutely need it.

Honorable mentions: [Noble guide](https://github.com/wz790/Fedora-Noble-Setup)
### Enable 3rd party repositories (MANDATORY!)
Enable them after install or use the commands below:\
```sudo dnf install https://download1.rpmfusion.org/free/fedora/rpmfusion-free-release-$(rpm -E %fedora).noarch.rpm && sudo dnf install https://download1.rpmfusion.org/nonfree/fedora/rpmfusion-nonfree-release-$(rpm -E %fedora).noarch.rpm```
### Enable full flatpak access (non-filtered version that isn't bundled by default on Fedora)
```flatpak remote-delete fedora && flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo```
### Install Nvidia drivers
Install the driver by using the command below, then wait 10-15 minutes before rebooting!!!   
```sudo dnf install akmod-nvidia xorg-x11-drv-nvidia-cuda -y```
[Click here for more details](https://rpmfusion.org/Howto/NVIDIA?highlight=%28%5CbCategoryHowto%5Cb%29)
### Install multimedia codecs
Follow the [official RPMFusion guide](https://rpmfusion.org/Howto/Multimedia?highlight=%28%5CbCategoryHowto%5Cb%29) 
### Enable Secure Boot
[Click here for more details](https://github.com/roworu/nvidia-fedora-secureboot)
