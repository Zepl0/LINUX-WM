# LINUX-WM

### Current Twm: BSPWM -> desktop:
![image](https://user-images.githubusercontent.com/100967935/168469678-dcb96476-8012-4cc9-b7c2-a0008be70aae.png)


Apps and packages that I have installed on my system: 

- Polybar -> status bar
- picom from yay ( yay -S picom-tryone-git ) -> transparency
- firefox -> web Browser
- chromium -> web Browser
- qetubrowser 
- pulseaudio -> audio
- pavucontrol -> audio control
- lxapparence
- nvim -> editor
- flameshot -> screenshots
- kitty -> terminal
- vlc -> video player
- xarchiver -> file umpressor
- thunar -> file manager
- ArandR -> Monitor screen size manager
- font-manager

## fonts
https://github.com/epk/SF-Mono-Nerd-Font
-> Hack Nerd Font
-> Jet Brain Nerd Font
-> Agave Nerd Font

## Snippets for VSNIps
1. HTML = https://github.com/abusaidm/html-snippets/blob/master/snippets/snippets.json
2. React = https://github.com/dsznajder/vscode-react-javascript-snippets/blob/master/src/snippets/generated.json
3. JavaScript = https://github.com/xabikos/vscode-javascript/blob/master/snippets/snippets.json
4. CSS = https://github.com/L13/vscode-css-snippets
5. C/C++ = https://github.com/one-harsh/vscode-cpp-snippets
6. LUA = https://github.com/niszet/pandoc-lua-snippet/blob/master/snippets/snippets.json
7. PYTHON = https://github.com/ylcnfrht/vscode-python-snippet-pack/blob/master/snippets/python_snippets.json

# NVIM

### Plugins using Packer as plugin manager
  #### -- PACKER 
  1. use 'wbthomason/packer.nvim'

  #### -- THEMES
  2. use {'dracula/vim', as = 'dracula'}
  3. use 'Mofiqul/vscode.nvim'
  4. use 'shaunsingh/solarized.nvim'
  5. use 'shaunsingh/moonlight.nvim'
  6. use 'shaunsingh/nord.nvim'
  #### -- TREESITTER
  7. use {
    'nvim-treesitter/nvim-treesitter',
    run = ':TSUpdate'
  }
  #### -- TREE 
  8. use {
    'kyazdani42/nvim-tree.lua',
    requires = {
      'kyazdani42/nvim-web-devicons', -- optional, for file icon
    },
  }
  #### -- autotag
  9. use {'windwp/nvim-ts-autotag'}
  -- AUTO PAIRS
  10. use 'windwp/nvim-autopairs'
  -- RAIMBOW
  11. use {'p00f/nvim-ts-rainbow'}
  -- LUALINE
  12. use 'nvim-lualine/lualine.nvim'
  -- BUFFERLINE
  13. use 'akinsho/bufferline.nvim'
  -- WHICHKEY
  14. use 'folke/which-key.nvim'
  -- TELESCOPE
  15. use 'nvim-telescope/telescope.nvim'
  16. use 'nvim-lua/plenary.nvim'
  #### -- CMP 
  17. use 'neovim/nvim-lspconfig'
  18. use 'hrsh7th/cmp-nvim-lsp'
  19. use 'hrsh7th/cmp-buffer'
  20. use 'hrsh7th/cmp-path'
  21. use 'hrsh7th/cmp-cmdline'
  22. use 'hrsh7th/nvim-cmp'
  23. use 'hrsh7th/cmp-vsnip'
  24. use 'hrsh7th/vim-vsnip'
  #### -- LSPKIN
  25. use 'onsails/lspkind.nvim'
