Sublime Text 4 User Package
===========================

Configuration for Sublime Text 4. Wanted to start from scratch, porting over only the useful things from my Sublime Text 3 config.


Features
--------

1. `:s` invokes Replace panel
1. `Y` yanks to end of line, rather than the whole line. This annoyed me in Vim as well.
1. `:bd` closes current buffer
1. `:wq` saves current file and closes buffer
1. `:e` edits a file
1. `gd` invokes Goto Definition on the word under the cursor
1. *alt-up* and *alt-down* navigate build results instead of *F4*/*shift-F4*

Installation
------------

1. Install Sublime Text.
1. Install [Package Control](https://packagecontrol.io/installation).
1. Make a symlink from projects directory to Sublime Text user package for easy access.
    ```
    $ cd ~
    $ ln -s ~/"Library/Application Support/Sublime Text/Packages/User"
    ```
1. Clone this repo into that directory.
    ```
    $ cd "Sublime Text"
    $ git clone https://github.com/BryceLohr/Sublimetext4User.git .
    ```
1. Create a link to the OS-specific settings so Sublime can find them.
    ```
    $ cd ~/"Library/Application Support/Sublime Text/Packages/User/Packages"
    $ ln -s User/OS OS
    ```
1. Restart Sublime.

#### Note

The most recent installation was done by hand-picking files to copy over, instead of cloning this repo into the Sublime Text user page.
