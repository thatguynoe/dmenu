# dmenu

An almost vanilla build of [dmenu](https://tools.suckless.org/dmenu/).

## Patches and features

* [**border-20201112-1a13d04**](https://tools.suckless.org/dmenu/patches/border/dmenu-border-20201112-1a13d04.diff) adds a border around the dmenu window of width `n` with the `-bw n` flag.
* [**grid-4.9**](https://tools.suckless.org/dmenu/patches/grid/dmenu-grid-4.9.diff) allows you to render dmenu's entries in a grid with the `-g` and `-l` flags.
    * [**gridnav-5.0**](https://tools.suckless.org/dmenu/patches/gridnav/dmenu-gridnav-5.0.diff) adds the ability to move left and right through a grid.
* [**password-5.0**](https://tools.suckless.org/dmenu/patches/password/dmenu-password-5.0.diff) hides input with the `-P` flag.
* [**dmenu-center-20240616-36c3d68.diff**](https://tools.suckless.org/dmenu/patches/center/dmenu-center-20240616-36c3d68.diff) centers the dmenu prompt with the `-c` flag.

## Installation

```sh
git clone https://github.com/thatguynoe/dmenu
cd dmenu
sudo make install
```

### Updates

The suckless dmenu development branch is the `master` branch in this repo. Consequently, this makes updating dmenu quite easy:

```sh
git clone https://github.com/thatguynoe/dmenu
cd dmenu

git switch master
git pull upstream master
git switch main
git merge master
```
