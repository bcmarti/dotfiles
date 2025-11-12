# Dotfiles Setup Guide

This repository contains configuration files for Hyprland and related tools.

## Requirements

Make sure the following packages and tools are installed:

- **Hyprland**  
- **Hypridle**  
- **Hyprlock**  
- **Hyprpaper**  
- **Walker and Elephant tools**:  
```bash
yay -S walker-bin elephant elephant-providerlist elephant-desktopapplications
```
- **Waybar**  
- **Grimblast** (for screenshots)  
- **Fastfetch**  
- **SDDM Astronaut Theme**:  
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/keyitdev/sddm-astronaut-theme/master/setup.sh)"
```

## Installation

1. Clone this repository into your home directory or preferred location.  
2. Copy the configuration files to their respective locations (e.g., `~/.config/hyprland/`, `~/.config/waybar/`, etc.).  
3. Install all required packages listed above.  
4. Configure the SDDM Astronaut Theme as per the setup script.  

## Notes
 
- Use `Hyprpaper` to set wallpapers for your monitors.  
- The Walker and Elephant tools provide additional menu and desktop application management.  
- Grimblast is used for screenshots, and Fastfetch displays system info on launch.  
- After installing the SDDM Astronaut Theme, choose the **'black hole'** template and update the `black_hole.conf` as needed.
