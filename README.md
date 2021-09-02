# ReScript parser for nvim-treesitter

This repository contains a thin wrapper around [ReScript parser for Tree-sitter](https://github.com/nkrkv/tree-sitter-rescript/) to make it an easy-to-install NeoVim plugin.

## Requirements

- NeoVim 0.5.0+
- Installed and configured [`nvim-treesitter`](https://github.com/nvim-treesitter/nvim-treesitter) plugin

## Installation

Add the plugin in your `init.vim`:

```vim
Plug 'nkrkv/nvim-treesitter-rescript'
```

or using [packer.nvim](https://github.com/wbthomason/packer.nvim):

```lua
use 'nkrkv/nvim-treesitter-rescript'
```

Install the newly available parser:

```
:TSInstall rescript
```

## Contributing

This is a technical repo containing a copy of the upstream [ReScript parser for Tree-sitter](https://github.com/nkrkv/tree-sitter-rescript/). Please, open issues and PR’s there. Unless the problem is indeed related to the plugin wrapping.
