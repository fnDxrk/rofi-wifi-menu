# rofi-wifi-menu

A Wi-Fi menu written in bash. Uses rofi and nmcli. Forked from [ericmurphyxyz](https://github.com/ericmurphyxyz/rofi-wifi-menu) 

![Screenshot of rofi-wifi-menu](https://github.com/user-attachments/assets/dc3ec766-dcdc-49c9-980b-387619385fed)

### Installation

**Archlinux :**
```
yay -S networkmanager ttf-jetbrains-mono-nerd rofi-git
```
If you want to use the icons, set your Rofi font to a [Nerd Font](https://github.com/ryanoasis/nerd-fonts). Then run the following commands:

```bash
git clone https://github.com/fnDxrk/rofi-wifi-menu.git
cd rofi-wifi-menu
./wifi-menu.sh
```

### Setup

1. **Add ~/.local/bin to your PATH** (required to run wifi-menu from anywhere): 

Add the following line to your shell configuration file:

```bash
export PATH="$HOME/.local/bin:$PATH"
```

After adding, reload your shell configuration or restart the terminal.

2. **Copy and run the script:**
```bash
cp wifi-menu.sh ~/.local/bin/wifi-menu
wifi-menu
```
