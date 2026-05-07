# Linux Mint post-install guide

| Tweak Name | Command/Link/Path |
| ------------- | ------------- |
| **Get the very latest Mesa drivers** | Go to **Software Sources -> PPAs**, click on **ADD** and paste the following:<br>`ppa:kisak/kisak-mesa` |
| **Install the latest Mint kernel** | Update manager -> Linux kernels. Choose the very latest kernel version provided by Mint. Using kernels outside what Linux Mint provides will break Nvidia drivers. Unless you know what you are doing, please do not use external repositories on Mint! |
| **Install additional codecs** | Either install them during the installer, or post-installation by going to **Start Menu -> Sound & Video -> Install Multimedia Codecs.** |
| **Enable Z-Ram (optional)** | https://forums.linuxmint.com/viewtopic.php?t=427964 |
| **Speed up Linux Mint (optional)** | https://easylinuxtipsproject.blogspot.com/p/speed-mint.html |
| **Enable NTSYNC (helps improve performance in games. Make sure to run them with Proton-GE!)** | `echo ntsync \| sudo tee /etc/modules-load.d/ntsync.conf && sudo modprobe ntsync` |
