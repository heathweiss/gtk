# gtk

A test project to make sure I can build gtk bindings in a fresh ubunut install.

Added gi-gtk ==3.0.* to dependencies

$ stack build
fails on building haskell-gi. As per haskell-gi README.md:
$ sudo apt-get install libgirepository1.0-dev libwebkit2gtk-4.0-dev libgtksourceview-3.0-dev
-installed good.

$ stack build
Does a ton of building for haskell-gi and gi-gtk
-build was good


added - gi-gtk-hs to dependencies
$ stack build
-Did a small build. Build was good.