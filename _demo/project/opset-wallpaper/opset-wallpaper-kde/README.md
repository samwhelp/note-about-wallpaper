
# opset-wallpaper-kde


## Reference

* https://specifications.freedesktop.org/icon-naming-spec/icon-naming-spec-latest.html
* https://superuser.com/questions/488232/how-to-set-kde-desktop-wallpaper-from-command-line
* https://www.reddit.com/r/kde/comments/65pmhj/change_wallpaper_from_terminal/
* https://github.com/pashazz/ksetwallpaper
* https://github.com/markubiak/wallpaper-reddit
* https://github.com/keshavbhatt/BingWall
* https://github.com/marguerite/linux-bing-wallpaper


## Agent

* [qdbus](http://manpages.ubuntu.com/manpages/focal/man1/qdbus.1.html)
* [gdbus](http://manpages.ubuntu.com/manpages/focal/man1/gdbus.1.html)
* [dbus-send](http://manpages.ubuntu.com/manpages/focal/en/man1/dbus-send.1.html)


## Install

``` sh
make install
```

* [opset-wallpaper-kde](opset-wallpaper-kde)
* [opset-wallpaper-kde.desktop](opset-wallpaper-kde.desktop)

## Remove

``` sh
make remove
```

## Usage

### On File Manager

1. Launch FileManager. For example: `thunar`
2. Specific Image File
3. Open With `opset-wallpaper-kde` to set wallpaper

### On xfce-terminal

1. Launch `xfce-terminal`
2. Run `opset-wallpaper-kde image_file`


## See Also

* [wallpaper-select-kde](https://github.com/samwhelp/note-about-fzf/tree/gh-pages/_demo/project/wallpaper-select/wallpaper-select-kde)
