# nasa-pod
Arch Linux AUR package providing Systemd service and timer for downloading and setting Nasa's picture of the day as wallpaper.

## Set the wallpaper on startup
Run this command with the user you want to set the wallpaper to.
``` bash
$ systemctl --user enable nasa-pod.service
```

## Set the wallpaper every hour
Run this command with the user you want to set the wallpaper to.
``` bash
$ systemctl --user enable nasa-pod.timer
```
