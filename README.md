# ZBrowse

When doing a shell work, it is often the case that `echo $variable` is invoked multiple times,
to check result of a loop, etc. Now, just pressing `Ctrl-B` is needed, with `ZBrowse` – `Zshell`
variable browser:

![ZBrowse](https://github.com/zdharma/zbrowse/blob/master/images/zbrowse.png)

(you can resize the video like web page)

[![asciicast](https://asciinema.org/a/120239.png)](https://asciinema.org/a/120239)

## Installation

First install [ZUI](https://github.com/zdharma/zui) plugin (it's an UI library).

**The plugin is "standalone"**, which means that only sourcing it is needed. So to
install, unpack `zbrowse` somewhere and add

```zsh
source {where-zbrowse-is}/zbrowse.plugin.zsh
```

to `zshrc`.

If using a plugin manager, then `Zplugin` is recommended, but you can use any
other too, and also install with `Oh My Zsh` (by copying directory to
`~/.oh-my-zsh/custom/plugins`).

### [Zplugin](https://github.com/psprint/zplugin)

Add `zplugin load zdharma/zbrowse` to your `.zshrc` file. Zplugin will handle
cloning the plugin for you automatically the next time you start zsh. To update
issue `zplugin update zdharma/zbrowse` (`update-all` can also be used).

### Antigen

Add `antigen bundle zdharma/zbrowse` to your `.zshrc` file. Antigen will handle
cloning the plugin for you automatically the next time you start zsh.

### Oh-My-Zsh

1. `cd ~/.oh-my-zsh/custom/plugins`
2. `git clone git@github.com:zdharma/zbrowse.git`
3. Add `zbrowse` to your plugin list

### Zgen

Add `zgen load zdharma/zbrowse` to your .zshrc file in the same place you're doing
your other `zgen load` calls in.
