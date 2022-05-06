# purescript-nvim-debug

`purescriptls` not working in `nvim-lsp-installer`

Steps to repro:

1. `nvim -u minimal_debug_init.lua`
1. `:LspInstall purescriptls`
1. `:LspInfo`

It will show as no executable is was found:

![Screen Shot 2022-05-05 at 19 15 47](https://user-images.githubusercontent.com/1557740/167056276-11b96d16-62c7-47d3-9f9e-86ba21523066.png)
