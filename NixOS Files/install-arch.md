#   MoriNUX KDE
Base:              - Arch Linux

Kernel:            - Linux-Zen

Shell:             - zsh

DE:                - KDE Plasma

#   Appearance


App Style:          Breeze 

App Style GTK:      Breeze 

Plasma Style:       Fluent Round

Colors:             Catppuccin Mocha Mauve
```
git clone --depth=1 https://github.com/catppuccin/kde catppuccin-kde && cd catppuccin-kde
./install.sh
```

Window decorations: Alba P6 

Fonts:
    
    General:        Noto-sans             10pt
    
    Fixed Width:    Hurmit Nerd Font Mono 10pt (https://www.nerdfonts.com/font-downloads)
    
    Small:          Noto-sans             8pt
    
    Toolbar:        Noto-sans             10pt
    
    Menu            Noto-sans             10pt
    
    Window Title:   Noto-sans             10pt
    
Icons:              Tela Dark (https://store.kde.org/p/1279924)

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

Dialer:             KDE Connect

File Manager:       Dolphin

File Archiver:      Ark

Terminal emulator:  Kitty

Text Editor:        Kate

Office:             LibreOffice

PDF:                Okular

Image Viewer:       GwenView

Music:              Elisa

Video:              Haruna

Map:                Google Maps

#   Widgets
-PlasMusic
-Minimalist Clock
-Ginti
-Start next menu

#               Build

#   Pacman
```
    - git clone https://aur.archlinux.org/paru-bin.git
    - cd paru-bin/
    - makepkg -si

paru -S --needed base-devel brave-bin btop curl discover e2fsprogs elisa fakeroot fastfetch ffmpeg ffmpeg4 flatpak gimp gst-plugin-pipewire gst-plugins-bad gst-plugins-bad-libs gst-plugins-base gst-plugins-base-libs gst-plugins-good gst-plugins-ugly gstreamer gwenview gzip haruna kitty linux-zen linux-zen-headers nano noto-fonts noto-fonts-cjk noto-fonts-emoji noto-fonts-extra ntfs-3g onlyoffice-bin partitionmanager pipewire-alsa pipewire-jack pipewire-pulse protonplus spectacle steam unrar unzip wget wireplumber yt-dlp zen-browser-bin zsh

paru -R htop vim
```

#   flatpak
```
flatpak install flathub com.github.tchx84.Flatseal com.usebottles.bottles
```
