# a minimal opinionated fork of [HyDE](https://github.com/HyDE-Project/HyDE)
<div align = center>
  <a href="https://discord.gg/AYbJ9MJez7">
    <img alt="Dynamic JSON Badge" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fdiscordapp.com%2Fapi%2Finvites%2FmT5YqjaJFh%3Fwith_counts%3Dtrue&query=%24.approximate_member_count&suffix=%20members&style=for-the-badge&logo=discord&logoSize=auto&label=The%20HyDe%20Project&labelColor=ebbcba&color=c79bf0">
  </a>
</div>

###### _<div align="right"><a id=-design-by-t2></a><sub>// design by t2</sub></div>_

![hyde_banner](Source/assets/hyde_banner.png)

<br>

&nbsp;|&nbsp;
<span><a href="#installation">Installation</a></span>&nbsp;|&nbsp;
<span><a href="#updating">Updating</a></span>&nbsp;|&nbsp;
<span><a href="#themes">Themes</a></span>&nbsp;|&nbsp;
<span><a href="#styles">Styles</a></span>&nbsp;|&nbsp;
<span><a href="CONTRIBUTING.md">Contributing</a></span>&nbsp;|&nbsp;
<span><a href="KEYBINDINGS.md">Keybindings</a></span>&nbsp;|&nbsp;
<span><a href="https://www.youtube.com/watch?v=2rWqdKU1vu8&list=PLt8rU_ebLsc5yEHUVsAQTqokIBMtx3RFY&index=1">Youtube</a></span>&nbsp;|&nbsp;
<span><a href="https://hydeproject.pages.dev/">Wiki</a></span>&nbsp;|&nbsp;
<span><a href="https://discord.gg/qWehcFJxPa">Discord</a></span>&nbsp;|&nbsp;

<br><br>

# TODO:
- reinstall with btrfs/timeshift/grub
- set default theme, 
- customize/replace rofi for better app launcher
- dotfiles integration


# installation

```sh
git clone --depth 1 https://github.com/HyDE-Project/HyDE ~/HyDE
cd ~/HyDE/Scripts
./install.sh
reboot
```

# tips
- to install custom apps
```sh
./install.sh pkg_user.lst
```
- to install Arch Linux use archinstall.config.json as a template for Arch installation
```sh
archininstall --config-url https://raw.githubusercontent.com/marcoscannabrava/hyde/refs/heads/mc/minimal/archinstall.config.json
# 1. modify the partitioning according to your HD - suggestion: BTRFS with default submodules, compression, and timeshift for snapshots
# 2. create root and regular users 
```
- for extra documentation refer to:
  - https://github.com/HyDE-Project/HyDE - original project
  - https://github.com/hyprwm/Hyprland
  - https://archlinux.org/