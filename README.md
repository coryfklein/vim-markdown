# Vim Markdown Syntax Highlighting

This is a fork of [plasticboy/vim-markdown](https://github.com/plasticboy/vim-markdown) that just uses the syntax highlighting of markdown files. Unfortunately, plasticboy's plugins messed up my vim editing of markdown files. Specifically the automatic indentation surrounding bullets was crippling.

I find that vim's built in indentation capabilities are more than enough to suffice, so here I use just the files needed for getting the right highlighting.

## Installation

If you use [Vundle](https://github.com/gmarik/vundle), add the following line to your `~/.vimrc`:

```vim
Plugin 'coryfklein/vim-markdown'
```

Then run inside Vim:

```vim
:so ~/.vimrc
:PluginInstall
```

If you use [Pathogen](https://github.com/tpope/vim-pathogen), do this:

```sh
cd ~/.vim/bundle
git clone https://github.com/coryfklein/vim-markdown.git
```

To install without Pathogen using the Debian [vim-addon-manager](http://packages.qa.debian.org/v/vim-addon-manager.html), do this:

```sh
git clone https://github.com/coryfklein/vim-markdown.git
cd vim-markdown
sudo make install
vim-addon-manager install mkd
```
