### Index
🔐: 1password
☁️: dropbox

1. Install [Chrome](#chrome)
2. Install [Homebrew](#homebrew) in Terminal
3. Install [Iterm](#iterm) in Terminal
4. Install [`fish` and `fisher`](#fish) in Iterm2
5. Install [`pyenv`](https://github.com/pyenv/pyenv)
6. Install [`virtualenv`](https://github.com/pyenv/pyenv-virtualenv) for `pyenv`
7. Install [`nvm`](https://github.com/jorgebucaran/nvm.fish)
8. Install [CLI](#cli)
9. Install [Dropbox](https://www.dropbox.com/)
10. Install [1Password](#1password)
11. Install [Alfred](#alfred): 🔐,☁️
12. Install [Better Touch Tool](#better-touch-tool): ☁️
13. Install [Contexts](#contexts): ☁️
14. Install [Things3](#things3)
15. Install [Sublime Text](#sublime-text): 🔐
16. Insatll [Application](#application)
17. Install [`mysql`](#mysql)

## Chrome
* Change `Sync and Google services`  
* Set `Font size`: 'Large'  
* Set `Show warning before quitting with ⌘Q`: disabled  
* Check extension

[Go to the Top](#index)

## Homebrew
This is **'Super Awwwwwwwwesome'** package manager, [Homebrew](https://docs.brew.sh/Installation).  
If you are use this tool, you can save your time.  

* Install ['mas'](https://github.com/mas-cli/mas): `brew install mas` - To download application in Mac Appstore
* Open [formulae search](https://formulae.brew.sh/): To search application or cli

[Go to the Top](#index)

## Iterm
This is **Terminal app**, [iTerm2](https://iterm2.com/downloads.html).  
This is well-known terminal app. You can customize it and set status for mac.  
And the **Theme**, 
I set color scheme as **gruvbox**. I referred this [contribution](https://github.com/martinlindhe/base16-iterm2/tree/master/itermcolors).  

* `brew install iterm2`
* Set theme - gruvbox dark hard


[Go to the Top](#index)


## `fish`
* `brew install fish`  
* `echo "/usr/local/bin/fish" | sudo tee -a /etc/shells`  
* `chsh -s /usr/local/bin/fish`  

### `fisher`
* `brew install fisher`

### Font
* [Hack](https://github.com/ryanoasis/nerd-fonts#option-4-homebrew-fonts): Hack Nerd Mono
* [Powerline Font](https://github.com/powerline/fonts): clone -> install -> remove
* Set font for Iterm2

### Theme
[spacefish](https://github.com/matchai/spacefish): `fisher install matchai/spacefish`


[Go to the Top](#index)

## CLI
- [youtube-dl](https://github.com/ytdl-org/youtube-dl): fish shell using `"[URL]"`
- [rg](https://github.com/BurntSushi/ripgrep): `brew install ripgrep`
- [bat](https://github.com/sharkdp/bat): `brew install bat`
- [fd](https://github.com/sharkdp/fd): `brew install fd`
- kotlin: `brew install kotlin`
- [gradle](https://gradle.org/install/): `brew install gradle`
- [jdk](https://adoptium.net/index.html): `brew tap homebrew/cask-versions; brew install --cask temurin8`
- [exa](https://github.com/ogham/exa): `brew install exa`
- [choose](https://github.com/theryangeary/choose): `brew install choose-rust`
- [bottom](https://github.com/ClementTsang/bottom): `brew install bottom`
- [gping](https://github.com/orf/gping): `brew install gping`
- [zoxide](https://github.com/ajeetdsouza/zoxide)

- [imagemagick](https://imagemagick.org/script/convert.php): `brew install imagemagick`

### Alias
* `alias --save l="exa -1la --icons --no-permissions -s modified"`

### Extra Information
+ [Modern Unix](https://github.com/ibraheemdev/modern-unix)


[Go to the Top](#index)

## 1Password
If you stil rememeber you **password**, **license**, and **some secret thing**   
or write them to note app/a piece of papepr,  
You can write them into [1Password](https://1password.com/) and get them when/what you want.

This app also supports IOS, web, and Andorid.

[Go to the Top](#index)

## Alfred
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
All inputs through mac can customized as you want if you have **Better Touch Tool**.  

I have a another keyboard, but sometimes I have to use keyboard of this mac.  
When I push <kbd>fn</kbd>, I can press function key. But it is awkward to press function key in IDEA.  
So I just mapped number key to function using [Better Touch Tool](https://folivora.ai/).

[Go to the Top](#index)

## Contexts
Contexts manages all windows and application in my mac.  
When you want to switch between application, you press <kbd>command</kbd> + <kbd>tab</kbd>.  
Or when you want to switch windows between in a application, you press <kbd>command</kbd> + <kbd>\`</kbd>.  
But if you have more windows as a full screen, the switching is not working as you want. 

[Contexts](https://contexts.co/) enable to **switch windows as I want**.  
Just try to use this app.

[Go to the Top](#index)


## Things3
Have you heard *GTD*? 
> 'Getting Things Done' is a time management method, ...  
>  from wikipedia

When you are focusing on something, there are times when an idea suddenly comes to mind.  
You do not have to worry about missing that idea anymore.

1. Just put in idea, [Things](https://culturedcode.com/things/).
2. Get it from Things when you want.
3. Do it.

[Go to the Top](#index)

## Sublime Text
[Sublime Text](https://www.sublimetext.com/) is **Text Editor**, it is simple and fast.  
I use two editor to write something.  

1. Install 'Package Controll'
2. Install Package 'A File Icon'
3. Install Package 'gruvbox'

### Setting
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

[Go to the Top](#index)

## Application
* Docker
* IDEA
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