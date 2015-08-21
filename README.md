Fedora Done Quick
==================

Make Fedora instantly better with this install script.

There are a few shell scripts out there on GitHub, but most don't do what _I_ want them to, and even fewer actually come with a license. So rather than forking something without a license and feeling vaguely uncomfortable about it, I'm creating my own, and doing it right. Well, right enough. For me. Use at your own risk.

Other Fedora Setup Scripts
--------------------------

These scripts served as an inspiration for my own. If you're interested in creating your own version of this script, consider checking these other tools out first, as they might take an approach that appeals to you, or just give you some ideas of things you'd like to implement.

* Sam Hewitt's [Fedora Post Install Script](https://github.com/snwh/fedora-post-install/)

Todo
----

In lieu of using a bug tracker or tasklist, let me just lay out here the things I want to do:
* Add any extra repositories that I need: Chrome, RPM Fusion, ???
* Add all of the important pacakges to the package list
* Add some codecs
* Fonts?
* Set up ownCloud, possibly other integrated accounts?
* Probably some Gnome extensions, and maybe set up Compiz Fusion?
* Perhaps break these packages into some sort of grouping, so I can interactively install or not install a group of packages
* Add all of the changes that need to be made to my dotfiles, as well as any themes for things like VIM and the Gnome Shell that I can't live without

Oh, and the script should probably only run as root, so, uh, test for that.
