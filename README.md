% Haskell Bindings to Bibutils, the Bibliography Conversion Utilities
% Andrea Rossato

About
-----

[hs-bibutils] is library with Haskell bindings to Chris Putnam's
[bibutils], a library that interconverts between various bibliography
formats using a common MODS-format XML intermediate.

[hs-bibutils] can be used with [citeproc-hs] and [pandoc] to read and
use various bibliographic database formats for processing and
automatically formatting citations and references according to a [CSL]
style.

[citeproc-hs] adds to [pandoc], the famous [Haskell] text processing
tool, a Bibtex like citation and bibliographic formatting and
generation facility.

[CSL] is an XML language for specifying citation and bibliographic
formatting, similar in principle to BibTeX `.bst` files or the binary
style files in commercial products like Endnote or Reference Manager.

Download
--------

[hs-bibutils] can be downloaded from [Hackage]:

<http://hackage.haskell.org/cgi-bin/hackage-scripts/package/hs-bibutils>

To get the darcs source run:

        git clone https://github.com/wilx/hs-bibutils.git

Installation
------------

[hs-bibutils] does not require [bibutils] to be installed, since it
ships with its one version of the library. To build and install
[hs-bibutils] unpack the tar archive, in the source directory run:

        runhaskell Setup.lhs configure
        runhaskell Setup.lhs build
        runhaskell Setup.lhs install

This last step requires `root` privileges.

If you don't have `root` privileges you can install [hs-bibutils]
locally with these commands:

        runhaskell Setup.lhs configure --user --prefix=$HOME
        runhaskell Setup.lhs build
        runhaskell Setup.lhs install --user

[hs-bibutils] should be compatible with cabal-install.

Documentation
-------------

The [Haddock] generated documentation is available here:

<http://code.haskell.org/hs-bibutils/docs/>

The original API documentation is available here:

<http://www.scripps.edu/~cdputnam/software/bibutils/library_specs.html>

Bug Reports
-----------

To submit bug reports you can use the [citeproc-hs] bug tracking
system available at the following address:

<http://code.google.com/p/citeproc-hs/issues>

Credits
-------

Thanks to [Chris Putnam] for his help.

Author
------

Andrea Rossato

`andrea.rossato at unitn.it`

Links to Related Projects
----------------

Bibutils
:    <https://sourceforge.net/p/bibutils/home/Bibutils/>

Pandoc
:    <http://pandoc.org/>

Citeproc-hs:
:    <http://code.haskell.org/citeproc-hs/>

CSL
:    <http://xbiblio.sourceforge.net/csl/>

Legal
-----

This software is released under the GNU GPL. See LICENSE for more
details.

This is an early, "alpha" release. It carries no warranties of any kind.

Copyright &copy; 2008 - 2010 Andrea Rossato

[hs-bibutils]: https://github.com/wilx/hs-bibutils
[bibutils]: https://sourceforge.net/p/bibutils/home/Bibutils/
[Hackage]: http://hackage.haskell.org/cgi-bin/hackage-scripts/package/hs-bibutils
[citeproc-hs]: http://code.haskell.org/citeproc-hs
[CSL]: http://citationstyles.org/
[pandoc]: http://pandoc.org/
[Zotero]: http://www.zotero.org
[MODS]: http://www.loc.gov/mods/
[Bruce D'Arcus]: http://community.muohio.edu/blogs/darcusb/
[John MacFarlane]: http://johnmacfarlane.net/
[Chris Putnam]: http://www.scripps.edu/~cdputnam/
[Haskell]:  http://www.haskell.org/
[Haddock]:  http://www.haskell.org/haddock/