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
	sudo install -Dm755 ./opset-wallpaper-lxqt /usr/local/bin/opset-wallpaper-lxqt
	sudo install -Dm644 ./opset-wallpaper-lxqt.desktop /usr/share/applications/opset-wallpaper-lxqt.desktop
.PHONY: install

remove:
	sudo rm -f /usr/local/bin/opset-wallpaper-lxqt
	sudo rm -f /usr/share/applications/opset-wallpaper-lxqt.desktop
.PHONY: remove
