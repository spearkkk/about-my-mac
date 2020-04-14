### Index
* [Setting](#setting)
* [Theme](#theme)
* [Package](#package)
  + [Markdown Preview](#markdown-preview)
  + [LiveReload for Sublime Text 3](#livereload-for-sublime-text-3)
* [Terminal to Sublime Text 3](##terminal-to-sublime-text-3)

# Sublime Text 3
I use two editor to write somethig, Notion and [Sublime Text](https://www.sublimetext.com/3).  
Notion has unlimited feature and is pretty good.  
But Notion is not fast as much as I expect.  

Sublime Text is fast and simple so I prefer to write something temporary.
And I am editing this documents using Sublime Text.

## Preference
<details>
  <summary>Expand...</summary>

```json
{
 "font_face": "Hack Nerd Font",
 "font_size": 18,
 "tab_size": 2,
 "remember_full_screen": true,
 "line_numbers": false,
 "fade_fold_buttons": false,
 "mini_diff": "auto",
 "translate_tabs_to_spaces": true,
 "indent_to_bracket": true,
 "highlight_line": true,
 "line_padding_top": 2,
 "line_padding_bottom": 2,
 "scroll_speed": 2.0,
 "highlight_modified_tabs": true,
 "show_tab_close_buttons": false,
 "bold_folder_labels": true,
}
```
</details>

## Theme
I set color scheme as **gruvbox**. I referred this [contribution](https://github.com/Briles/gruvbox).  

<details>
  <summary>Expand...</summary>

```json
{
  "theme": "gruvbox.sublime-theme",
  "color_scheme": "Packages/gruvbox/gruvbox (Dark) (Medium).sublime-color-scheme",
  "gruvbox_buttons_font_size_16": true,
  "gruvbox_command_palette_compact": true,
  "gruvbox_folder_icons_large": true,
  "gruvbox_folder_icons_square": true,
  "gruvbox_iconset_midstroke": true,
  "gruvbox_panel_xxs": true,
  "gruvbox_scrollbar_width_xl": true,
  "gruvbox_scrollbar_width_xs": true,
  "gruvbox_sidebar_cozy": true,
  "gruvbox_sidebar_font_size_10": true,
  "gruvbox_sidebar_heading_bold": true,
  "gruvbox_sidebar_indent_xxs": true,
  "gruvbox_sidebar_label_bold": true,
  "gruvbox_statusbar_button_xxs": true,
  "gruvbox_statusbar_font_size_16": true,
  "gruvbox_statusbar_xxs": true,
  "gruvbox_tabs_font_size_14": true,
  "gruvbox_tabs_xxs": true,
}
```
</details>

## Package
* [Markdown Preview](https://packagecontrol.io/packages/MarkdownPreview): Preview for markdwon.
* [LiveReload for Sublime Text 3](https://packagecontrol.io/packages/LiveReload): Not need to refresh anymore.
* Kotlin: Highlight Kotlin.
[Go to Top](#index)

---

# Terminal to Sublime Text 3
Add to this alias to `~/.zshrc`.
```shell
  alias open-here="open -a /Applications/Sublime\ Text.app `pwd`"
  alias open-there="open -a /Applications/Sublime\ Text.app `pbpaste`"
```
[Go to Top](#index)