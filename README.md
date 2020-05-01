# Time Machine
This simple backup tool uses zenity as frontend and [laurent22](https://github.com/laurent22/rsync-time-backup) rsync script as backend.

Enjoy the simplicity :)

![time-machine screenshot](https://raw.githubusercontent.com/murkl/time-machine/master/res/screenshot.png)

## Dependencies
### Arch
```
sudo pacman -S zenity rsync xdg-utils
```
### Debian/Ubuntu/elementaryOS
```
sudo apt install zenity rsync xdg-utils
```

## Run the script
```
./time-machine
```
