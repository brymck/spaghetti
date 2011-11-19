spaghetti
=========

A Ruby script to help with translation copypasta.

Installation
------------

Run the following in a command line console:

    git clone git://github.com/brymck/spaghetti.git
    cp spaghetti/spaghetti ~/bin
    touch ~/.spaghetti/sauce.yml

Usage
-----

Add a word

    spaghetti add english noodle japanese 麺

Find-replace added words for a file

    spaghetti convert test1.txt test2.txt from japanese to english
