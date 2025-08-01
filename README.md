# Config files

## Getting started

### Install stow

#### Arch Linux

```bash
sudo pacman -S stow
```

#### MacOS

```bash
brew install stow
```

### Clone dotfiles

```bash
cd ~/dev/
git clone git@github.com:aoikurokawa/dotfiles.git 
```

### Create symlink

```bash
stow waybar/
```

## Software

### Hyprland

- Hyprlock
- Waybar

### Tmux

Stow tmux configuration

```bash
stow --dir=$HOME/dev/dotfiles/ --target=$HOME tmux
```

Read configuration file

```bash
tmux source-file ~/.config/tmux/tmux.conf
```

### Alacritty
- https://zenn.dev/shinnopo/articles/798398b1d87f62

## Manage dotfiles

## Neovim Setup

1. Install latest version [nvim](https://github.com/neovim/neovim/releases/tag/stable)
2. Extract the file that downloaded previously
3. Run
```bash
sudo mv ~/Downloads/nvim-linux64/ ~/
```
4. Add PATH
```bash
export PATH=$PATH:~/nvim-linux64/bin
```
* https://qiita.com/qq8244353/items/94cea37bf85c09dc4742

5. Following this instruction


- Sample [link](https://www.youtube.com/watch?v=stqUbv-5u2s)

## Rust analyzer
- https://rust-analyzer.github.io/manual.html#rust-analyzer-language-server-binary


## NOTES
- [How to ignore folder when search files](https://stackoverflow.com/questions/68563040/how-to-make-telescope-ignore-files-inside-node-modules)

## Resources
- https://www.gnu.org/software/stow/
