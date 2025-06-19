# nvim

My personal Neovim configuration built from [kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim).

## Features

- **Lightweight**: Minimal and fast configuration
- **Well-documented**: Clear code structure and comments
- **LSP Integration**: Language server support out of the box
- **Modern plugins**: Carefully curated plugin selection
- **Git integration**: Built-in git workflow support

## Requirements

- Neovim >= 0.9.0
- Git
- A C compiler (gcc)
- [ripgrep](https://github.com/BurntSushi/ripgrep)
- [fd](https://github.com/sharkdp/fd)
- A [Nerd Font](https://www.nerdfonts.com/) (optional, for icons)

## Installation

1. Backup your existing Neovim configuration (if any)
2. Clone this repository:
   ```bash
   git clone https://github.com/ajaikumarvs/nvim.git ~/.config/nvim
   ```
3. Start Neovim:
   ```bash
   nvim
   ```
4. Let the plugins install automatically

## Structure

```
├── init.lua              # Main configuration entry point
├── lua/
│   ├── custom/           # Custom configurations and plugins
│   └── kickstart/        # Core kickstart modules
└── doc/                  # Documentation
```

## Customization

The configuration is designed to be easily customizable:

- **Plugin management**: Uses [lazy.nvim](https://github.com/folke/lazy.nvim)
- **Custom plugins**: Add your plugins in `lua/custom/plugins/`
- **Personal settings**: Modify `init.lua` for your preferences

## Acknowledgments

Built upon the excellent foundation of [kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim) by the Neovim community.

