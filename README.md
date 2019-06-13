# Dots-and-i3wm
Config of i3wm, i3blocks and usefull scripts

Dependencies:
`sxiv, libimage-exiftool-perl, mupdf-tools, exiv2, atool, odt2txt, sxhkd, docx2txt, highlight, nerd-fonts, lm-sensors, socat, zsh, rxvt-unicode-256color, terminator, xclip, ed, tree, arandr, bc, calcurse, zathura, zathura-djvu, poppler-utils, mpd, mpc, cmus, dbus-x11, libnotify-bin, xautolock, suckless-tools, imagemagick, fonts-inconsolata, fonts-symbola, fonts-linuxlibertine, vifm, ranger, python3-pip, python-pip, oh-my-zsh, ranger, lf, gotop, glances, mpv, w3m, feh, maim, slop, pulseaudio, pavucontrol, pulsemixer, pywal, stterm, curl, xclip, vim, neovim, geany, xarchiver, rar, unar, zip, arj, lhasa, weechat, mediainfo, fzf`


As window manager, i use i3wm with i3blocks.  Config of i3wm is in .config/i3 folder. Config of i3blocks is in .config/i3blocks folder. Scripts for i3blocks (scripts for weather, volume, RAM, CPU usage, mpd module and date and time module is in .local/bin folder. Fell fre to modify these).

As fonts (in i3wm, i3blocks and terminals) i use [Nerd-Fonts](https://github.com/ryanoasis/nerd-fonts) Please install these, acording [instructions](https://github.com/ryanoasis/nerd-fonts). Nerd Fonts takes popular programming fonts and adds a bunch of Glyphs. I highly recommend it! 😉

As color theme i use [Atomic](https://github.com/gerardbm/atomic). Atomic color scheme is already included in terminals, i3wm and cmus.

Fot tmux configuration, please check [this](https://github.com/gpakosz/.tmux)

My default shell is zsh. With it i use [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting). It is Fish shell-like syntax highlighting for Zsh 🐟 and [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions). It is Fish-like fast/unobtrusive autosuggestions for zsh 🐠

Install these plugins from the official repositories.

P.S.

A little explanation about i3blocks modules.

`clock` --Shows time and date. If clicked, brings up calender or coming calcuse events.


`cpu` --Shows CPU temperature. If clicked, shows most processor-intensive processes.


`mem` --Shows memory usage. If clicked, shows most memory-intensive processes.


`mediaplayer` --Shows mpd current song.


`volume` -- Shows volume percentage or mute notification. If clicked, brings up pulsemixer. The pulsemixer (very useful and lightwieght terminal app) not in Debian repos. You can install it with pip command `pip3 install --user pulsemixer`


`weather` --Gets weather forcast from wttr.in and returns today's precipitation chance (☔), daily low (snowflake) and daily high (sunny). More info in [wttr.in](https://github.com/chubin/wttr.in).


Also, i want to say big thanks to opensource community and these guys: [LukeSmithxyz](https://github.com/LukeSmithxyz) and [gerardbm](https://github.com/gerardbm) for they ideas😄


And here screenshots:

![Screenshot](screen.png?raw=true "Bussy")
![Screenshot](screen_1.png?raw=true "Clear")
![Screenshot](screen_2.png?raw=true "Notification")
