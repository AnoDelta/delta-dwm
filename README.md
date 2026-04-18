# Delta-dwm

My personal dwm (dynamic window manager) build.

## Patches applied
- pertag — each tag remembers its own layout
- attachbottom — new windows attach at bottom of stack
- swallow — terminals swallow child GUI windows
- systray — system tray in the bar
- uselessgap — gaps between windows
- appicons — application icons in the bar
- winicon — window icons in the bar

## Dependencies
- libX11
- libXft
- libXinerama
- libXrandr
- [delta-st](https://github.com/AnoDelta/delta-st) — terminal
- [delta-slstatus](https://github.com/AnoDelta/delta-slstatus) — status bar
- [delta-dmenu](https://github.com/AnoDelta/delta-dmenu) — app launcher
- [dotfiles](https://github.com/AnoDelta/dotfiles) — shell scripts, xinitrc, start-dwm-session

## Optional
- [delta-slock](https://github.com/AnoDelta/delta-slock) — lock screen

## Install
```sh
git clone https://github.com/AnoDelta/delta-dwm.git
cd delta-dwm
make && sudo make install
```
