# dolphin-emu-git
Unofficial Arch Linux repository building the latest Dolphin Emulator every now and then.

Add this at the end of your `/etc/pacman.conf`:  
```ini
[dolphin-emu-git]
Server = https://swyter.github.io/$repo/
SigLevel = Optional
```

Refresh your local database with `pacman -Sy` and install packages like this: `pacman -S dolphin-emu-git`.
