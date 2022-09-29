# nvim-setup
Plugin file for setting up nvim

- Install main libraries

$ brew install neovim
$ brew install gopls
$ sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'

- Setup config in ~/.config/nvim directory

- Install Plugins

$ nvim +PlugInstall


* Some useful shortcut keys:

1. Leader key was mapped to ','

gd : Go to definition

gi : Go to implementation

tab + T: Display directory tree

ctrl-o : Go back previous open file

ctrl-p : Open fzf search window

ctrl-u : Scroll page up

ctrl-d : Scroll page down

,ae : switch to test file

,-tab : switch between previous file

2. On fzf window:
2.1. We can use: Ctrl + K / J to move up / down on file list
2.2. We can use: Ctrl + U / D to move up / down on preview window

