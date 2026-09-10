# cmus-sixel
album art in cmus with terminals that support sixel graphics which most do even minimal ones like st terminal.

## Requirements
- Terminal with sixel support
- ffmpeg
- img2sixel

### Install
```sh
cp cmus-sixel.sh ~/.config/cmus/
cmus-remote -C "set status_display_program=~/.config/cmus/cmus_sixel.sh"
```
