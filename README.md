Unity doesn't load, no Launcher, no Dash appears
======================================================

 - Try to open a terminal with `Ctrl+Alt+T`.
 - This may not work but you can try right clicking on the desktop and selecting **"Open terminal here."** Otherwise, you may need to change to a **"hard"** terminal by pressing `Ctrl+Alt+F1` and log in.
 - Install `compizconfig-settings-manager` by running
```
$ sudo apt-get install compizconfig-settings-manager
```
- Then run it with this:
```
$ DISPLAY=:0 ccsm
```
- The first part tells the terminal which display you want it to load on (otherwise it won't have a clue).
- If you switched to a `TTY` in `step 1`, switch back to the graphical server by pressing **`Ctrl+Alt+F7` (or `Ctrl+Alt+F8` sometimes).**
- There there should be a CompizConfig Settings Manager waiting for you.
- Find the `Unity plugin`. `Enable` it.
- Everything should spring into life but if it doesn't, you might have to `restart`. You can do that by going back to the terminal and running `sudo reboot`.
