# What is this
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

## Install oh-my-zsh

[oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh)

```
$ sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```


## Setup .zshrc

```
$ cp .zshrc ~/
$ source .zshrc
$ exec zsh
```

## Install nvim

```
$ brew install neovim 
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

## Install plugins list

- [vim-horizon](https://github.com/ntk148v/vim-horizon)
- [nerdtree](https://github.com/preservim/nerdtree)
- [vim-plug](https://github.com/junegunn/vim-plug)
- [fzf](https://github.com/junegunn/fzf#vim-plugin)
- [vim-fugitive](https://github.com/tpope/vim-fugitive)
- [vim-commentary](https://github.com/tpope/vim-commentary)
- [coc.vim](https://github.com/neoclide/coc.nvim)

## Vim-plug commands


```
// plugin install
:PlugInstall

// plugin status
:PlugStatus

// pligin update
:PlugUpdate
```

## Coc.nvim Extensions

```
:CocInstall coc-json coc-tsserver coc-markdownlint coc-markdown-preview-enhanced
:CocList extensions

```

## Setup .tmux.conf

replace `Ctl + g` from `Ctl + b`

```
$ cp .tmux.conf ~/
```

