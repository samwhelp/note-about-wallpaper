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
	sudo install -Dm755 ./opset-wallpaper-xfce /usr/local/bin/opset-wallpaper-xfce
	sudo install -Dm644 ./opset-wallpaper-xfce.desktop /usr/share/applications/opset-wallpaper-xfce.desktop
.PHONY: install

remove:
	sudo rm -f /usr/local/bin/opset-wallpaper-xfce
	sudo rm -f /usr/share/applications/opset-wallpaper-xfce.desktop
.PHONY: remove
