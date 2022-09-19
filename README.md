# dmenu

An almost vanilla build of [dmenu](https://tools.suckless.org/dmenu/).

## Patches and features

* [**border-20201112-1a13d04**](https://tools.suckless.org/dmenu/patches/border/dmenu-border-20201112-1a13d04.diff) adds a border around the dmenu window of width `n` with the `-bw n` flag.
* [**grid-4.9**](https://tools.suckless.org/dmenu/patches/grid/dmenu-grid-4.9.diff) allows you to render dmenu's entries in a grid with the `-g` and `-l` flags.
    * [**gridnav-5.0**](https://tools.suckless.org/dmenu/patches/gridnav/dmenu-gridnav-5.0.diff) adds the ability to move left and right through a grid.

## Installation

```sh
git clone https://github.com/thatguynoe/dmenu
cd dmenu
sudo make install
```
