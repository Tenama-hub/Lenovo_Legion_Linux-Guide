# 🐧 Linux guide for Legion laptops, handhelds & PCs 🐧
# ⭐ LAST UPDATE : 14 APRIL 2026 ⭐
Feel free to join our [discord group as well](https://discord.gg/legionseries). 

# __General advice and websites recommendation__
* **It's best to do research on how to use Linux instead of jumping ship and expect the same workflow as on Windows. This is one of the many newbie traps!!**
* Don't install packages from the internet unless necessary. Always trust your SOFTWARE/PACKAGE MANAGER bundled with your distribution.
* Don't jump the distrohop wagon whenever a new shiny distribution claims to give you better this and better that. Many of those benefits are very negligible and only harm the Linux ecosystem by fragmenting it even further. Use distributions that are popular, mainstream, well-known and come from reputable sources. You can game on any distro and apply the same tweaks on a "non-gaming" distribution.
* Don't rely on custom kernels to give you significant performance gains. Using the kernel bundled with your distribution is more than enough.
* Don't run scripts that claim to give you more performance, especially if they were not tested or come from a untrusted source/maintainer. Those are the equivalent of running registry tweaks on windows to get free fps (aka a scam.)
* Don't rely too much on AI tools to debug your problems, unless you know and read carefully what it gives you instead of blindly copy-pasting.
  
To check if your games work on linux, these websites will help you keep yourself updated:   
https://areweanticheatyet.com/   
https://www.protondb.com/   
https://appdb.winehq.org/
### Websites for linux news (desktops, distributions etc)
https://9to5linux.com/   
https://gamingonlinux.com/
# __Distribution recommendation__
Based on my own experience + community feedback. Treat this as a way to begin your Linux journey. These are mainstream, well-known, supported linux distributions with huge userbases and documentation.
<details>
<summary>Fedora</summary>

\
{[Official Website](https://fedoraproject.org/)} | {[Post-Install Guide](https://github.com/Tenama-hub/Linux_guide_for_Legion/blob/main/fedora_post_install_guide.md)}
* Comes with Gnome/Plasma by default. Offers different flavors of desktops too
* Offers the "vanilla" experience that desktop developers have envisioned
* Regarded as a solid distro with up to date drivers and emphasis on stability
* Great documentation, large user base and security configured OOTB (secure boot needs to be tweaked manually. Check my post-install guide)
* Semi-Rolling release distribution    
> (-) Codecs & Nvidia drivers are not pre-installed (follow the post-install guide). Sometimes a hassle to get them both up and running optimally.\
> (-) No secure boot post-install. Needs to be signed manually.
</details>

<details>
<summary>OpenSUSE Tumbleweed</summary>

\
{[Official Website](https://www.opensuse.org/)} | {[Post-Install Guide(reference video)](https://youtu.be/0T02xd9qVmM?si=_op_kdpDzYjRkK5F)}
* Comes with Gnome/Plasma by default.
* Regarded as a solid distro with up to date drivers and emphasis on stability, especially since it's a rolling release distro
* Pretty good documentation
* Secure boot configured
* Snapper installed & configured by default. Allows you to roll back a bad update
* RPM Based (like Fedora),European (r/BuyFromEU) and automatically optimizes packages based on hardware
* Offers both a rolling release model (Tumbleweed) or LTS (Leap)   
> (-) Codecs & Nvidia drivers are not pre-installed (follow the reference video). Sometimes a hassle to get them both up and running optimally.\
> (-) Bundled sysadmin GUI settings can be confusing for beginners.
</details>

<details>
<summary>Ubuntu / Kubuntu</summary>

\
{[Official Website for Ubuntu](https://ubuntu.com/download)} | {[Official Website for Kubuntu](https://kubuntu.org/)} | {[Post-Install Guide](https://github.com/Tenama-hub/Linux_guide_for_Legion/blob/main/ubuntu_post_install_guide.md)}
- Comes with Gnome (Ubuntu) or KDE Plasma (Kubuntu) by default. Can use other variants with different desktops
- Pre-install Nvidia drivers and codecs during the installation process
- Pretty good documentation & huge active base
- Secure boot configured
- Offers both a rolling release model or LTS   
> (-) Prioritizes Snaps over any other package formats and may have their own issues (depending on the app). You can still use Debs, Appimages (install GearLever) or Flatpaks (install Warehouse/Bazaar from Flathub) as alternatives.\
> (-) System issues may occur on non-LTS versions.
</details>
<details>
<summary>Linux Mint</summary>

\
{[Official Website](https://linuxmint.com/)} | {[Post-Install guide](https://github.com/Tenama-hub/Linux_guide_for_Legion/blob/main/linux_mint_post_install_guide.md)}
* Comes with Cinnamon/XFCE/Mate (replicate windows 7/10 layout)
* Bundles many useful tools OOTB
* Customizable touchpad gestures like on Windows (Cinnamon only)
* Stable release distribution   
> (-) Lags behind some of the newer technologies and packages, which may cause issues on newer hardware.\
> (-) Still uses X11, which is behind certain modern features (dual screens may not work as intended for example)\
> (-) No secure boot post-install. Needs to be signed manually.
</details>

## If you feel adventurous...

<details>
<summary>Bazzite</summary>

\
{[Official Website](https://bazzite.gg/)}
- Comes with Plasma/Gnome by default
- Pre-installed Steam, Nvidia drivers and codecs
- Can be used for any use case, not just gaming
- Great alternative to SteamOS
- Very hard to break and requires little to no maintenance due to its "atomic" nature
- [Atomic distribution](https://docs.bazzite.gg/General/FAQ/#steamos-is-based-on-arch-linux-so-why-use-fedora-atomic-desktop) based on Fedora. Updates can be done in the background and are relatively quick   
> (-) Apps can only be installed as Flatpaks, AppImages, HomeBrew or through Distrobox/Kontainer.\
> (-) You cannot do system-level changes like on traditional distros, unless you create your own fork of the project.\
> (-) Support outside their official Discord leaves more to be desired.\
> (-) No secure boot post-install. Needs to be signed manually (can be done through Ujust)
</details>

<details>
<summary>EndeavourOS</summary>

\
{[Official Website](https://endeavouros.com/)}
- Comes with Plasma by default. Can install a different desktop environment during the installation process (same for the bootloader)
- Pure Arch Linux experience, with several tools and tuning done to get you up and running
- Bleeding edge distribution based on Arch Linux, which means you will get frequent updates
- Nvidia drivers pre-installed
- Great documentation & community
> (-) More terminal focused, as it doesn't come bundled with a GUI package manager.\
> (-) Updates can go bad due to it's bleeding edge nature and you will experience several bugs here and there.\
> (-) AUR isn't the safeset place to get your packages from.\
> (-) Requires prior linux knowledge in order to properly use it. Not suitable for newbies or for production environments.\
> (-) No secure boot post-install. Needs to be signed manually.
</details>

<details>
<summary>CachyOS</summary>

\
{[Official Website](https://cachyos.org/)} | {[Post-Install guide](https://wiki.cachyos.org/configuration/post_install_setup/)}
- Comes with Plasma by default. Can install a different desktop environment during the installation process (same for the bootloader)
- Pre-configured snapshots in case updates go bad (If you choose BTRFS+Limine by default)
- One-click install for gaming packages (Steam, Lutris, Heroic, Mangohud with Goverlay + libraries needed) + nvidia drivers pre-installed
- A functional software center that allows installing AUR and Flatpaks
- Bleeding edge distribution based on Arch Linux, which means you will get frequent updates
- Optimized for your hardware, meaning you can get a boost in performance
- Great documentation (wiki.cachyos.org)
> (-) "Optimizations" only apply to certain specific scenarios (Gaming isn't one of them).\
> (-) Updates can go bad due to it's bleeding edge nature and you will experience several bugs here and there.\
> (-) AUR isn't the safeset place to get your packages from.\
> (-) Requires prior linux knowledge in order to properly use it. Not suitable for newbies or for production environments.\
> (-) No secure boot post-install. Needs to be signed manually.
</details>

# __Distributions to avoid!__
<details>
<summary>Debian (stable branch)</summary>

\
  **Unless you use Debian sid/testing, it is not suitable for legion laptops. Updates (especially MAJOR ones) are released very slowly and packages tend to get outdated pretty quick.**
</details>
<details>
<summary>Pop!_OS</summary>

\
  **The new Cosmic desktop variant lacks critical fixes for gaming and it is still currently in alpha. For now, there are better options.**
</details>
<details>
<summary>SteamOS</summary>

\
  **Doesn't have an nvidia alternative and is not finished for **non-handheld devices**. If you REALLY need something similar, use Bazzite.**
</details>
<details>
<summary>Manjaro</summary>

\
  **It's future is uncertain as it has a history of a lot of wrongdoings, strange decisions and updates that led to broken systems or significant bugs. Is currently on a hiatus due to [disagreements and developers being on strike](https://forum.manjaro.org/t/manjaro-2-0-manifesto/186171). There are much better options out there.**
</details>
<details>
<summary>Business-related distributions</summary>

\
  **Oracle Linux, Clear Linux or anything made for business purposes. Self explanatory.**
</details>
<details>
<summary>Hacking/Cybersecurity distributions</summary>

\
  **Parrot, Tails, Kali Linux and alike are meant to be used either through VMs or external devices, not on actual hardware.**
</details>
<details>
<summary>Obscure/outdated distributions</summary>

\
  **Avoid distributions maintained by randoms/single developer, that are **"too good to be true"** (nonsense promises) or try to replicate Windows 1:1.**
</details>
<details>
<summary>Hobby/niche distributions</summary>

\
  **Do keep in mind you won't have any guarantee they won't die off in the future or have support outside their forums (forums being just a Discord server). They also come with issues of their own (unorthodox way of handling packages, low-quality in-house tools, kernel problems, questionable community, very low amount of maintainers etc). Their soley purpose is to fill a niche that can be accomplished on any modern, mainstream distributions.\
Some example of such distros are Nobara, RegataOS, Garuda, ZorinOS, PikaOS etc.**
</details>

# __Installing Legion tools and drivers__ 
### **As of Kernel 6.17, power profiles switching and battery conservation don't require the Legion Driver.**   
This allows you to use most, if not all the legion exclusive features on linux (fan control, panel overdrive, etc). Comes with a GUI to easily access these said features.   
If you use Plasma and you want to have a tool that gives you the important options at a glance, I recommend using [PlasmaVantage](https://gitlab.com/Scias/plasmavantage) or Cinnamon's inspired counterpart from the [desktop plugin store](https://cinnamon-spices.linuxmint.com/applets/view/395)   
## Distro packages (highly recommended)
- [**Debian/Ubuntu**](https://github.com/MrDuartePT/pacstall-programs/tree/lll-repo)
- [**Fedora**](https://copr.fedorainfracloud.org/coprs/mrduarte/LenovoLegionLinux/)
  - [Alternate link](https://mrduartept.github.io/LLL-pkg-repo)
- **Arch Linux**:
    - [lenovolegionlinux-git](https://aur.archlinux.org/packages/lenovolegionlinux-git)
    - [lenovolegionlinux-dkms-git](https://aur.archlinux.org/packages/lenovolegionlinux-dkms-git)
- **Gentoo**:
    - [GURU Overlay](https://gitweb.gentoo.org/repo/proj/guru.git)
    - [ebuild](https://gpo.zugaina.org/sys-firmware/lenovolegionlinux)
- [**NixOS**](https://search.nixos.org/packages?channel=unstable&from=0&size=50&sort=relevance&type=packages&query=lenovo-legion)
## Manual Install Module
The project's [github page](https://github.com/johnfanv2/LenovoLegionLinux?tab=readme-ov-file#bulb-instructions) should give you enough instructions to aid you in the process.\
After it's done, to check if module is built and installed correctly, enter the following command
```sudo lsmod |grep legion_laptop```\
The output should show that legion_laptop and platform profile modules are loaded.

# __App & Tools recommendation__
### [Bazaar](https://flathub.org/en/apps/io.github.kolunmi.Bazaar)
Front-end for managing Flatpak packages, if your distribution's package manager is not good enough for this use case. Used by default on Bazzite.
### [Retrodeck](https://flathub.org/en/apps/net.retrodeck.retrodeck)
An all-in-one emulation front-end that comes with the most popular emulators, pre-configured OOTB. You can configure and add BIOS files for each component through its configurator app.
### [Easyeffects](https://flathub.org/en/apps/com.github.wwmm.easyeffects)
Front-end equalizer for managing your microphone and speakers. Want to filter your microphone background sounds? Want to have a better sound quality? Then this app is for you.
### [Warehouse](https://flathub.org/en/apps/io.github.flattool.Warehouse)
All-in-one flathub package manager (install flatpaks, delete leftover data, manage flatpak data). A more technical variant of Bazaar.
### [Flatseal](https://flathub.org/en/apps/com.github.tchx84.Flatseal)
Manage Flatpak permissions. Useful for non-KDE Plasma distributions.
### [GearLever](https://flathub.org/en/apps/it.mijorus.gearlever)
Front-end Appimage manager. Allows "installing" said packages, without needing to fetch them in the file manager.
### [PeaZip](https://flathub.org/en/apps/io.github.peazip.PeaZip)   
A fantastic WinRar/7-Zip alternative.
# __Battery saving tools__
The tool that comes bundled with your distribution of choice should be good enough. For advanced users only!
> [!WARNING]
> Some of the tools will not work together with the rest (exceptions may apply). Make sure you remove all the tools besides the one you want to currently use.\
> Do **NOT** use configuration files from laptops you don't **OWN**. This may cause severe issues with your hardware! You have been warned.
### Tuned 
A mix between power profiles daemon and TLP. Easily integrated with all desktops that feature Power profiles switching and can be customized to your needs. Used on Fedora & Bazzite by default.
[More info](https://github.com/redhat-performance/tuned)
### Power Profiles Daemon
Used in majority of distros. Plays well with pstate scalers and any hardware in general. Not as powerful as TLP but it gets the job done. Conflicts with the rest of the tools besides powertop
[More info](https://gitlab.freedesktop.org/upower/power-profiles-daemon)
### TLP 
A shell script that applies extensive configurations based on battery or AC. Will cause issues if incorrectly configured. Conflicts with other tools.   
- **Debian/Ubuntu**:
```sudo apt install tlp```
- **Fedora**:
```sudo dnf install tlp```
- **Arch Linux**:
```sudo pacman -S tlp```
   
For easier tool access, [install the gui version](https://github.com/d4nj1/TLPUI)   
After that we can configure TLP.   
Open TLPUI and change your settings(Strictly optional. Default settings are fine) . Enable the tool by typing in terminal:   
```sudo systemctl enable tlp.service && sudo systemctl start tlp.service```
### Auto-Cpufreq
A simple script that changes how the cpu should scale depending if you are on AC or Battery. Plays well with pstate, but it may cause issues with some hardware.
- **Debian/Ubuntu**:
```git clone https://github.com/adnanhodzic/auto-cpufreq.git && cd auto-cpufreq && sudo ./auto-cpufreq-installer```
- **Fedora**:
```git clone https://github.com/adnanhodzic/auto-cpufreq.git && cd auto-cpufreq && sudo ./auto-cpufreq-installer```
- **Arch Linux**:
```sudo pacman -S auto-cpufreq```
   
[More Info](https://github.com/AdnanHodzic/auto-cpufreq/tree/fdb20f5ea2f94ed9146299b87ad03dc1f64c79ec#auto-cpufreq-installer)
### Powertop 
A shell script tool that allows you to optimize some parts of the hardware to go on a low power state when not in use. I'd recommend using it only to check your power draw, as the optimization feature is already applied by other power saving tools.
- **Debian/Ubuntu**:
```sudo apt install powertop```
- **Fedora**:
```sudo dnf install powertop```
- **Arch Linux**:
```sudo pacman -S powertop```

After installing it, you can use the app by typing:   
```sudo powertop```   
If you want to use it to optimize the hardware power usage (power-profiles/auto-cpufreq ONLY), run this command:   
```sudo powertop --calibrate && sudo powertop --auto-tune```

# __Wine front-ends__
[Wine](https://www.winehq.org/) is a special tool that allows running Windows apps in Linux. This sparked the creation of proton, that is actively used for games.
### [Lutris](https://lutris.net/)
Allows installing, configuring games & apps in one-in-all tool. Comes with features like automatic installation of games through community patches and importing game libraries from steam, GOG and Epic Games Store. Avoid using install scripts as all of them rely on the outdated wine-ge runner.
### [Heroic game launcher](https://heroicgameslauncher.com/) 
Allows installing & configuring games & apps in one-in-all tool from Epic Games Store, Humble, Amazon, GoG, Origin, Ubisoft Connect and local games/backups.
### [Faugus-Launcher](https://github.com/Faugus/faugus-launcher) 
A simple, easy to use launcher that takes advantage of [UMU](https://github.com/Open-Wine-Components/umu-launcher). It's not as feature complete as Lutris, but it gets the job done without extra shenanigans.
### [Port-Proton](https://github.com/Castro-Fidel/PortWINE)
Formerly PortWINE. It's simple to use, can auto-install game launchers and has enough configuration tools, as well as a special prefix with dotnet frameworks preinstalled. There are some trust issues (mainly the dev is Russian, take that how you will), doesn't allow custom wine launch options, apps start slower than the competition and some options are counter-intuitive. Use this as a last resort.

# __General bugs and fixes__
<details>
<summary>System swappiness (if you have >= 16GB ram)</summary>
  
* Setting your swappiness to 10 will reduce stuttering when your RAM memory is almost full, as the system will not prioritize using your SWAP partition as system memory for apps.
* ```sudo nano /etc/sysctl.conf```
* Add ```vm.swappiness=10``` Then save. (ctrl+O then hit enter)
</details>
<details>
<summary>Zram tweaks</summary>

* (Make sure your distributon has zram enabled by running ```zramctl``` in the terminal!)
* If you have games crashing due to memory leaks, tweaking zram would help ameliorate the problem. To do so, do the following:
* ```sudo nano /etc/systemd/zram-generator.conf```
* Inside the new configuration file, paste this:   
```[zram0]```\
```compression-algorithm=zstd```\
```zram-size = min(ram / 2, 16384)```\
* Save & Reboot. What this does is it tweaks zram to compress half of your total ram. While it will fix games crashing due to low ram, it will also add a little performance hit. It shouldn't be noticable at all.
</details>
<details>
<summary>Bad speakers quality</summary>

* If your speakers sound shallow and bad, try out [this preset](https://github.com/Tomiscout/Lenovo-Legion-5-Pro-Linux-guide/tree/main/easyeffects). If you use handhelds, [better give this one a try](https://www.reddit.com/r/LegionGo/comments/1m7632y/legion_go_s_steam_os_audio_fix_pipewire_eq/).
* If you don't want to use Easyeffects for your legion laptop, download & extract the pipewire archive in .config, open convolver-sink.conf and change YOURUSERNAME with your linux's username.\
  Restart pipewire and change your sound profile in settings.
</details>
<details>
<summary>Bad laptop mic quality</summary>

* Set your microphone volume to 30-50%, then install this [noise cancelling module](https://github.com/Rikorose/DeepFilterNet/blob/main/ladspa/README.md) or use EasyEffects\NoiseTorch.
</details>



<details>
<summary>Refresh rate/ VRR not working</summary>
  
* Some screen panels will force you to use either the highest or the lowest refresh rate (even keep you at the highest resolution). Edid.bin tells your screen what resolutions and refresh rates it supports. This is a problem that affects some panels due to generic drivers being used instead of the ones provided by the screen providers.
1. In WINDOWS, download the CRU tool. Open it, then click on **EXPORT**. Save the file as edid.bin. (Make sure that you can see your refresh rates in Windows too. Otherwise, add them by yourself, then
2. Copy the file to a usb drive and boot back to linux.
3. Open a terminal and type the following commands:
```cd /lib/firmware && sudo mkdir edid && sudo cp (path to file)/edid.bin /lib/firmware/edid```
4. To make sure your edid file is recognized, use the following:   
```for p in /sys/class/drm/*/status; do con=${p%/status}; echo -n "${con#*/card?-}: "; cat $p; done```
   
For the below commands, replace {display_id} with the output of the connected display from the command in number 4.
### For systemd-boot
```sudo kernelstub -a 'drm.edid_firmware={display_id}:edid/edid.bin video={display_id}:e'```
### For GRUB:
```sudo nano /etc/default/grub```, add ```drm.edid_firmware={display_id}:edid/edid.bin video={display_id}:e``` to **GRUB_CMDLINE_LINUX_DEFAULT**

Then run either ```sudo update-grub``` or ```sudo grub2-mkconfig -o /boot/grub2/grub.cfg```    
Reboot.   
### For Immutable/atomic distros based on Fedora( e.g. Bazzite), use the following (make sure you replace {display_id} with the output from number 4, as well as path-to-file with the actual path):
```
sudo mkdir -p /etc/firmware/edid
sudo cp (path-to-file)/edid.bin /etc/firmware/edid
sudo rpm-ostree kargs --append-if-missing=drm.edid_firmware={display_id}:edid/edid.bin
sudo rpm-ostree kargs --append-if-missing=video={display_id}:e
```
In case it hasn't fixed yet, run these 2 as well:
```   
sudo echo 'install_items+=" /etc/firmware/edid/edid.bin "' | sudo tee /etc/dracut.conf.d/edid.conf
sudo rpm-ostree kargs --append-if-missing=firmware_class.path=/etc/firmware 
```
</details>


> [!WARNING]
> UNDER NO CIRCUMSTANCE, DO NOT INCREASE/DECREASE THE RESOLUTION OF YOUR SCREEN/REFRESH RATE PAST YOUR SPECS! DOING SO WILL CAUSE SEVERE ISSUES!
