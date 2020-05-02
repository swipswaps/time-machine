# Time Machine
This simple backup tool uses zenity as frontend and [laurent22](https://github.com/laurent22/rsync-time-backup) rsync script as backend.

Enjoy the simplicity :)

![time-machine screenshot](https://raw.githubusercontent.com/murkl/time-machine/master/res/screenshot.png)


## Features
* Sanbox architecture
* Leightweight & less dependencies
* Robust error handling (backup can be canceled)
* Configuration of every script variable
* rsync-time-backup.sh aguments support
* Update feature (incl. notification)
* 100% GUI 

## Example Configuration
```
# readme: https://github.com/laurent22/rsync-time-backup#usage
rsync_arguments="-p 2222"
source_dir="$HOME"
destination_dir="user@example.com:/mnt/backup_drive"
gui_width=479
gui_height=279
desktop_icon=true
update_check=true
```

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
