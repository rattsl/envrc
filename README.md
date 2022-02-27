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
## Oh-my-zsh plugin install
This plugins are 3rd party liblary, so we need `git clone` to install those plugins.

- [auto-suggestion](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#oh-my-zsh)
```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

- [powerlevel10k](https://github.com/romkatv/powerlevel10k)

Before installing this plugin, we need some [fonts](https://github.com/romkatv/powerlevel10k#fonts), and configure your terminal to use this font.

```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
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

