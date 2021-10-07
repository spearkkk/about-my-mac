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

##### Powerline Font  
*Install: [Official Link](https://github.com/powerline/fonts): clone -> install -> remove*  

##### `fisher`
```sh
curl -sL https://git.io/fisher | source && fisher install jorgebucaran/fisher
```

##### spacefish
```sh
# theme: https://github.com/matchai/spacefish
# 
fisher install matchai/spacefish
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

- *[zoxide](https://github.com/ajeetdsouza/zoxide)*
- *mysql*
  1. https://hub.docker.com/_/mysql
  2. https://poiemaweb.com/docker-mysql

---
### Chrome
- *`Font size`: 'Large'*
- *Set `Show warning before quitting with ⌘Q`: disabled*
- *Check extension*

---
### Iterm
This is **Terminal app**, [iTerm2](https://iterm2.com/downloads.html).  
This is well-known terminal app. You can customize it and set status for mac.  

*Add the Theme(gruvbox dark hard 256): [contribution](https://github.com/martinlindhe/base16-iterm2/tree/master/itermcolors)*

---
### 1Password

If you stil rememeber you **password**, **license**, and **some secret thing**   
or write them to note app/a piece of papepr,  
You can write them into [1Password](https://1password.com/) and get them when/what you want.

This app also supports IOS, web, and Andorid.

---
### Alfred
[Alfred](https://www.alfredapp.com/) is **awesome launcher app**.  
It has more feature than Spotlight.  
* can search anything in my mac.
* can search something in web without fousing web browser.
* can store/get in clipboard, text, image, and file.
* can convert text using snippet.
* can explore your mac more and more using Workflow.
<details>
  <summary>Additional Infomation</summary>

##### Custom Terminal
- [Iterm](https://github.com/vitorgalvao/custom-alfred-iterm-scripts)

##### Theme
I revised color and font for [appearence](./Gruvbox-Dark.alfredappearance) based on **gruvbox**.  
!! You must should install **'Hack Nerd Mono'** if you use this appearence.  
![appearence](./alfred_appearence.gif)

##### Workflows
Alfred say ...
> With Alfred's Powerpack and workflows, ... and boost your productivity.

However, there are so many workflows and some of them will be not updated.  
Workflows is good to me but sometimes it is hard to find nice workflows.  

I searched in goolge and github, and I make a note to keep workflows.  
If you want to see [more](https://github.com/spearkkk/alfred-workflow)...

</details>

- *Enable License: 🔐* 
- *Sync Preferences: ☁️*

---
### Better Touch Tool
All inputs through mac can customized as you want if you have **Better Touch Tool**.  

I have a another keyboard, but sometimes I have to use keyboard of this mac.  
When I push <kbd>fn</kbd>, I can press function key. But it is awkward to press function key in IDEA.  
So I just mapped number key to function using [Better Touch Tool](https://folivora.ai/).

---
### Contexts
Contexts manages all windows and application in my mac.  
When you want to switch between application, you press <kbd>command</kbd> + <kbd>tab</kbd>.  
Or when you want to switch windows between in a application, you press <kbd>command</kbd> + <kbd>\`</kbd>.  
But if you have more windows as a full screen, the switching is not working as you want. 

[Contexts](https://contexts.co/) enable to **switch windows as I want**.  
Just try to use this app.

- *Set Preference: [Link](./preference/context)*

---
### Things3
mas search things3
mas install [id]

Have you heard *GTD*? 
> 'Getting Things Done' is a time management method, ...  
>  from wikipedia

When you are focusing on something, there are times when an idea suddenly comes to mind.  
You do not have to worry about missing that idea anymore.

1. Just put in idea, [Things](https://culturedcode.com/things/).
2. Get it from Things when you want.
3. Do it.

---
### Sublime Text
[Sublime Text](https://www.sublimetext.com/) is **Text Editor**, it is simple and fast.  
I use two editor to write something.  
  
- *Install 'Package Controll'*
- *Install Package 'A File Icon'*
- *Install Package 'gruvbox'*
- *Install Packge 'MarkdownPreview'*
- *Set Preference*  
<details>
  <summary>Default Setting...</summary>
  
```json
{
    /// default setting
    "font_face": "Hack Nerd Font Mono",
    "font_size": 15,
    "translate_tabs_to_spaces": true,
    "margin": 2,
    "mini_diff": "auto",
    "trim_automatic_white_space": false,
}
```
</details>

<details>
  <summary>Gruvbox Setting...</summary> 

```json
{
    /// gruvbox theme seting
    "theme": "gruvbox.sublime-theme",
    "color_scheme": "Packages/gruvbox/gruvbox (Dark) (Soft).sublime-color-scheme",
    "gruvbox_accent_blue": true,
    "gruvbox_autocomplete_cramped": true,
    "gruvbox_sideline_autocomplete_row_thickest": true,
    "gruvbox_sidebar_compact": true,
    "gruvbox_sidebar_indent_s": true,
    "gruvbox_sidebar_font_size_14": true,
    "gruvbox_sidebar_heading_bold": true,
    "gruvbox_sidebar_label_bold": true,
    "gruvbox_command_palette_compact": true,
    "gruvbox_statusbar_xl": true,
    "gruvbox_statusbar_button_xs": true,
    "gruvbox_statusbar_font_size_15": true,
    "gruvbox_tabs_xxs": true,
    "gruvbox_tabs_font_size_15": true,
    "gruvbox_underline_active_tab_thicker": true,
    "gruvbox_panel_xxs": true,
    "gruvbox_scrollbar_width_xl": true,
    "gruvbox_buttons_font_size_16": true,
    "gruvbox_disable_borders": true,
    "gruvbox_folder_icons_large": true,
    "gruvbox_iconset_thick": true,
    "gruvbox_disable_panels_button": true,
    "gruvbox_highlight_active_buttons": true,
    "gruvbox_highlight_active_tree_row": true,
    "gruvbox_less_contrast": true, 
    "gruvbox_tabs_autowidth": true,  
    "gruvbox_tabs_bold": true,
}
```
</details>

---
### IDEA
##### Setting
* Editor Tabs: Tab placements: 'None', Tab limit: '1'
##### Plugins
* Gruvbox Theme: dark hard
* Rainbow Brackets
* String Manipulation

---

### Terminal Tweaks

<details>
  <summary>Quick Look: Animation</summary>

*Apply*  
```sh
defaults write -g QLPanelAnimationDuration -float 0; killall Finder
```
*Reset*  
```sh
defaults delete -g QLPanelAnimationDuration; killall Finder
```
</details>

<details>
  <summary>Dock: Delay</summary>

*Apply*  
```sh
defaults write com.apple.Dock autohide-delay -float 0; killall Dock
```
*Reset*  
```sh
defaults delete com.apple.dock autohide-delay; killall Dock
```
</details>

<details>
  <summary>Dock: Animation</summary>

*Apply*  
```sh
defaults write com.apple.dock autohide-time-modifier -float 0; killall Dock
```
*Reset*  
```sh
defaults delete com.apple.dock autohide-time-modifier; killall Dock
```
</details>

<details>
  <summary>Launch Pad: Animation</summary>

*Apply*  
```sh
defaults write com.apple.dock springboard-show-duration -int 0; killall Dock
```
```sh
defaults write com.apple.dock springboard-hide-duration -int 0; killall Dock
```
*Reset*  
```sh
defaults delete com.apple.dock springboard-show-duration; killall Dock
```
```sh
defaults delete com.apple.dock springboard-hide-duration; killall Dock
```
</details>

<details>
  <summary>Pop-up&Dialog: Animation</summary>

*Apply*  
```sh
defaults write -g NSWindowResizeTime -float 0.01
```
```sh
defaults write -g NSAutomaticWindowAnimationsEnabled -bool FALSE
```
*Reset*  
```sh
defaults delete -g NSWindowResizeTime
```
```sh
defaults delete -g NSAutomaticWindowAnimationsEnabled
```
</details>

<details>
  <summary>Screenshot</summary>

*File Format*  
Default: .png

```sh
defaults write com.apple.screencapture type PDF; killall SystemUIServer
```

*File Path*  
Default: \~/Desktop

```sh
defaults write com.apple.screencapture location /drag/location/here; killall SystemUIServer
``` 

</details>