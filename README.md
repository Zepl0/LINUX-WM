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
  -- PACKER 
  use 'wbthomason/packer.nvim'

  -- THEMES
  use {'dracula/vim', as = 'dracula'}
  use 'Mofiqul/vscode.nvim'
  use 'shaunsingh/solarized.nvim'
  use 'shaunsingh/moonlight.nvim'
  use 'shaunsingh/nord.nvim'
  -- TREESITTER
  use {
    'nvim-treesitter/nvim-treesitter',
    run = ':TSUpdate'
  }
  -- TREE 
  use {
    'kyazdani42/nvim-tree.lua',
    requires = {
      'kyazdani42/nvim-web-devicons', -- optional, for file icon
    },
  }
  -- autotag
  use {'windwp/nvim-ts-autotag'}
  -- AUTO PAIRS
  use 'windwp/nvim-autopairs'
  -- RAIMBOW
  use {'p00f/nvim-ts-rainbow'}
  -- LUALINE
  use 'nvim-lualine/lualine.nvim'
  -- BUFFERLINE
  use 'akinsho/bufferline.nvim'
  -- WHICHKEY
  use 'folke/which-key.nvim'
  -- TELESCOPE
  use 'nvim-telescope/telescope.nvim'
  use 'nvim-lua/plenary.nvim'
  -- CMP 
  use 'neovim/nvim-lspconfig'
  use 'hrsh7th/cmp-nvim-lsp'
  use 'hrsh7th/cmp-buffer'
  use 'hrsh7th/cmp-path'
  use 'hrsh7th/cmp-cmdline'
  use 'hrsh7th/nvim-cmp'
  use 'hrsh7th/cmp-vsnip'
  use 'hrsh7th/vim-vsnip'
  -- LSPKIN
  use 'onsails/lspkind.nvim'

