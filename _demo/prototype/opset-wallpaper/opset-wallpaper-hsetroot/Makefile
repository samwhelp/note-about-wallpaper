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
	sudo install -Dm755 ./opset-wallpaper-hsetroot /usr/local/bin/opset-wallpaper-hsetroot
	sudo install -Dm644 ./opset-wallpaper-hsetroot.desktop /usr/share/applications/opset-wallpaper-hsetroot.desktop
.PHONY: install

remove:
	sudo rm -f /usr/local/bin/opset-wallpaper-hsetroot
	sudo rm -f /usr/share/applications/opset-wallpaper-hsetroot.desktop
.PHONY: remove
