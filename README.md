yariza Sublime Text 3 Settings
==============================

My Sublime Settings.

Install on OS X by typing:

	cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/
	git clone git@github.com:yariza/sublime-settings.git User/

Or alternatively, if you don't want to operate from the Library directory,
you can use symlinks:

	cd /path/to/dir
	git clone git@github.com:yariza/sublime-settings.git
	cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/
	rm -r User
	ln -s /path/to/dir/sublime-settings User

Note that this will remove your existing Sublime Text 3 Settings.
