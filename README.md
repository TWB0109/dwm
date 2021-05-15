# dwm - dynamic window manager
dwm is an extremely fast, small, and dynamic window manager for X.

## Installation
- Edit the config.def.h file to match your liking
- Edit the `dwms`, `natscroll`, `autolock` and `dbar` scripts to match your liking 

## Running dwm

Add the following line to your .xinitrc to start dwm using startx:

    dwms


## Usage
Check for keybindings in `config.def.h`, if you want to add your own, I recommend using [sxhkd](https://github.com/baskerville/sxhkd)

- To restart (recompile) dwm in place after changing configuration use `MOD4+q`
- To quit dwm use `MOD4+Shift+q`

Where MOD4 = WINDOWS/SUPER Key

## Dependencies
Check the `dwms`, `natscroll`, `autolock` and `dbar` scripts for dependencies, modify it to add or remove dependencies.
