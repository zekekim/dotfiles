# My dotfiles
This is my dotfiles! I spend a lot of time finnagling here and having fun setting up things within the terminal and for window managing as well.
Feel free to rip anything or contribute as well.

## Installation
Install GNU Stow using `brew install stow` or `apt install stow` for linux. To install any of these modules, do
```bash
stow <module name>
# or
stow . # to install all modules
```

## Prerequisites

### Neovim
The neovim config file requires you to first install `packer` and the most recent stable version of `neovim`.
Feel free to modify the themeing in the `/after/plugin/colors.lua` file.

### zsh
My zsh utilizes `oh-my-zsh` so make sure that you install that first.

### Alacritty
Alacritty is needed first!

### i3
My i3 config file contains buttons and background images that are specific to my computer, so you may need to swap things around there.
Additionally, `picom.conf` utilizes picom in order to enable background opacity and whatnot.
i3wm is needed first!


## Credits
Lots of my Neovim and i3 configuration is inspired by @theprimeagen. Thank you.

