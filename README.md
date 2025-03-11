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

<br>

4. Set up zsh :wrench:
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
git clone https://github.com/zsh-users/zsh-autosuggestions ~/.oh-my-zsh/custom/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ~/.oh-my-zsh/custom/plugins/zsh-syntax-highlighting

```
Find the line with plugins=(...) in the ~/ file.zshrc and add the names of the plugins
```
plugins=(git zsh-autosuggestions zsh-syntax-highlighting)

```

<br>

5. Set up neovim :page_with_curl:
   - I use the [AstroNvim](https://astronvim.com/) framework 
```bash
git clone --depth 1 https://github.com/AstroNvim/template ~/.config/nvim
rm -rf ~/.config/nvim/.git
nvim
```

<br>

6. Set GTK theme :bird:
```bash
nwg-look
```
Choose a theme **Matherial Dark**

### How to run :ghost:

I don't use display managers, so I just write **Hyprland**, but you can put an [sddm](https://github.com/sddm/sddm), for example, to automatically start Hyprland.



<!----------------------------------{ Images }--------------------------------->

[Preview A]: https://github.com/dark-tonzako/hyprland/blob/main/README/sc1.png
[Preview B]: https://github.com/dark-tonzako/hyprland/blob/main/README/sc2.png
[Preview C]: https://github.com/dark-tonzako/hyprland/blob/main/README/sc3.png
