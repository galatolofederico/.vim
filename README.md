# dotvim

My (hopefully) maintained vim configuration

## Installation

To install the .vimrc

```
[[ -f ~/.vimrc ]] && mv ~/.vimrc ~/.vimrc.bak
git clone git@github.com:galatolofederico/dotvim.git ~/dotvim
ln -s ~/dotvim/.vimrc .vimrc
```

This repository uses [vim-plug](https://github.com/junegunn/vim-plug) so install it

```
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

To install the plugins on `vim` type 

```
:PlugInstall
```

To install [YouCompleteMe](https://github.com/ycm-core/YouCompleteMe)

```
cd ~/.vim/plugged/YouCompleteMe/
python3 install.py --all
```

