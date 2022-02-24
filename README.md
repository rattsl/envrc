# what is this
this repository is for Linux Development Environmental Setup(NeoVim, Tmux, Zsh)

# Installation

install Neovim(vim), Tmux, Zsh

```
$ brew install screen
$ brew install tmux
$ brew install vim
$ brew install neovim
```

---


## Install zsh

```
$ brew install zsh
$ echo $SHELL
$ chsh -s /bin/zsh
```

## Setup .zshrc

```
$ cp .zshrc ~/
$ exec zsh
```

## Install nvim

```
# brew install neovim 
```

## Setup nvim conf

```
$ cp init.vim ~/.config/nvim/ 
```

## Installation vim-plug

[vim-plug](https://github.com/junegunn/vim-plug)

```
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```

### Pligins
## Setup git alias
