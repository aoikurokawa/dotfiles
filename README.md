# Setup

## Alacritty
- https://zenn.dev/shinnopo/articles/798398b1d87f62

## Chezmoi
- https://www.chezmoi.io/install/


## Manage dotfiles

## Neovim

1. Install latest version [nvim](https://github.com/neovim/neovim/releases/tag/stable)
2. Extract the file that downloaded previously
3. Run
```bash
sudo mv ~/Downloads/nvim-linux64/bin/nvim /opt/
sudo ln -s /opt/nvim /usr/local/bin/nvim
```
4. Create init.lua
```bash
mkdir -p ~/.config/nvim
cd ~/.config/nvim
nvim init.lua
```
5. Copy paste this [file](https://github.com/nvim-lua/kickstart.nvim/blob/master/init.lua)

- Sample [link](https://www.youtube.com/watch?v=stqUbv-5u2s)


## NOTES
- [How to ignore folder when search files](https://stackoverflow.com/questions/68563040/how-to-make-telescope-ignore-files-inside-node-modules)
