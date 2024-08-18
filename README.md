
# ArchLinux /w Hyprland Su**less Config


![Logo](./example.png)

## Preparation

1. Install **ArchLinux**, base install, pipewire, wireplumber, wayland, 
2. Install appropriate gpu/libva/vulkan **driver for you GPU**, hw accelleration needed in order to run hyprland
3. install the following packages

**Official Repo (w/ Pacman)**
- hyprland
- waybar
- pamixer
- playerctl
- pavucontrol
- brightnessctl
- ttf-font-awesome
- ttf-jetbrains-mono
- ttf-iosevka-nerd
- ttf-opensans
- nwg-look
- qt5ct
- qt6ct
- ttf-hack
- kvantum
- breeze-icons
- yad
- mako
- cliphist
- hyprpaper
- network-manager-applet
- blueman
- thunar
- alacritty
- polkit-kde-agent
- sddm
- otf-font-awesome
- gvfs
- hypridle
- hyperlock

**AUR**
- wlogout
- arc-gtk-theme
- hyprshot


## Dot Files Installation

1. Configure **hyprland** by copying the folder ``hypr`` under ``~/.config/hypr``
2. Configure **waybar** by copying the folder ``waybar`` under ``~/.config/waybar``
3. Configure **mako** by copying the folder ``mako`` under ``~/.config/mako``
4. Configure **gtk** by copying the ``gtk*`` files and folders under ``~/.config``

## Wallpaper

This configuration will look for ``~/.config/hypr/wallpaper/bg.jpg`` file, you can edit this behaviour in ``~/.config/hypr/hyprpaper.conf``


## Missing feature
1. clean the gtk mess
2. configure font
3. configure sleep and lock