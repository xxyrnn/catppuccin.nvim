# catppuccin.nvim

Personal port of the Catppuccin Mocha theme for Neovim

Original theme: [https://github.com/catppuccin/nvim](https://github.com/catppuccin/nvim)

## Installation

- lazy.nvim

  ```lua
  return {
      "xxyrnn/catppuccin.nvim",
      lazy = false,
      priority = 1000,
      config = function()
          vim.cmd("colorscheme catppuccin")
      end
  }
  ```
