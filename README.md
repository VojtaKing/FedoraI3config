Fedora i3 Config

Minimalist and functional configuration files for a Fedora-based i3 window manager setup.

Requirements

Make sure the following packages are installed:

i3 – Tiling window manager

polybar – Status bar replacement

rofi – Window switcher, application launcher

dunst – Lightweight notification daemon

btop – Resource monitor

helix – Text editor

zathura – PDF and document viewer

thunar – File manager

fastfetch – System info tool

dconf – Configuration system (for GTK and desktop settings)

On Fedora, you can install them via:
```bash
sudo dnf install i3 polybar rofi dunst btop helix zathura thunar fastfetch dconf
```
Installation

Clone the repository and copy the config files to your home directory: 
```bash
git clone https://github.com/VojtaKing/fedora-i3-config.git
cd fedora-i3-config
```
# Copy configs to your .config directory
```bash
cp -r .config ~/.config/ && cp -r pictures ~/Pictures
```
