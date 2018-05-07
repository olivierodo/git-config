# Git config

This repository is used as a sub module of my [dotfiles repo](https://github.com/olivierodo/dotfiles)

### Getting started (stand alone)

Install the files

```
ln -s $(pwd)/.gitconfig ~/.gitconfig
ln -s $(pwd)/.gitconfig.local ~/.gitconfig.local
ln -s $(pwd)/.gitignore ~/.gitignore
```

Configuration

```
git config --file ~/.gitconfig.local user.name [YOUR NAME]
git config --file ~/.gitconfig.local user.email [YOUR EMAIL]
