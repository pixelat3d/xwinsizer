
# xwinsizer
Easily Tame X Windows

Needed something to replace Borderless Gaming, but for Linux, so why not write a quick bash script? 
Please note that this will not work at all on Wayland as that is an entirely separate paradigm.

Example usage:
```
# Set size and center a 2560x1440 window on a 3440x1440 ultrawide
./xwinsizer 0x0580000d --borderless -w 2560 -h 1440 -x 440 -y 0
```

If you launch without a window id, you will be prompted with interactive menus.
