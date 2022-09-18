### System Prefernces
*Set Preference: [Link](../system_preferences/README.md)*

## => 📍 On Terminal  
### Homebrew

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### Iterm2
```sh
brew install --cask iterm2
```

---
### fish
[fishshell](https://fishshell.com/)
[stackoverflow](https://stackoverflow.com/a/70203456/6766780)
```sh
brew install fish
echo "/usr/local/bin/fish" | sudo tee -a /etc/shells
chsh -s /usr/local/bin/fish
```
```sh
fish_add_path /opt/homebrew/bin
```

---
### mas
To download application in Mac App Store
  
```sh
brew install mas
```


##### Font: Hack
```sh
brew tap homebrew/cask-fonts
brew install --cask font-hack-nerd-font
```

##### fisher
```sh
curl -sL https://git.io/fisher | source && fisher install jorgebucaran/fisher
```

##### Theme: [starship](https://starship.rs/)
```sh
brew install starship
```
```sh
# ~/.config/fish/config.fish

starship init fish | source
```



---
## => 📍 On Iterm2

### Application
```sh
brew install --cask google-chrome
brew install --cask dropbox
brew install --cask 1password
brew install --cask alfred
brew install --cask bettertouchtool
brew install --cask contexts
brew install --cask sublime-text
brew install --cask intellij-idea

# 904280696 - mas search things3
mas install 904280696
brew install --cask thingsmacsandboxhelper

brew install --cask docker
brew install --cask paw
brew install --cask dozer
brew install --cask imazing
brew install --cask pdf-expert
brew install --cask transmission
brew install --cask iina
brew install --cask spotify
brew install --cask beardedspice
brew install --cask appcleaner

# 1091189122 - mas search bear
mas install 1091189122

# 1176895641 - mas search spark
mas install 1176895641

# 694633015 - mas search "VPN Unlimited"
mas install 694633015

# 553245401 - mas search "Friendly Streaming"
mas install 553245401

# 1190243926 - mas search EzyCal
mas install 1190243926

# 869223134 - mas search kakaotalk
mas install 869223134

# 937984704 - mas search "amphetamine"
mas install 937984704

brew install --cask pomotodo
brew install --cask raindropio
brew install --cask zoom
brew install --cask keka
brew install --cask slack
```

---
### CLI
```sh
###
# reference: https://github.com/ibraheemdev/modern-unix
#
# ### utility ###
#
# https://github.com/muesli/duf
brew install duf
# https://github.com/orf/gping
brew install gping
# https://github.com/ClementTsang/bottom
brew install bottom
# https://github.com/theryangeary/choose
brew install choose-rust
# https://github.com/ogham/exa
brew install exa
# https://github.com/sharkdp/fd
brew install fd
# https://github.com/sharkdp/bat
brew install bat
# https://github.com/BurntSushi/ripgrep
brew install ripgrep
# https://github.com/bootandy/dust
brew install dust
# http://mama.indstate.edu/users/ice/tree/
brew install tree
#
# ### develop ###
#
# https://gradle.org/install/
brew install gradle
# https://kotlinlang.org/
brew install kotlin
# https://adoptium.net/index.html
# brew tap homebrew/cask-versions
# brew install --cask temurin8
# https://github.com/jorgebucaran/nvm.fish
fisher install jorgebucaran/nvm.fish
# 
# ### tools ###
#
# https://github.com/ytdl-org/youtube-dl
# usage: fish shell using "[URL]"
brew install youtube-dl
# https://imagemagick.org/script/convert.php
brew install imagemagick

brew install --cask monitorcontrol
```

### alias
```sh
# set alias for exa
alias --save l="exa -1la --icons --no-permissions -s modified"
```

##### *[zoxide](https://github.com/ajeetdsouza/zoxide)*
```sh
brew install zoxide
```
```sh
# ~/.config/fish/config.fish
zoxide init fish | source
```

##### *mysql*
1. https://hub.docker.com/_/mysql
2. https://poiemaweb.com/--cask docker-mysql

##### *nvm*
```sh
fisher install jorgebucaran/nvm.fish

```
```sh
nvm install lst
nvm use [version]
```

```sh
ln -s (which node) /usr/local/bin/node
ln -s (which npm) /usr/local/bin/npm
```

##### *nvm global cli*
```sh
npm config get prefix
```
```sh
# ~/.config/fish/config.fish
set PATH [npm config get prefix]/bin $PATH
```

### Flutter
```sh
brew install --cask flutter
```