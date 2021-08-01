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
	@echo '	$$ make remove'
	@echo

.PHONY: help


install: install-opset-wallpaper-feh install-opset-wallpaper-hsetroot install-opset-wallpaper-xwallpaper install-opset-wallpaper-xfce install-opset-wallpaper-gnome

.PHONY: install


remove: remove-opset-wallpaper-feh remove-opset-wallpaper-hsetroot remove-opset-wallpaper-xwallpaper remove-opset-wallpaper-xfce remove-opset-wallpaper-gnome

.PHONY: remove


install-opset-wallpaper-feh:
	make -C opset-wallpaper-feh install
.PHONY: install-opset-wallpaper-feh

remove-opset-wallpaper-feh:
	make -C opset-wallpaper-feh remove
.PHONY: remove-opset-wallpaper-feh


install-opset-wallpaper-hsetroot:
	make -C opset-wallpaper-hsetroot install
.PHONY: install-opset-wallpaper-hsetroot

remove-opset-wallpaper-hsetroot:
	make -C opset-wallpaper-hsetroot remove
.PHONY: remove-opset-wallpaper-hsetroot


install-opset-wallpaper-xwallpaper:
	make -C opset-wallpaper-xwallpaper install
.PHONY: install-opset-wallpaper-xwallpaper

remove-opset-wallpaper-xwallpaper:
	make -C opset-wallpaper-xwallpaper remove
.PHONY: remove-opset-wallpaper-xwallpaper


install-opset-wallpaper-xfce:
	make -C opset-wallpaper-xfce install
.PHONY: install-opset-wallpaper-xfce

remove-opset-wallpaper-xfce:
	make -C opset-wallpaper-xfce remove
.PHONY: remove-opset-wallpaper-xfce


install-opset-wallpaper-gnome:
	make -C opset-wallpaper-gnome install
.PHONY: install-opset-wallpaper-gnome

remove-opset-wallpaper-gnome:
	make -C opset-wallpaper-gnome remove
.PHONY: remove-opset-wallpaper-gnome
