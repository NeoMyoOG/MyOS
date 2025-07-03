<div align="center">

# MyOS KDE

> [!NOTE]
> I haven't found a way to make a script to copy and paste the configuration files on an easy way, you can use GNU Stow so I would clone this repo on a hidden folder!

</div>

Base:              - Arch Linux

Kernel:            - Linux-Zen

Shell:             - zsh

DE:                - KDE Plasma

![screenshot](Resources/myos-mocha.png)
![screenshot](Resources/myos-latte.png)

#   Appearance


App Style:          Breeze 

App Style GTK:      Breeze 

Plasma Style:       Utterly Round

Colors:             Catppuccin Mocha Mauve // Catppuccin Latte Mauve
```
git clone --depth=1 https://github.com/catppuccin/kde catppuccin-kde && cd catppuccin-kde
./install.sh
```

Window decorations: Breeze 

Fonts:
    
    General:        NotoSans Nerd             10pt
    
    Fixed Width:    NotoSansM Nerd 8pt
    
    Small:          NotoSans Nerd             8pt
    
    Toolbar:        NotoSans Nerd             10pt
    
    Menu            NotoSans Nerd             10pt
    
    Window Title:   NotoSans Nerd             10pt
    
Icons:              Tela Purple Dark (https://store.kde.org/p/1279924)

Cursors:            BreezeX Light (https://store.kde.org/p/1640746)

System Sounds:      Ocean

Splashscreen:       Catppuccin Mocha Mauve

SDDM:               Catppuccin Mocha

Shell:              ohmyzsh! "bira"

   - Install:
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

#   Aplications

Web Browser:        Zen Browser

File Manager:       Dolphin

File Archiver:      Ark

Terminal emulator:  Kitty

Text Editor:        Kate / nano

Office:             OnlyOffice

PDF:                Okular

Image Viewer:       GwenView

Music:              RecordBox

Video:              Haruna

Map:                Google Maps

#   Widgets

-Redmi Clock
-Ginti
-Wallpaper Effects
-Panel Colorizer

#               Build

#   Pacman
```
    - git clone https://aur.archlinux.org/paru-bin.git
    - cd paru-bin/
    - makepkg -si

paru -S --needed base-devel brave-bin btop curl discover e2fsprogs elisa fakeroot fastfetch ffmpeg ffmpeg4 flatpak gimp gst-plugin-pipewire gst-plugins-bad gst-plugins-bad-libs gst-plugins-base gst-plugins-base-libs gst-plugins-good gst-plugins-ugly gstreamer gwenview gzip haruna isoimagewriter kalk kitty linux-zen linux-zen-headers nano noto-fonts noto-fonts-cjk noto-fonts-emoji noto-fonts-extra ntfs-3g onlyoffice-bin partitionmanager pipewire-alsa pipewire-jack pipewire-pulse protonplus qbittorrent spectacle steam unrar unzip wget wireplumber yt-dlp zen-browser-bin zsh

paru -R htop #vim
```

#   flatpak
```
flatpak install flathub com.github.tchx84.Flatseal com.usebottles.bottles ca.edestcroix.Recordbox com.obsproject.Studio com.obsproject.Studio.Plugin.AitumMultistream com.obsproject.Studio.Plugin.GStreamerVaapi com.obsproject.Studio.Plugin.Gstreamer com.obsproject.Studio.Plugin.OBSVkCapture dev.vencord.Vesktop org.prismlauncher.PrismLauncher
```
