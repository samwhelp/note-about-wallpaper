default: help
.PHONY: default

help:
	@echo 'Usage:'
	@echo '	$$ make [action]'
	@echo
	@echo 'Example:'
	@echo '	$$ make'
	@echo '	$$ make help'
	@echo
	@echo '	$$ make install'
	@echo
.PHONY: help


install:
	sudo install -Dm755 ./opset-wallpaper-xwallpaper /usr/local/bin/opset-wallpaper-xwallpaper
	sudo install -Dm644 ./opset-wallpaper-xwallpaper.desktop /usr/share/applications/opset-wallpaper-xwallpaper.desktop
.PHONY: install

remove:
	sudo rm -f /usr/local/bin/opset-wallpaper-xwallpaper
	sudo rm -f /usr/share/applications/opset-wallpaper-xwallpaper.desktop
.PHONY: remove
