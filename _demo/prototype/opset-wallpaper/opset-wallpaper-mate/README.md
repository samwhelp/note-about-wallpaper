
# opset-wallpaper-mate


## Reference

* https://specifications.freedesktop.org/icon-naming-spec/icon-naming-spec-latest.html


## Agent

* [gsettings](http://manpages.ubuntu.com/manpages/focal/man1/gsettings.1.html)


## Install

``` sh
make install
```

* [opset-wallpaper-mate](opset-wallpaper-mate)
* [opset-wallpaper-mate.desktop](opset-wallpaper-mate.desktop)

## Remove

``` sh
make remove
```

## Usage

### On File Manager

1. Launch FileManager. For example: `thunar`
2. Specific Image File
3. Open With `opset-wallpaper-mate` to set wallpaper

### On xfce4-terminal

1. Launch `xfce4-terminal`
2. Run `opset-wallpaper-mate image_file`


## See Also

* [wallpaper-select-mate](https://github.com/samwhelp/note-about-fzf/tree/gh-pages/_demo/project/wallpaper-select/wallpaper-select-mate)


## Explore

run

``` sh
gsettings list-recursively | grep mate | grep picture
```

show

```
org.mate.background picture-options 'zoom'
org.mate.background picture-opacity 100
org.mate.background picture-filename '/usr/share/backgrounds/ubuntu-mate-common/Green-Wall-Logo.png'
org.mate.screensaver picture-filename '/usr/share/backgrounds/mate/desktop/Stripes.png'
org.mate.Atril pictures-directory @ms nothing
```

run

``` sh
gsettings list-recursively | grep gtk | grep theme
```

show

```
org.mate.interface gtk-theme 'Yaru-MATE-light'
org.mate.interface gtk-key-theme 'Default'
org.gnome.desktop.interface gtk-theme 'Yaru-MATE-light'
org.gnome.desktop.interface gtk-key-theme 'Default'
```
