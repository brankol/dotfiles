# dotfiles

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

