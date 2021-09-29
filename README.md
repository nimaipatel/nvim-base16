# nvim-base16

Neovim plugin for building base16 colorschemes with support for Neovim's
builtin LSP and Treesitter.

This is a fork of https://github.com/RRethy/nvim-base16/ with the pre-built
colorschemes removed to decrease the load time. People who use an external
build tool like https://github.com/Misterio77/flavours can use this. 

```lua
-- You can provide a table specifying your colors to the setup function.
require('base16-colorscheme').setup({
    base00 = '#16161D', base01 = '#2c313c', base02 = '#3e4451', base03 = '#6c7891',
    base04 = '#565c64', base05 = '#abb2bf', base06 = '#9a9bb3', base07 = '#c5c8e6',
    base08 = '#e06c75', base09 = '#d19a66', base0A = '#e5c07b', base0B = '#98c379',
    base0C = '#56b6c2', base0D = '#0184bc', base0E = '#c678dd', base0F = '#a06949',
})
```
