# a minimal opinionated fork of [HyDE](https://github.com/HyDE-Project/HyDE)

![hyde_banner](source/assets/hyde_banner.png)


# TODO:
- ssh-agent.service installation
- fix waybar

# installation

```sh
git clone --depth 1 https://github.com/HyDE-Project/HyDE ~/HyDE
cd ~/HyDE/scripts
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