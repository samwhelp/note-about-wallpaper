
# opset-wallpaper-xfce


## Reference

* https://specifications.freedesktop.org/icon-naming-spec/icon-naming-spec-latest.html
* https://github.com/archcraft-os/archcraft-xfce-pkgs/blob/main/xfce-styles/src/styles/Forest.sh
* https://stackoverflow.com/questions/34268791/how-to-change-the-desktop-wallpaper-on-linux-from-within-a-shell-bash-script
* https://github.com/yatsenko-ihor/himawari8-wallaper/blob/master/himawari8_wallaper.sh

## Agent

* [xfconf-query](https://xfce.finalrewind.org/) ([GitHub](https://github.com/derf/xfce))


## Install

``` sh
make install
```

* [opset-wallpaper-xfce](opset-wallpaper-xfce)
* [opset-wallpaper-xfce.desktop](opset-wallpaper-xfce.desktop)

## Remove

``` sh
make remove
```

## Usage

### On File Manager

1. Launch FileManager. For example: `thunar`
2. Specific Image File
3. Open With `opset-wallpaper-hsetroot` to set wallpaper

### On xfce4-terminal

1. Launch `xfce4-terminal`
2. Run `opset-wallpaper-hsetroot image_file`


## See Also

* [wallpaper-select-xfce](https://github.com/samwhelp/note-about-fzf/tree/gh-pages/_demo/project/wallpaper-select/wallpaper-select-xfce)
