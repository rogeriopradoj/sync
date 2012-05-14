# sync

Syncing Git, Terminal and Sublime Text's config with Dropbox.

---

## Using

On Mac, open your terminal and get started.

	cd ~/Dropbox
	git clone git@github.com:zenorocha/sync

## Dotfiles

	cd ~/
	ln -s ~/Dropbox/sync/dotfiles/.bash_profile .bash_profile
	ln -s ~/Dropbox/sync/dotfiles/.gitconfig .gitconfig
	
## Sublime Text 2

	cd ~/Library/Application\ Support/Sublime\ Text\ 2/
	
	ln -s ~/Dropbox/sync/sublime/Packages/ ./Packages
	ln -s ~/Dropbox/sync/sublime/Pristine\ Packages/ ./Pristine\ Packages/
	ln -s ~/Dropbox/sync/sublime/Installed\ Packages/ ./Installed\ Packages