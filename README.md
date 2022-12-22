# nvim-config
Neovim setup using Lua.

## Installation
1. Install Neovim.
2. Clone repo into `~/.config/`
3. Navigate to `nvim/lua/hamza/packer.lua` and open with nvim.
4. Run the `:so` command.
5. Run the `:PackerSync` command and wait for the plugins to be installed.
6. Check `remap.lua`, `set.lua`, and the `after/plugin/` directory for keymaps.

## Setup lsp for Python
1. Open any `.py` file in nvim.
2. `lsp-zero` will prompt user to select an lsp for installation -> choose `Pyright`
3. [Optional] check for correct installation of lsp using the `:Mason` command.
4. **In a project** folder, create a `pyrightconfig.json` file specifying options (see microsoft/pyright for docs). Important: specify `"venvPath"` and `"venv"` so that pyright knows which packages to look up.

## Acknowledgement

Credit goes to ThePrimeagen: https://www.youtube.com/watch?v=w7i4amO_zaE
