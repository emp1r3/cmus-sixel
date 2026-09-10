# cmus-sixel
album art in cmus with terminals that support sixel graphics which most do even minimal ones like st terminal.
it is minimal and posix compliant and easy to use. have fun xD

## Requirements
- Terminal with sixel support
- ffmpeg
- img2sixel

### Install
```sh
cp cmus-sixel.sh ~/.config/cmus/
chmod +x ~/.config/cmus/cmus-sixel.sh
cmus-remote -C "set status_display_program=~/.config/cmus/cmus-sixel.sh"
```
### Bonus
you can also run the script standalone in a different terminal to print the current playing song album cover.
```sh
sh cmus-sixel.sh && echo
```
