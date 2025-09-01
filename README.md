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
OSH_THEME="powerline-plain"
```

## Tmux

https://github.com/gpakosz/.tmux

### Customization

`C-b e` to edit local settings

```
# this is the place to override or undo settings
set-option -g repeat-time 0

# start with mouse mode enabled
2 set -g mouse on

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
colorscheme unokai

set number
set relativenumber
```
