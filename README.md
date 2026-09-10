# cmus-sixel
album art in cmus with terminals that support sixel graphics which most do even minimal ones like st terminal.
it is minimal and posix compliant and easy to use. have fun xD
<img width="1920" height="1080" alt="2026-09-10-194319_1920x1080_scrot" src="https://github.com/user-attachments/assets/f3485032-5785-4fb2-afb5-e53090c5da6e" />
<img width="1920" height="1080" alt="2026-09-10-194559_1920x1080_scrot" src="https://github.com/user-attachments/assets/65393b0c-980c-47c9-8529-f04c81c8c9de" />

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
Use the script anyway you like xD
```sh
sh cmus-sixel.sh && echo
```
