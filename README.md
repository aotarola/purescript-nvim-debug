# purescript-nvim-debug

`purescriptls` not working in `nvim-lsp-installer`

Steps to repro:

1. `nvim -u minimal_debug_init.lua`
1. `:LspInstall purescriptls`
1. `:LspInfo`

It will show as no executable is was found
