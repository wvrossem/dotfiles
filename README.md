# Brew

* Install Brew
* Install the following packages:
  * `ack`
  * `coreutils`
  * `docker`
  * `git`
  * `httpie`
  * `mongodb`
  * `mpv`
  * `nvm`
  * `python`
  * `python3`
  * `redis`
  * `tmux`
  * `tree`
  * `zsh`
  * `zsh-completions`
  
```
buku			gdbm			harfbuzz		libevent		mpfr			pixman			sqlite
cairo			gettext			hugo			libffi			mpv			pkg-config		tmux
ffmpeg			ghostscript		icu4c			libmpc			mujs			python			x264
fontconfig		glib			isl			libpng			nvm			python3			xvid
freetype		gmp			jpeg			libtiff			openssl			python@2		xz
fribidi			gobject-introspection	lame			little-cms2		pandoc			r			youtube-dl
gcc			graphite2		libass			lua@5.1			pcre			readline		zsh
```

# Apps / Cask

### Install via installer or brew Cask

DEV Tools:
  * Atom
    * Settings are synced via https://atom.io/packages/sync-settings
  * Iterm3 + set to load the profile in `/shell`
  * Robomongo
  * Medis
  * Sourcetree
  * Postman
  * Lepton
  * Dash
  * Cyberduck

General:
  * Chrome
  * Spotify
  * Vlc
  * Google Drive
  * Skype
  * Virtualbox
 
## Cask List

* freefilesync             
* iina                     
* keepassx                 
* macpass                  
* orange                   
* riot                     
* tagspaces                
* vienna
* handbrake                
* keepassxc                
* mactex                   
* pdftotext               
* rstudio                  
* thunderbird

### Via App store

  * Soriko Radio
  * Slack
  * Amphetamine
  * Pixelmator

  * Color picker
  * Write
  * WhatsApp

# MacOS

* Install the Fira font: https://mozilla.github.io/Fira/

# Git

Copy the git dotfiles files to the home directory

* .gitignore_global: global ignores for OSX, Node.js
* .gitconfig
  * Set the email
  * Check relevant aliases
* gitmessage.txt:  the template commit message as configured in .gitconfig

# Shell

* Install oh-my-zsh
* Install honukai zsh theme: https://github.com/oskarkrawczyk/honukai-iterm-zsh
* `.zshrc` to home directory
* Load iterm2 profile via preferences

# Node setup

Set node to a specific version

* `nvm install 6.9.5`
* `nvm use 6.9.5`
* `nvm alias default 6.9.5`

Set npm to a specific version

* `npm install -g npm@2.15.11`
* `rm /usr/local/bin/npm`
* `ln -s /usr/bin/npm@2.15.11 /usr/local/bin/npm`
