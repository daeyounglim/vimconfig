## ⚙️  vim config
This repo contains the `.vimrc` file and related packages used to decorate my
vim environment.

## 🔓 Package managers
The following 2 package managers are included in the `.vimrc` file:
  + [vim-plug](https://github.com/junegunn/vim-plug)
  + [Vundle](https://github.com/VundleVim/Vundle.vim)

## 🏳️‍🌈 Color scheme
[vim-colorscheme](https://github.com/flazz/vim-colorschemes) provides a variety
of color schemes for vim. Follow the instructions in the link. The current
colorscheme configured in the `.vimrc` file is `apprentice`.

## 🔨 Installation
This repo tracks the `.vim/` folder, which implies the `.vimrc` file is located
in `.vim/` folder. Clone this repo under `~/.vim/` and create the symbolic link for `~/.vim/.vimrc` under `~/` by
running the following command:
```bash
# if you don't have ~/.vim/ folder
# uncomment and run the following
# mkdir ~/.vim
cd ~/.vim
ln -s ~/.vim/.vimrc ~/.vimrc
```

