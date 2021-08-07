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
	sudo install -Dm755 ./opset-wallpaper-feh /usr/local/bin/opset-wallpaper-feh
	sudo install -Dm644 ./opset-wallpaper-feh.desktop /usr/share/applications/opset-wallpaper-feh.desktop
.PHONY: install

remove:
	sudo rm -f /usr/local/bin/opset-wallpaper-feh
	sudo rm -f /usr/share/applications/opset-wallpaper-feh.desktop
.PHONY: remove
