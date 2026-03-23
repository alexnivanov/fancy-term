# fancy-term
Fancy configs for shell, vim &amp; tmux.

## Zsh

https://ohmyz.sh

## Bash

https://github.com/ohmybash/oh-my-bash

### Customization

```sh
vi ~/.bashrc
```

```
OSH_THEME="minimal"
```

```
# Example aliases
# alias bashconfig="mate ~/.bashrc"
# alias ohmybash="mate ~/.oh-my-bash"

# Enable line wrapping
alias less='less -FRXc'
```

## Tmux

https://github.com/gpakosz/.tmux

### Customization

`C-b e` to edit local settings

```
# this is the place to override or undo settings

# Fix nasty command timeout
set-option -g repeat-time 0

# start with mouse mode enabled
set -g mouse on

# replace C-b by C-a instead of using both prefixes
set -gu prefix2
```

## Vim

https://github.com/amix/vimrc

### Customization

```sh
vi ~/.vim_runtime/my_configs.vim
```

```
colorscheme dracula

set number
set relativenumber
```
