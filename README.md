Installation
============
1. Get the plugin
-----------------
Using Pathogen https://github.com/tpope/vim-pathogen:

    cd ~/.vim/bundle
    git clone git://github.com/bbelyeu/pylint.vim.git

Manually:

    cd ~/.vim/compiler
    wget http://raw.github.com/bbelyeu/pylint.vim/master/compiler/pylint.vim

2. Setup ~/.vimrc
-----------------
To get Vim to auto-recognize pylint as Python's compiler, add the following line to your `~/.vimrc`:

    autocmd FileType python compiler pylint


Troubleshooting
===============
Make sure you have pylint installed (easy\_install pylint / apt-get install pylint).
Validate that `pylint <python file>` command works as expected.


Feedback
========
Post bugs, ideas and pull requests to http://github.com/bbelyeu/pylint.vim
