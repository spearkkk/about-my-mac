### Index
- [Iterm 2](#iterm-2)
  * [Setting from iCloud](#setting-from-icloud)
  * [Theme](#theme)
- [zsh](#zsh)
  * [Command Line Tools](#command-line-tools)

# Iterm 2
Default terminal is not good to me. I just use [iTerm2](https://iterm2.com/downloads.html).  
**Setting from iCloud**: `iCloud/application/iterm/`  

## Theme
I set color scheme as **gruvbox**. I referred this [contribution](https://github.com/martinlindhe/base16-iterm2/tree/master/itermcolors).  
[Go to Top](#index)

---
# zsh
`zsh` is alternative to bash. Actuall I installed `fish` but It is akward to me.
So I prefer [zsh](https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH).  
Just do it if you have Homebrew.

```shell
  brew install zsh
```
* [Oh My zsh!](https://github.com/ohmyzsh/ohmyzsh): Plugin manager for `zsh`.
* [Powerlevel10k](https://github.com/romkatv/powerlevel10k): Make it more fast.

## Command Line Tools
* [bat](https://github.com/sharkdp/bat): Alternative to `cat`.
* [fd](https://github.com/sharkdp/fd): Alternative to `find`.
* [ripgrep](https://github.com/BurntSushi/ripgrep): Alternative to `grep`.
* [exa](https://github.com/ogham/exa): Alternaive to `ls`.
  ```shell
    alias l="exa --long --header --icons --sort=modified --reverse"
  ```
* [jenv](https://github.com/jenv/jenv#1-getting-started): Java Version Manager.
* [pyenv](https://github.com/pyenv/pyenv#homebrew-on-macos): Python Version Manager.
* [virtualenv](https://github.com/pyenv/pyenv-virtualenv): Virtual Environment for Python.
* [nvm](https://github.com/nvm-sh/nvm): Node Version Manger.
  
[Go to Top](#index)

