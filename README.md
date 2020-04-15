### Index
- [About My Mac](#about-my-mac)
  * [Homebrew](#homebrew)
  * [Font & Color Scheme](#font--color-scheme)
- [Application](#application)
  * [Alfred](#alfred)
  * [Better Touch Tool](#better-touch-tool)
  * [Contexts](#contexts)
  * [Chrome](#chrome)
  * [1Passowrd](#1passowrd)
  * [Things 3](#things-3)
  * [Spark](#spark)
  * [Amphetamine](#amphetamine)
  * [Dozer](#dozer)
  * [App Cleaner](#app-cleaner)
  * [Spotify & Boom 3D & BeardedSpice](#spotify--boom-3d--beardedspice)
  * [iMazing](#imazing)
  * [iTerm2](#iterm2)
  * [Sublime Text 3](#sublime-text-3)
  * [IDEA](#idea)
  * [Paw](#paw)
- [System Preferences](#system-preferences)
- [Terminal Tweaks](#terminal-tweaks)

# About My Mac
## Homebrew

This is **'Super Awwwwwwwwesome'** package manager.  
If you are use this tool, you can save your time.  
[Installation](https://docs.brew.sh/Installation)

## Font & Color Scheme

**Font**  
There are many fonts in this world, but I prefer 'Hack Nerd' font: [Installation](https://github.com/ryanoasis/nerd-fonts)

**Color Scheme**  
I prefer `gruvbox` color scheme. You can see color scheme [here](https://github.com/morhetz/gruvbox) 
and use [contribution](https://github.com/morhetz/gruvbox-contrib).

[Go to Top](#index)

---
# Application

> **Productivity**  
## Alfred
This is **Default Launcher**([Link](./application/alfred/README.md)), it has more feature than Spotlight.  
* can search anything in my mac.
* can search something in web without fousing web browser.
* can store/get in clipboard, text, image, and file.
* can convert text using snippet.
* can explore your mac more and more using Workflow.

## Better Touch Tool

All inputs through mac can customized as you want if you have **Better Touch Tool**.  

I have a another keyboard, but sometimes I have to use keyboard of this mac.  
When I push <kbd>fn</kbd>, I can press function key. But it is awkward to press function key in IDEA.  
So I just mapped number key to function using [this app](./application/better_touch_tool/README.md).

## Contexts

Contexts manages all windows and application in my mac.  
When you want to switch between application, you press <kbd>command</kbd> + <kbd>tab</kbd>.  
Or when you want to switch windows between in a application, you press <kbd>command</kbd> + <kbd>\`</kbd>.  
But if you have more windows as a full screen, the switching is not working as you want. 

[Contexts](https://contexts.co/) enable to switch windows as I want.  
Just try to use this app. :D

> **Utility**  
## Chrome

This is **Default Web Brower**([Link](./application/chrome/README.md)), it has more extension.  
Specially, I use 1Password extension to fill login information. 

## 1Passowrd

## Things 3

## Spark

## Amphetamine

## Dozer

## App Cleaner

## Spotify & Boom 3D & BeardedSpice

## iMazing

> **Develop**  
## iTerm2
This is **Defalt Terminal**([Link](./application/iterm/README.md)), this is well-known terminal app.  
You can customize it and set status for mac.  

## Sublime Text 3
This is **Default Text Editor**([Link](./application/sublime_text/README.md)), it is simple and fast.

## IDEA

## Paw
[Go to Top](#index)

---  
# System Preferences
There are just screenshots to set 'System Preferences'.  
If you want to see [more](system_preferences/README.md) ...  
[Go to Top](#index)

---  
# Terminal Tweaks
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
[Go to Top](#index)  