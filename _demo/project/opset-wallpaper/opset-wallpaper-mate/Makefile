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
	sudo install -Dm755 ./opset-wallpaper-mate /usr/local/bin/opset-wallpaper-mate
	sudo install -Dm644 ./opset-wallpaper-mate.desktop /usr/share/applications/opset-wallpaper-mate.desktop
.PHONY: install

remove:
	sudo rm -f /usr/local/bin/opset-wallpaper-mate
	sudo rm -f /usr/share/applications/opset-wallpaper-mate.desktop
.PHONY: remove
