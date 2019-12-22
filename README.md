## Requirements
- ctags (yum install ctags on redhat based systems)
- vim must be compiled with perl & python (in order to use gundo)
  - ./configure --enable-perlinterp --enable-pythoninterp

### On OSX, use <a href="http://mxcl.github.com/homebrew/">homebrew</a> to install vim (terminal & gui):

    brew install ctags
    brew install macvim --override-system-vim

## Install

    git clone https://github.com/sesaravanan7/vim_settings.git .vim
    cd .vim
    ln -s ~/.vim/vimrc ~/.vimrc

## Customization

    ~/.vim/vimrc.$USER
