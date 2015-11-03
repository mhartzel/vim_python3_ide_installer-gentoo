
This is my shell script to install vim and other packages so that I can use vim as my Python3 development environment.

This program will do the following things:

Uninstall previous vim packages and old vim configuration. All Gentoo specific vim modifications are removed.
Download latest vim source from git repository. Compile and install a new vim with Python3 support.
Download and install 256 color capable urxvt terminal emulator and set it up to use clipboard and the Terminus font.
Install vim plugins Pathogen and Tagbar to make vim a Python3 IDE.
Remove most color schemes that come with vim, leaving only: default, desert, murphy and slate.
Install 256 color vim colorschemes: desert256, distinguished, jellybeans, solarized.

