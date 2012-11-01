# Web Haskell packages repository for Arch Linux

The `[habs-web]` repository is a set of [Arch Linux][arch] packages mainly
focused on Haskell Web Frameworks. It includes [Happstack][happs], [Snap][snap]
, [Yesod][yesod] and [Hakyll][hakyll], and all the needed dependencies
(including database backends).

These are [cblrepo](http://hackage.haskell.org/package/cblrepo) files to build
the repository.

If you want to check and build this, you'll need
[cblrepo](http://hackage.haskell.org/package/cblrepo) and *Cabal Install*. If
you are looking for the actual repo add this to your `/etc/pacman.conf`
**before** `[Extra]`:

~~~~~ { .bash }

[haskell]
Server = http://xsounds.org/~haskell/$arch

[haskell-web]
Server = http://archhaskell.mynerdside.com/$repo/$arch

~~~~~

Please note that this is a temporary repository. Hopefully it will be merged with the main one.

[arch]: http://www.archlinux.org
[happs]: http://www.happstack.com
[snap]: http://snapframework.com
[yesod]: http://www.yesodweb.com
[hakyll]: http://jaspervdj.be/hakyll
