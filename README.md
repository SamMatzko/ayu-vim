**This project is forked from [ayu-vim](https://github.com/ayu-theme/ayu-vim); you can see its original README there.**

This fork is for customizing the colors so that they look nicer and give higher contrast. Note that only the **dark mode** is affected by these changes.

![higher contrast](https://github.com/SamMatzko/ayu-vim/assets/95320171/b1ba5501-d71a-467b-9f71-6b16210e19c3)

# Warning
`ayu` is still in development and a lot of things need to be covered. Theme works only if VIM supports `termguicolors` option. This is true for [Neovim](https://neovim.io) and VIM from 7.4.1799.

# Installation
```VimL
Plug 'SamMatzko/ayu-vim' " or other package manager
"...
set termguicolors     " enable true colors support
let ayucolor="light"  " for light version of theme
let ayucolor="mirage" " for mirage version of theme
let ayucolor="dark"   " for dark version of theme (modified theme)
colorscheme ayu
```
