
# opset-wallpaper-gnome


## Reference

* https://specifications.freedesktop.org/icon-naming-spec/icon-naming-spec-latest.html
* https://github.com/samwhelp/play-ubuntu-18.04-plan/blob/master/prototype/de-basic/play-gnome/config-install.sh#L52

## Agent

* [gsettings](http://manpages.ubuntu.com/manpages/focal/man1/gsettings.1.html)


## Install

``` sh
make install
```

* [opset-wallpaper-gnome](opset-wallpaper-gnome)
* [opset-wallpaper-gnome.desktop](opset-wallpaper-gnome.desktop)

## Remove

``` sh
make remove
```

## Usage

### On File Manager

1. Launch FileManager. For example: `nautilus`
2. Specific Image File
3. Open With `opset-wallpaper-gnome` to set wallpaper

### On xfce4-terminal

1. Launch `xfce4-terminal`
2. Run `opset-wallpaper-gnome image_file`


## See Also

* [wallpaper-select-gnome](https://github.com/samwhelp/note-about-fzf/tree/gh-pages/_demo/project/wallpaper-select/wallpaper-select-gnome)
