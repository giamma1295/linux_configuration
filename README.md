
# ArchLinux /w Hyprland Minimal Config
Minimal Hyprland configuration with alacritty, mako, thunar, waybar, wofi and so on...
 

<div style="text-align: center;">
  <img src="./images/main.png" alt="Hyprland Home" />
  <p>Home</p>
</div>
<div style="text-align: center;">
  <img src="./images/terminal.png" alt="2 alacritty Instances" />
  <p>Terminal: Alacritty</p>
</div><div style="text-align: center;">
  <img src="./images/thunar.png" alt="Alacritty and Thunar" />
  <p>FileManager:Thunar</p>
</div>

## Preparation

1. Install **ArchLinux**, base install, pipewire, wireplumber, wayland, 
2. Install appropriate gpu/libva/vulkan **driver for you GPU**, hw accelleration needed in order to run hyprland
3. install the following packages

**Official Repo (w/ Pacman)**
- alacritty
- breeze-icons
- brightnessctl
- blueman
- cliphist
- fuse2
- gtk4
- gvfs
- hypridle
- hyprland
- hyprlock
- hyprpaper
- imagemagick
- kvantum
- libadwaita
- mako
- network-manager-applet
- nwg-look
- noto-fonts
- otf-font-awesome
- pamixer
- papirus-icon-theme
- pavucontrol
- playerctl
- polkit-kde-agent
- qt5ct
- qt6ct
- sddm
- thunar
- thunar-archive-plugin
- tumbler
- ttf-font-awesome
- ttf-fira-sans 
- ttf-fira-code 
- ttf-firacode-nerd
- ttf-hack
- ttf-opensans
- waybar
- wofi
- xarchiver
- xdg-user-dirs
- xdg-desktop-portal
- yad
- zip

**AUR**
- arc-gtk-theme
- bibata-cursor-theme
- hyprshot
- wlogout


## Dot Files Installation

1. Configure **hyprland** by copying the folder ``dotfiles/hypr`` under ``~/.config/hypr``
2. Configure **waybar** by copying the folder ``dotfiles/waybar`` under ``~/.config/waybar``
3. Configure **mako** by copying the folder ``dotfiles/mako`` under ``~/.config/mako``
4. Configure **gtk** by copying the ``dotfiles/gtk*`` files and folders under ``~/.config``
5. Configure **qt** by copying the ``dotfiles/qt6ct`` folder under ``~/.config/qt6ct``
6. Configure **alacritty** by copying the ``dotfiles/alacritty`` folder under ``~/.config/alacritty``

## Wallpaper

This configuration will look for ``~/.config/hypr/wallpaper/minimal-bg.jpg`` file, you can edit this behaviour in ``~/.config/hypr/hyprpaper.conf`` linking your favourite image.


## Missing feature
1. Configure sleep and lock
2. Re-check package list
3. Create a script to automate this installation!