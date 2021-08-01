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
	sudo install -Dm755 ./opset-wallpaper-gnome /usr/local/bin/opset-wallpaper-gnome
	sudo install -Dm644 ./opset-wallpaper-gnome.desktop /usr/share/applications/opset-wallpaper-gnome.desktop
.PHONY: install

remove:
	sudo rm -f /usr/local/bin/opset-wallpaper-gnome
	sudo rm -f /usr/share/applications/opset-wallpaper-gnome.desktop
.PHONY: remove
