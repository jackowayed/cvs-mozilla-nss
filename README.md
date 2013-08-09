Custom TLS Extensions in NSS
===================================

NSS is Mozilla's SSL (and more) library. Firefox and Chrome both use it.

In this repository, I am adding support for custom TLS Extensions, in support of [TACK](http://tack.io/) and similar initiatives.

The work is being done in `security/nss/lib/ssl/`.

This started with a cvs checkout and committing everything that resulted. git-cvsimport was causing trouble. All kinds of CVS garbage is committed, but the diffs from the starting point are what's important.