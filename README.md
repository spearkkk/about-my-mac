# About My Mac

## Homebrew
[Installation](https://docs.brew.sh/Installation): Super Aaaaaaawesome Package Manager  
If you are use this tool, you can save your time.

## Font & Color Scheme
### Font
[Installation](https://github.com/ryanoasis/nerd-fonts): Hack Nerd
### Color Scheme
I prefer `gruvbox` color scheme.
* [Link](https://github.com/morhetz/gruvbox)
* [Contribution Link](https://github.com/morhetz/gruvbox-contrib)

# Application
## Chrome
Default Web Brower([Link](./application/chrome/README.md)), it has more extension.  
Specially, I use 1Password extension to fill login information. 

## Alfred
Default Launcher([Link](./application/alfred/README.md)), it has more feature than Spotlight.  
* can search anything in my mac.
* can search something in web without fousing web browser.
* can store/get in clipboard, text, image, and file.
* can convert text using snippet.
* can explore your mac more and more using Workflow.
## Sublime Text 3
Default Text Editor([Link](./application/sublime_text/README.md)), it is simple and fast.

## iTerm2
Defalt Terminal([Link](./application/iterm/README.md)), this is well-known terminal app.  
You can customize it and set status for mac.

# System Preferences
[More](system_preferences/README.md)

# Terminal Tweaks
## Quick Look
### Animation
**Apply**
```shell
defaults write -g QLPanelAnimationDuration -float 0; killall Finder
```
**Reset**
```shell
defaults delete -g QLPanelAnimationDuration; killall Finder
```
##  Dock
### Delay
**Apply**
```shell
defaults write com.apple.Dock autohide-delay -float 0; killall Dock
```
**Reset**
```shell
defaults delete com.apple.dock autohide-delay; killall Dock
```
### Animaion
**Apply**
```shell
defaults write com.apple.dock autohide-time-modifier -float 0; killall Dock
```
**Reset**
```shell
defaults delete com.apple.dock autohide-time-modifier; killall Dock
```
## Launch Pad
### Animation
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
## Pop-up&Dialog
### Animaion
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
## Screenshot
###  File Format
Default: .png
```shell
defaults write com.apple.screencapture type PDF; killall SystemUIServer
```
### File Path
Default: ~/Desktop
```shell
defaults write com.apple.screencapture location /drag/location/here; killall SystemUIServer
```