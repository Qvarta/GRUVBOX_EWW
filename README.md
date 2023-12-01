# My Eww Dotfiles for Hyprland.


This is my personal eww dotfiles repository. All widgets are EWW.

OLD:
![preview](eww/images/screenshot/1.jpg)

NEW(at work...):
https://github.com/Qvarta/GRUVBOX_EWW/assets/145424608/b4bea2cf-bab9-4639-9bde-b8ec41dc4c35

### Requirements

- hyprland
- eww
- jq(multiple scripts)
- curl(weather script)
- socat(workspace script)
- bluez
- bluez-utils
- brightnessctl
- NetworkManager
- pavucontrol
- mako(notification)
- swww(change background)
- imagemagick(background script)
- cmus(palyer script)
- hyprshot(screenshot script)
- Iosevka Nerd Font

### Installation

1. If is not installed, install Archlinux using archinstall, selecting the profile -desktop -Hyprland.
2. Clone this repository.

	```bash
	$ git clone https://github.com/Qvarta/eww_dots.git
	```

3. Make 'install' executable. Run it and follow the instructions.

	```bash
        cd eww_dots
        chmod +x install
        ./install
	```

### Configuration

1. Edit var.conf in ~/.config/eww/ to set up your devices and language.

	```bash
        micro ~/.config/eww/var.conf
	```
2. For some scripts to work correctly, the packages specified in Requirements.

