# doom-config
My Doom Emacs configuration for Rails development.

## Installation

### Install Emacs

Install the dependencies
``` shell
# Dependencies
brew install git ripgrep
brew install coreutils fd
xcode-select --install

```

Install [emacs-plus](https://github.com/d12frosted/homebrew-emacs-plus)
``` shell
brew tap d12frosted/emacs-plus
brew install emacs-plus
ln -s /usr/local/opt/emacs-plus/Emacs.app /Applications/Emacs.app
```


### Install Doom

``` shell
git clone https://github.com/danielventulieri/doom-config.git ~/.doom.d
git clone https://github.com/hlissner/doom-emacs ~/.emacs.d
~/.emacs.d/bin/doom install
```
