dotfiles-git
============

My ~/.config/git/, global gitignore, gitconfig, etc.

## Installation

    cd ~/.config
    mkdir git
    cd git

Copy all the files in the new git directory.

    cd ~
    ln -s .config/git/gitconfig .gitconfig
    
Create ~/.config/git/gitconfig-local with this content:

    [user]
        name = Your Name
        email = you@example.com
