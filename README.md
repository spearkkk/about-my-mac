# Index
[tl;dr](./tl-dr/README.md)
- [Chrome](#chrome)

---
### Chrome
Default web browser, but sometimes I use Safari.

*preference*
- *`Font size`: 'Large'*
- *Set `Show warning before quitting with ⌘Q`: disabled*
- *Check extension*
  
[Go to Top](#index)
---

### Iterm
Default **terminal app**, [iTerm2](https://iterm2.com/downloads.html).
This is well-known terminal app. You can customize it and set status for mac.  

*preference*
*Add the Theme(gruvbox dark hard 256): [contribution](https://github.com/martinlindhe/base16-iterm2/tree/master/itermcolors)*
*Sync Preferences: ☁️, `~/Dropbox/application/Iterm2`* 
  
[Go to Top](#index)
---

### 1Password
Password manager  
If you stil rememeber you **password**, **license**, and **some secret thing** or write them to paper,  
You can write them into [1Password](https://1password.com/) and get them when/what you want.  
This app also supports IOS, web, and more.
  
[Go to Top](#index)
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

*preference*
- *Enable License: 🔐* 
- *Sync Preferences: ☁️, `~/Dropbox/application/Alfred4`*
  
[Go to Top](#index)
---

### Better Touch Tool
All inputs through mac can customized as you want if you have **Better Touch Tool**.  

I have a another keyboard, but sometimes I have to use keyboard of this mac.  
When I push <kbd>fn</kbd>, I can press function key. But it is awkward to press function key in IDEA.  
So I just mapped number key to function using [Better Touch Tool](https://folivora.ai/).

*preference*
- *Sync Preferences: ☁️, Dropbox*
- *Install Preset: [Link](https://goldenchaos.net/goldenchaos-btt.html)*
  
[Go to Top](#index)
---

### Contexts
Contexts manages all windows and application in my mac.  
When you want to switch between application, you press <kbd>command</kbd> + <kbd>tab</kbd>.  
Or when you want to switch windows between in a application, you press <kbd>command</kbd> + <kbd>\`</kbd>.  
But if you have more windows as a full screen, the switching is not working as you want. 

[Contexts](https://contexts.co/) enable to **switch windows as I want**.  
Just try to use this app.

*preference*
- *Set Preference: [Link](./preference/context/READMD.md)*
  
[Go to Top](#index)
---

### Sublime Text
[Sublime Text](https://www.sublimetext.com/) is **Text Editor**, it is simple and fast.  

*preference*  
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

*preference*
- *Editor Tabs: Tab placements: 'None', Tab limit: '1'*
- *Plugins: Gruvbox Theme: dark hard*
- *Plugins: Rainbow Brackets*
- *Plugins: String Manipulation*
  
[Go to Top](#index)
---

### Things3
Have you heard *GTD*? 
> 'Getting Things Done' is a time management method, ...  
>  from wikipedia

When you are focusing on something, there are times when an idea suddenly comes to mind.  
You do not have to worry about missing that idea anymore.

1. Just put in idea, [Things](https://culturedcode.com/things/).
2. Get it from Things when you want.
3. Do it.

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
  
[Go to Top](#index)