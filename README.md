Gitroot
=======

Possibility to change to your gitroot very fast in bash.
It comes handy working on large git projects(like for example Magento) and reviewing changes.

Initialize
=======

. ./gitroot

Usage
=======

This will add new commandline functions to your commandline:

1. "gd" (or "gitroot gd" if gr is already taken)
2. "gr" (or "gitroot gr" if gr is already taken)


gd
------
Will change your current directory to the git root directory.

gr
------
Echoes the gitroot directory without a end of line.

It can be used for copying files inside your git project.
cp filetocopy.txt $(gr)/path/in/git/to/newfile.txt

Permanent use
=======
Apeend content of the gitroot file without first line to:

Current user:
- ~/.bashrc
- ~/.bash_aliases

Global:
/etc/bash.bashrc

