<div align = center>
  
![Hyprland logo](README/Hyprland.webp)

</div>

<br>

<div align = center>
  
*Hi :wave:, I use Archlinux together with Hyprland. I made myself a gruvbox-style desktop environment. That's fine with me :smirk:*

</div>

<br>

### How it looks :stuck_out_tongue:

<br>

![Preview A]

<br>

![Preview B]

<br>

![Preview C]

<br>

### Installation:

<br>

1. Using the Pacman package manager :point_down:
```bash
$ sudo pacman -S sudo git neovim networkmanager base-devel
$ sudo pacman -S mesa nvidia-open
$ sudo pacman -S pipewire pipewire-alsa pipewire-pulse pipewire-jack wireplumber 
$ sudo pacman -S hyprland xdg-desktop-portal-hyprland hyprpolkitagent qt5wayland qt6wayland
$ sudo pacman -S hyprlock hyprpaper dunst kitty eza wofi zsh ttf-jetbrains-mono-nerd
$ sudo pacman -S waybar vlc libreoffice-stable viewminor btop
$ sudo pacman -S telegram-desktop firefox qbittorrent network-manager-applet
$ sudo pacman -S ntfs-3g p7zip unrar gzip bzip2 xz unzip
$ sudo pacman -S thunar thunar-volman gvfs-mtp gvfs gvfs-gphoto2 mtpfs android-udev thunar-archive-plugin file-roller
$ sudo pacman -S tumbler ffmpegthumbnailer
$ sudo pacman -S bluez bluez-utils blueberry
$ sudo pacman -S lxappearance nwg-look ark-gtk-theme
$ sudo pacman -S gtk3 gtk4 qt5ct qt6ct 
$ sudo pacman -S grim slurp
```
<br>

2. Installing Pacman wrapper and AUR helper - **yay** :baby_bottle:
```bash
git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si
cd ..
rm -rf yay
```

<br>

3. Using the yay :sunglasses:
```bash
yay -S candy-icons-git
yay -S wlogout
```



<!----------------------------------{ Images }--------------------------------->

[Preview A]: https://github.com/dark-tonzako/hyprland/blob/main/README/sc1.png
[Preview B]: https://github.com/dark-tonzako/hyprland/blob/main/README/sc2.png
[Preview C]: https://github.com/dark-tonzako/hyprland/blob/main/README/sc3.png
