shirk/homebrew-bochs
====================
This is a brew tap for my modified [bochs](http://bochs.sourceforge.net) formulae.
It's now on GitHub since bochs was removed from the main [homebrew](http://brew.sh) formulae some time ago.

How do I install this?
----------------------
It's as simple as `brew tap shirk/homebrew-bochs` and then `brew install bochs`.

Formula notes
-------------
This version of the bochs formulae has some additional options:

* --with-smp - enable SMP support in Bochs (default was to not have SMP at all)
* --with-x11 - enable the dependency on X11 and the X11 GUI
* --with-gtk+ - enable the GTK+ GUI (depends on X11)
* --with-sdl - enable the SDL GUI (can be used with --without-x11 to build a native SDL-only GUI)

