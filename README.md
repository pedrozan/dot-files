# dot-files
My configurations for Ubuntu development happiness

## Contents
- [Installation](#installation)
    - [NeoVim](#neovim)
    - [Zshell](#zshell)

- [Fonts](#fonts)

## Installation

### NeoVim

- Install NeoVim;
- Copy `nvim/init.vim` to `~/.config/nvim/init.vim`, you might need to create this file;
- Copy `nvim/plugins.vim` to `~/.config/nvim/plugins.vim`;
- Open Neovim `$ nvim` and run :PlugInstall and :UpdateRemotePlugins. You might need to close and re-open Neovim;
- Install the vim linter vint with `pip3 install vim-vint`;
- Install `ripgrep` for Ubuntu with Snap, `sudo snap install ripgrep --classic`;
- Copy custom vim airline theme by [Caleb Taylor](https://github.com/ctaylo21): `nvim\space.vim\` to `~\.config\nvim\plugged\vim-airline-themes\autoload\airline\themes\space.vim`;
- Install Nerd Fonts to make it pretty.

### ZShell and OhMyZshell

- Install Zshell: `$ sudo apt-get update && sudo apt-get install zsh`;
- Install [OhMyZshell](https://ohmyz.sh/): `$ sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
- Copy configurations from `zshell/.zshrc` to `~/.zshrc`, you might want to make a backup of your old `.zshrc` with `$ mv ~/.zshrc ~/_zshrc`


## Fonts
All fonts can be obtained from [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts)
