## Neovim lua configs
Neovim configs in lua for auto completions, copilot and much more.

### Installation
```
git clone https://github.com/DGclasher/nvim-lua ~/.config/nvim
```

Install [packer](https://github.com/wbthomason/packer.nvim) for neovim.
```
git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim
```

Open up [packer.lua](./lua/clasher/packer.lua) then source and sync the packages.
```
:source %
:PackerSync
```