# vim-terminal
Use terminal easily in vim.(only support 8.1)

### Toggle
![toggle](img/toggle.gif?raw=true)

### Add tab
![add](img/tab.gif?raw=true)

### Switch tab
![change](img/change_tab.gif?raw=true)

## Feature
* Quickly open and close terminal with `:VSTerminalToggle`.
* Tab management with `:VSTerminalOpenNew`, `:VSTerminalOpenWithIndex`, `:VSTerminalDeleteWithIndex`.
* Use `g:vs_terminal_custom_height` to config terminal height.
* Use `g:vs_terminal_custom_pos` to config terminal position.('top' or 'bottom')
* Use `g:vs_terminal_custom_command` to config default command.(like `/bin/sh`)


## Install
`vim-terminal` should work with any modern plugin managers for Vim.
* [vim-plug](https://github.com/junegunn/vim-plug)
  * `Plug 'PangPangPangPangPang/vim-terminal'`
  
## Usage
Below are some helper lines in my `.vimrc`

```vim
" Quick toggle terminal.
Plug 'PangPangPangPangPang/vim-terminal'
" Plug 'PangPangPangPangPang/vim-terminal', { 'branch' : 'dev' }
map <silent> <F12> :VSTerminalToggle<cr>
tmap <silent> <F12> <c-w>:VSTerminalToggle<cr>
```

## Lisence
MIT License. Copyright (c) 2018 Max Wang.
