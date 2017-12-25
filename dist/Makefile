PREFIX = /usr/bin

install:
			install gamepacker $(PREFIX)
			install mounter	$(PREFIX)
			install run-games $(PREFIX)
			install mntsudo /etc/sudoers.d
			groupadd rungames
uninstall:
			rm -f $(PREFIX)/gamepacker
			rm -f $(PREFIX)/mounter
			rm -f $(PREFIX)/run-games
			rm -f $(PREFIX)/mntsudo
			groupdel rungames