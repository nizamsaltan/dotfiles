# [Insert nice header and desc]


## Dependencies
- i3-gaps
- polybar
- picom
- rofi

### Optional
- feh -> wallpaper, image viewer
- dunst -> notification manager
- polkit-gnome-authentication-agent -> authentication agent
- xfce4-screenshooter -> screenshot


#### For polybar spotify module 🎵

https://github.com/Jvanrhijn/polybar-spotify
(script is preinstalled)

- Python (2.x or 3.x)
- Python [dbus](https://pypi.org/project/dbus-python/ "dbus") module
- playerctl


## My personal preferences
These dotfiles works perfectly with these apps, but of course you can change them as your taste

- Thunar (file manager)
- Mousepad (basic text editor)
- Shotwell (Image viewer)
- Dunst (notification deamon)
- xfce4-screenshot
- Fonst: [Poppins](https://fonts.google.com/specimen/Poppins?query=Popp "Poppins Font"), [DM Mono](https://fonts.google.com/specimen/DM+Mono?query=DM+Mon "DM Mono Font")
- [Colloid icon theme](https://github.com/vinceliuice/Colloid-icon-theme "Colloid icon theme")
- [Fluent light gtk theme](https://github.com/vinceliuice/Fluent-gtk-theme "Fluent light")
- [Wallpaper: twitter - u/michaelboegl](https://twitter.com/michaelboegl/status/1607831306838097920?s=20 "Wallpaper twitter - u/michaelboegl")

# Screenshots
[![Home](https://raw.githubusercontent.com/nizamsaltan/dotfiles/main/Screenshot_2023-01-21_12-29-15.png "Home")](https://raw.githubusercontent.com/nizamsaltan/dotfiles/main/Screenshot_2023-01-21_12-29-15.png "Home")
[![Thunar & Shotwell](https://raw.githubusercontent.com/nizamsaltan/dotfiles/main/Screenshot_2023-01-21_12-17-46.png "Thunar & Shotwell")](https://raw.githubusercontent.com/nizamsaltan/dotfiles/main/Screenshot_2023-01-21_12-17-46.png "Thunar & Shotwell")
[![Code](https://raw.githubusercontent.com/nizamsaltan/dotfiles/main/Screenshot_2023-01-21_12-07-25.png "Code")](https://raw.githubusercontent.com/nizamsaltan/dotfiles/main/Screenshot_2023-01-21_12-07-25.png "Code")
[![Spotify](https://raw.githubusercontent.com/nizamsaltan/dotfiles/main/Screenshot_2023-01-21_12-03-56.png "Spotify")](https://raw.githubusercontent.com/nizamsaltan/dotfiles/main/Screenshot_2023-01-21_12-03-56.png "Spotify")

------------

## Notes

### Transparency
there is also a litte bit of transparency with some beautiful blur effect on some apps. You can check full list is in here (to change them, head over to $HOME/.config/picom/picom.conf)

for example 95% transparency in 'vscode'
- "95:class_g = 'Code'",
- "88:class_g = 'discord'",
- "90:class_g = 'Spotify'",
- "80:class_g = 'Blueman-manager'",
- "90:class_g = 'Steam'",
- "95:class_g = 'unityhub'",
- "100:class_g = 'firefox'",
- "100:class_g = 'Unity'",
- "100:class_g = 'jetbrains-rider'",

### Wallpaper
Wallpaper defined inside i3 config file which uses 'feh' for image viewer. To change wallpaper, check /usr/share/wallpapers/wallpaper.jpg and of course you can change image format

### Basic shortcuts
These are my personal shorcuts. Most of them placed inside i3 config file.

- $MOD = windows/super key
- $MOD+Q = kill window
- $MOD+Shift+E = power menu
- $MOD+D = rofi
- $MOD+CTRL+'Arrow Keys' = resize window 1px
- $MOD+CTRL+LeftShift+'Arrow Keys' = resize window 10px
- $MOD+Shift+'Arrow Keys' = move window
- $MOD+Shift+S = screenshot region
- $MOD+PrintScreen = fullscreen screenshot
