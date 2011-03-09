# Arko's Dotfiles

My dotfiles.

*There is no place like 127.0.0.1* -- No longer valid...

# How to Install

If you want to stay up to date with the very latest code, clone the git repository:

    git clone git://github.com/Arko/dotfiles.git ~/.dotfiles

Or, if you don't have git, you can just download the latest source as a tarball:

    curl -L http://github.com/Arko/dotfiles/tarball/master -o arko-dotfiles-master.tar.gz
    tar -xzvf arko-dotfiles-master.tar.gz

Finally, change to the cloned or extracted dotfiles directory and run install

    ./install

## What will happen?

Whether you use `git clone` or the tarball download, running the install script will:

1. Check for conflicting files and offer to safely backup them.
2. Create the ~/.dotfiles directory, if needed
3. Copy all dotfiles to ~/.dotfiles, if needed
4. Symlink ~/.dotfiles/bashrc to ~/.bashrc
5. Symlink ~/.dotfiles/bash\_profile to ~/.bash\_profile
