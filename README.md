# pyrep

Search and/or replace regular expressions within many files interactively.

(C) Martin Väth (martin at mvath.de).
This project is under the BSD license.

There is a successor project
https://github.com/vaeth/replacer
Use that instead since it is better in almost every aspect:

When I wrote this code many years ago, python has just been released.
There was no python style recommendation out there (or I was not aware of).
From current viewpoint the code reads rather ugly and hardly pythonic.
However, I left it unchanged except for some python2/3 compatibility quirks.

`pyrep` (*Py*thon g*rep*) is a python script with which you can search
and also replace regular expressions in a collection of files.
Its functionality is similar to the perl script `plrep` from
https://github.com/vaeth/mv_perl/

To install this script, just copy the content of bin/ into your `$PATH`.
To get zsh completion, copy the content of zsh/ to your zsh's `$fpath`,
perhaps `/usr/share/zsh/site-functions/`.

For Gentoo, there is an ebuild in the `mv` repository
(available by `app-select/eselect-repository` or `app-portage/layman`).
