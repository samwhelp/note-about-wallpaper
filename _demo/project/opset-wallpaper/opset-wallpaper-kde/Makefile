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
	sudo install -Dm755 ./opset-wallpaper-kde /usr/local/bin/opset-wallpaper-kde
	sudo install -Dm644 ./opset-wallpaper-kde.desktop /usr/share/applications/opset-wallpaper-kde.desktop
.PHONY: install

remove:
	sudo rm -f /usr/local/bin/opset-wallpaper-kde
	sudo rm -f /usr/share/applications/opset-wallpaper-kde.desktop
.PHONY: remove
