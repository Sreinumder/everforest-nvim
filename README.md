fork of https://github.com/neanias/everforest-nvim for some minor changes.
lazy.nvim setup:
```
return {
		"Sreinumder/everforest-nvim",
		-- "neanias/everforest-nvim",
    priority = 1000, -- make sure to load this before all the other start plugins
    config = function()
      vim.cmd([[colorscheme everforest]])
		end,
},
```
