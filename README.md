#updot
Updot is a dotfile update script that keeps your dotfiles in sync between
computers via GitHub.

This script copies the specified dotfiles to `~/dotfiles`, and then symlinks
them back into their original locations.

##Usage
Just run `updot.py`, and the rest should be handled for you.

The script will ensure that your `gitconfig` settings are correct, that you
have an ssh key set up with GitHub, and will configure the local and remote
repository for you.

The dotfiles you want tracked should be added to the `dotfiles.manifest` file
located in the `~/dotfiles` directory.
