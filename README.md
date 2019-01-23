# dotfiles

## vimrc installation

1. Copy the `.vimrc` file to your home directory (likely `~`).

2. Install the [plug](https://github.com/junegunn/vim-plug) manager for libraries.

`curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim`

3. Load vim and install the plugins

```
:PlugInstall
```
