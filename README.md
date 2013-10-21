Repository for dotfiles
=======================

This repository contains several dotfiles like .bashrc and .vimrc, so that
configuration can be easily shared across computers.

For installation of the files, "GNU Stow" can be used. The hierarchy of the
dotfiles directory has to emulate the intended installation directory (~/ for most files).

So, to install the files to the home directory, use "stow" like this:

$ cd ~/dotfiles
$ stow bash
$ stow vim
etc

