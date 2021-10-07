### Index
🔐: 1password
☁️: dropbox

## Homebrew
*Install*
[Official Link](https://docs.brew.sh/Installation)

This is **'Super Awwwwwwwwesome'** package manager.  
If you are use this tool, you can save your time. 

### Additional Step
1. Open [formulae search](https://formulae.brew.sh/): To search application or cli

[Go to the Top](#index)

## mas
*Install*
```sh
brew install mas
```

To download application in Mac Appstore

### Additional Step
1. 
```sh
mas signup [your apple id]
 ```

[Go to the Top](#index)

## Chrome
*Install*
```sh
brew install --cask google-chrome
```
### Additional Step
1. `Font size`: 'Large'  
2. Set `Show warning before quitting with ⌘Q`: disabled  
3. Check extension

[Go to the Top](#index)

## Iterm
*Install*
```sh
brew install --cask iterm2
```

This is **Terminal app**, [iTerm2](https://iterm2.com/downloads.html).  
This is well-known terminal app. You can customize it and set status for mac.  

### Additional Step
1. Add the Theme(gruvbox dark hard 256): [contribution](https://github.com/martinlindhe/base16-iterm2/tree/master/itermcolors)

[Go to the Top](#index)


## fish
*Install*
```sh
brew install fish

```
```sh
echo "/usr/local/bin/fish" | sudo tee -a /etc/shells

```
```sh
chsh -s /usr/local/bin/fish

```

### Additional Step
1.
```sh
brew tap homebrew/cask-fonts
```

2.
```sh
brew install --cask font-hack-nerd-font

```

3. [Powerline Font](https://github.com/powerline/fonts): clone -> install -> remove
4. Install `fisher`
```sh
curl -sL https://git.io/fisher | source && fisher install jorgebucaran/fisher

```
5. Add the Theme: [spacefish](https://github.com/matchai/spacefish)
```sh
fisher install matchai/spacefish

```

## CLI
### [youtube-dl](https://github.com/ytdl-org/youtube-dl): fish shell using `"[URL]"`
```sh
brew install youtube-dl

```
### [rg](https://github.com/BurntSushi/ripgrep)
```sh
brew install ripgrep

```
### [bat](https://github.com/sharkdp/bat)
```sh
brew install bat

```
### [fd](https://github.com/sharkdp/fd)
```sh
brew install fd

```
### kotlin
```sh
brew install kotlin

```
### [gradle](https://gradle.org/install/)
```sh
brew install gradle

```
### [jdk](https://adoptium.net/index.html)
```sh
brew tap homebrew/cask-versions

```
```sh
brew install --cask temurin8

```
### [exa](https://github.com/ogham/exa)
```sh
brew install exa

```
### [choose](https://github.com/theryangeary/choose)
```sh
brew install choose-rust

```
### [bottom](https://github.com/ClementTsang/bottom)
```sh
brew install bottom

```
### [gping](https://github.com/orf/gping)
```sh
brew install gping

```
### [zoxide](https://github.com/ajeetdsouza/zoxide)
### [duf](https://github.com/muesli/duf)
```sh
brew install duf

```
### [imagemagick](https://imagemagick.org/script/convert.php)
```sh
brew install imagemagick

```

### Additional Step
1.
```sh
alias --save l="exa -1la --icons --no-permissions -s modified"

```

### Extra Information
+ [Modern Unix](https://github.com/ibraheemdev/modern-unix)

## Dropbox
*Install*
```sh
brew install --cask dropbox

```

## 1Password
*Install*
```sh
brew install --cask 1password

```

If you stil rememeber you **password**, **license**, and **some secret thing**   
or write them to note app/a piece of papepr,  
You can write them into [1Password](https://1password.com/) and get them when/what you want.

This app also supports IOS, web, and Andorid.

[Go to the Top](#index)

## Alfred
*Install*
```sh
brew install --cask alfred

```
### Additional Step
1. Enable License: 🔐
2. Sync Preferences: ☁️

[Alfred](https://www.alfredapp.com/) is **awesome launcher app**.  
It has more feature than Spotlight.  
* can search anything in my mac.
* can search something in web without fousing web browser.
* can store/get in clipboard, text, image, and file.
* can convert text using snippet.
* can explore your mac more and more using Workflow.

### Custom Terminal
[Iterm](https://github.com/vitorgalvao/custom-alfred-iterm-scripts)

### Theme
I revised color and font for [appearence](./Gruvbox-Dark.alfredappearance) based on **gruvbox**.  
!! You must should install **'Hack Nerd Mono'** if you use this appearence.  
![appearence](./alfred_appearence.gif)

### Workflows
Alfred say ...
> With Alfred's Powerpack and workflows, ... and boost your productivity.

However, there are so many workflows and some of them will be not updated.  
Workflows is good to me but sometimes it is hard to find nice workflows.  

I searched in goolge and github, and I make a note to keep workflows.  
If you want to see [more](https://github.com/spearkkk/alfred-workflow)...

[Go to the Top](#index)

## Better Touch Tool
*Install*
```sh
brew install --cask bettertouchtool

```
All inputs through mac can customized as you want if you have **Better Touch Tool**.  

I have a another keyboard, but sometimes I have to use keyboard of this mac.  
When I push <kbd>fn</kbd>, I can press function key. But it is awkward to press function key in IDEA.  
So I just mapped number key to function using [Better Touch Tool](https://folivora.ai/).

[Go to the Top](#index)

## Contexts
*Install*
```sh
brew install --cask contexts

```

Contexts manages all windows and application in my mac.  
When you want to switch between application, you press <kbd>command</kbd> + <kbd>tab</kbd>.  
Or when you want to switch windows between in a application, you press <kbd>command</kbd> + <kbd>\`</kbd>.  
But if you have more windows as a full screen, the switching is not working as you want. 

[Contexts](https://contexts.co/) enable to **switch windows as I want**.  
Just try to use this app.

[Go to the Top](#index)

## Things3
*Install*
```sh
mas search things3

```
```sh
mas install [id]

```

Have you heard *GTD*? 
> 'Getting Things Done' is a time management method, ...  
>  from wikipedia

When you are focusing on something, there are times when an idea suddenly comes to mind.  
You do not have to worry about missing that idea anymore.

1. Just put in idea, [Things](https://culturedcode.com/things/).
2. Get it from Things when you want.
3. Do it.


## Sublime Text
*Install*
```sh
brew install --cask sublime-text

```
### Additional Step
1. Install 'Package Controll'
2. Install Package 'A File Icon'
3. Install Package 'gruvbox'
4. <details><summary>Default Setting...</summary>

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

5. <details><summary>Gruvbox Setting...</summary> 

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

[Sublime Text](https://www.sublimetext.com/) is **Text Editor**, it is simple and fast.  
I use two editor to write something.  



## IDEA
### Setting
* Editor Tabs: Tab placements: 'None', Tab limit: '1'
### Plugins
* Gruvbox Theme: dark hard
* Rainbow Brackets
* String Manipulation

[Go to the Top](#index)

## Application
* Docker
* Paw
* Dozer
* Amphetamine
* Bear
* Spark
* Imazing
* PDF Expert
* VPN Unlimited
* Transmission
* Friendly Streaming
* IINA
* Spotify
* Boom 3D
* BeardedSpice
* EzyCal
* KakaoTalk
* AppCleaner

[Go to the Top](#index)

## System Preferences
**General**  
Set `Recent Items`: 'None'  

**Dock & Menu Bar**  
Set `Size`: small  
Set `Automactically hide and show the Dock`: enabled  
Set `Blooth`: 'Show in Menu Bar'  
Set `Battery`: 'Show in Menu Bar' & 'Show Percentage'  

**Mission Control**   
All enabled  

**Spotlight**  
All disabled  

**Keyboard**
- https://jojoldu.tistory.com/420

## Terminal Tweaks

<details>
  <summary>Quick Look: Animation</summary>

**Apply**  
```shell
defaults write -g QLPanelAnimationDuration -float 0; killall Finder
```
**Reset**
```shell
defaults delete -g QLPanelAnimationDuration; killall Finder
```
</details>

<details>
  <summary>Dock: Delay</summary>

**Apply**
```shell
defaults write com.apple.Dock autohide-delay -float 0; killall Dock
```
**Reset**
```shell
defaults delete com.apple.dock autohide-delay; killall Dock
```
</details>

<details>
  <summary>Dock: Animation</summary>

**Apply**
```shell
defaults write com.apple.dock autohide-time-modifier -float 0; killall Dock
```
**Reset**
```shell
defaults delete com.apple.dock autohide-time-modifier; killall Dock
```
</details>

<details>
  <summary>Launch Pad: Animation</summary>

**Apply**
```shell
defaults write com.apple.dock springboard-show-duration -int 0; killall Dock
```
```shell
defaults write com.apple.dock springboard-hide-duration -int 0; killall Dock
```
**Reset**
```shell
defaults delete com.apple.dock springboard-show-duration; killall Dock
```
```shell
defaults delete com.apple.dock springboard-hide-duration; killall Dock
```
</details>

<details>
  <summary>Pop-up&Dialog: Animation</summary>

**Apply**
```shell
defaults write -g NSWindowResizeTime -float 0.01
```
```shell
defaults write -g NSAutomaticWindowAnimationsEnabled -bool FALSE
```
**Reset**
```shell
defaults delete -g NSWindowResizeTime
```
```shell
defaults delete -g NSAutomaticWindowAnimationsEnabled
```
</details>

<details>
  <summary>Screenshot</summary>

**File Format**  
Default: .png
```shell
defaults write com.apple.screencapture type PDF; killall SystemUIServer
```
**File Path**  
Default: ~/Desktop
```shell
defaults write com.apple.screencapture location /drag/location/here; killall SystemUIServer
``` 
</details>

[Go to the Top](#index)

## mysql
1. https://hub.docker.com/_/mysql
2. https://poiemaweb.com/docker-mysql

[Go to the Top](#index)