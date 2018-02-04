由于原版本的命令很容易冲突，所以改了下命令

--------------------------------------------------------------------------

### Bashmarks is a shell script that allows you to save and jump to commonly used directories. Now supports tab completion.

## Install

1. git clone git://github.com/huyng/bashmarks.git
2. cd bashmarks
3. make install
4. source **~/.local/bin/bashmarks.sh** from within your **~.bash\_profile** or **~/.bashrc** file

## Shell Commands

    sss <bookmark_name> - Saves the current directory as "bookmark_name"
    ggg <bookmark_name> - Goes (cd) to the directory associated with "bookmark_name"
    ppp <bookmark_name> - Prints the directory associated with "bookmark_name"
    ddd <bookmark_name> - Deletes the bookmark
    lll                 - Lists all available bookmarks
    
## Example Usage

    $ cd /var/www/
    $ sss webfolder
    $ cd /usr/local/lib/
    $ sss locallib
    $ lll
    $ ggg web<tab>
    $ ggg webfolder

## Where Bashmarks are stored
    
All of your directory bookmarks are saved in a file called ".sdirs" in your HOME directory.
