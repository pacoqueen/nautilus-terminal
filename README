==============================================================================
=    Nautilus Terminal - A terminal embedded in the Nautilus file browser    =
==============================================================================

Nautilus Terminal is a terminal embedded in Nautilus, the GNOME's file
browser. It is always open in the current folder, and follows the navigation
(the "cd" command is automatically executed when you move to an other folder).
Nautilus Terminal have a lot of functionalities:

    * It always follows your navigation in your folders.
    * It supports Copy/Paste (Ctrl+Shift+C / *Ctrl+Shift+V).
    * It supports drag & drop of files and folders.
    * It can be hidden/shown when you want (with the F4 key).
    * It is resizeable.

WEB SITE: http://projects.flogisoft.com/nautilus-terminal/


Dependencies:
-------------

    * Python (>= 2.6) <http://python.org/>
    * GObject Introspection <http://live.gnome.org/GObjectIntrospection>
    * VTE <http://live.gnome.org/VTE>
    * Nautilus (>= 3.0) <http://live.gnome.org/Nautilus>
    * Nautilus Python (>= 1.0) <http://projects.gnome.org/nautilus-python/>
    * PyXDG (optional) <http://www.freedesktop.org/wiki/Software/pyxdg>


Local install:
--------------

Just create ~/.local/share/nautilus-python/extensions and copy (or link) src/nautilus-terminal.py there.

Get sure you have python-nautilus installed (sudo apt-get install python-nautilus) and restart nautilus with `nautilus -q && nautilus`.


Notes:
------

Since `fork_command_full` is deprecated on latest versions of VTE, nautilus-terminal v1.1 only works with VTE >= 0.28 (in Debian's versioning numbers). I think is 0.39 in its owns VTE (Gnome's) versioning.

All references to `fork_command_full` changed to use `spawn_sync` in systems with older VTE versions (i. e. Ubuntu 14.04).

Forked from https://launchpad.net/nautilus-terminal since it does not seems have development activity since 2011 or so.

