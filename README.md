## D7F - My DWM Configuration

dwm is a dynamic window manager for X. It manages windows in tiled, monocle and floating layouts. All of the layouts can be applied dynamically, optimising the environment for the application in use and the task performed.

You can see more at the suckless website [here](https://dwm.suckless.org/)

## Patches

- [gaps]()
- [startup]()

## Defaults

terminal: kitty

launcher: dmenu


## Build
`sudo make clean install`
**Dependencies**
	- X11
	- Xft
	- Xinerama
	- Etc.
in order to install these dependencies search for the headers in your given distrobution.
