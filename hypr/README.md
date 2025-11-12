# Hyprland Configuration Guide

## 1. hyprland.conf

Change the following lines according to your preferred programs:

```ini
# Set programs that you use
$terminal = kitty
$fileManager = dolphin
# $menu = wofi --show drun
$menu = walker
$browser = zen-browser
```

These rules create individual opacity settings for specific programs:

```ini
windowrulev2 = opacity 0.85 0.7, class:^(kitty)$
windowrulev2 = opacity 0.93 0.7, class:^(code-oss)$
windowrulev2 = opacity 1.0 override 1.0 override, class:^(discord)$
```

---

## 2. hypridle.conf

The following lines check whether the user is currently in a Discord call.  
If a call is active, the system will **not** lock the screen:

```bash
bash -c 'if ! pw-cli ls Node | grep -q "WEBRTC VoiceEngine"; then pidof hyprlock || hyprlock; else echo "Call active, skipping lock"; fi'
```

---

## 3. hyprpaper.conf

Update the paths to your wallpaper files and modify the monitor settings as needed.
