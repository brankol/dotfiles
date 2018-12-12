# dotfiles

[Using GNU stow to manage your dotfiles](http://brandon.invergo.net/news/2012-05-26-using-gnu-stow-to-manage-your-dotfiles.html)

## vim

### Install plugin as submodule
```
git submodule add http://github.com/tpope/vim-fugitive.git bundle/fugitive
git add .
git commit -m 'Install Fugitive.vim bundle as a submodule.'
```

### Install vim environment on another machine
```
cd dotfiles
git submodule update --init
```

Taken from [vimcasts](http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen/).

## fzf

After `stow fzf`, run `~/.fzf/install`.
Also be sure to install [ripgrep](https://github.com/BurntSushi/ripgrep#installation) as fzf is configured to use rg behind the scenes.

