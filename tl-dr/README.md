### System Prefernces
*Set Preference: [Link](../system_preferences/README.md)*

### Homebrew
This is **'Super Awwwwwwwwesome'** package manager.  
If you are use this tool, you can save your time.  
  
*Install: [Official Link](https://docs.brew.sh/Installation)*  
*Open [Formulae Search](https://formulae.brew.sh/): To search application or cli*  

---
### `mas`
To download application in Mac App Store
  
```sh
brew install mas
```
```sh
mas signup [your apple id]
 ```

---
### `fish`
```sh
brew install fish
echo "/usr/local/bin/fish" | sudo tee -a /etc/shells
chsh -s /usr/local/bin/fish
```

##### Font: Hack
```sh
brew tap homebrew/cask-fonts
brew install --cask font-hack-nerd-font
```

##### `fisher`
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
### Application
```sh
brew install --cask google-chrome
brew install --cask iterm2
brew install --cask dropbox
brew install --cask 1password
brew install --cask alfred
brew install --cask bettertouchtool
brew install --cask contexts
brew install --cask sublime-text
brew install --cask intellij-idea

# 904280696 - mas search things3
mas install 904280696
brew install —cask thingsmacsandboxhelper

brew install docker
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
# set alias for exa
alias --save l="exa -1la --icons --no-permissions -s modified"
# https://github.com/sharkdp/fd
brew install fd
# https://github.com/sharkdp/bat
brew install bat
# https://github.com/BurntSushi/ripgrep
brew install ripgrep
#
# ### develop ###
#
# https://gradle.org/install/
brew install gradle
# https://kotlinlang.org/
brew install kotlin
# https://adoptium.net/index.html
brew tap homebrew/cask-versions
brew install --cask temurin8
# 
# ### tools ###
#
# https://github.com/ytdl-org/youtube-dl
# usage: fish shell using "[URL]"
brew install youtube-dl
# https://imagemagick.org/script/convert.php
brew install imagemagick
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
2. https://poiemaweb.com/docker-mysql