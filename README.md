# Time Machine
This simple backup tool uses zenity as frontend and [laurent22](https://github.com/laurent22/rsync-time-backup) rsync script as backend.

Enjoy the simplicity :)

![time-machine menu](https://raw.githubusercontent.com/murkl/time-machine/master/res/screenshot/menu.png)
![time-machine configuration](https://raw.githubusercontent.com/murkl/time-machine/master/res/screenshot/configuration.png)
![time-machine exclude](https://raw.githubusercontent.com/murkl/time-machine/master/res/screenshot/configuration.png)

## Dependencies
### Arch
```
sudo pacman -S rsync xdg-utils
```
### Debian/Ubuntu/elementaryOS
```
sudo apt install rsync xdg-utils
```

## Run the script
```
./time-machine
```
