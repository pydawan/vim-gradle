# VIM-GRADLE #

This vim bundle simply recognizes .gradle files as being groovy syntax.

## Installing and Using ##

- Install [pathogen](http://www.vim.org/scripts/script.php?script_id=2332) into `~/.vim/autoload/` and add the
   following line to your `~/.vimrc`:

        call pathogen#infect()

- Make a clone of the `vim-gradle` repository:

        $ mkdir -p ~/.vim/bundle
        $ cd ~/.vim/bundle
        $ git clone https://github.com/tfnico/vim-gradle

- OR use git submodules:

        $ git submodule add https://github.com/tfnico/vim-gradle.git bundle/vim-gradle
        $ git submodule init

Of course, if you use [Janus](https://github.com/carlhuda/janus/), you should put the clone in ~/.janus/
instead.

That's it. Pathogen should handle the rest, and use groovy syntax
highlighting when opening .gradle files.

## Credits ##

Inspiration from [vim-less](https://github.com/groenewege/vim-less).
