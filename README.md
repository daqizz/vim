# vim
vim备份
Backup your old vim configuration files:

1. mv ~/.vim ~/.vim.backup
 mv ~/.vimrc ~/.vimrc.backup
Clone and install this repo:

2.git clone git@github.com:FlowerWrong/fw-vim.git ~/.vim
 ln -s ~/.vim/vimrc ~/.vimrc
3.Setup Vundle:

 git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim
4.Install plugins. Launch vim(ignore the errors) and then run:

 :PluginList
 :PluginInstall
