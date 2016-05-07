# .tmux

Intialize and symlink

        $ cd ~
        $ ln -s ~/.tmux/tmux.conf ~/.tmux.conf

Install Plugins

        $ git submodule init
        $ git submodule update

To add a new plugin

        $ cd ~/.tmux
        $ git submodule add git@source/pluginname.git ~/.tmux/plugins/pluginname
