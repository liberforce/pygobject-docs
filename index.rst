==================
What is PyGObject?
==================

.. title:: Overview

.. toctree::
    :hidden:

    getting_started
    api
    faq
    testing
    porting
    basic_types
    examples
    gobject
    memory_leaks
    devguide
    contact


**PyGObject** are Python bindings for gobject based libraries such as GTK+,
GStreamer, WebKitGTK+, glib, gio and many more.

If you want to write a Python application for GNOME or a Python GUI
application using GTK+, then PyGObject is the way to go.


How does it work?
-----------------

.. image:: images/overview.svg

PyGObject uses glib, gobject, girepository, ffi and other libraries to access
the C library (libgtk-3.so) and the additional metadata from the accompanying
typelib file (Gtk-3.0.typelib) and dynamicly provides a Python interface based
on that information.


Who Is Using PyGObject?
-----------------------

* `D-Feet <https://wiki.gnome.org/action/show/Apps/DFeet>`__ - an easy to use D-Bus debugger
* `GNOME Music <https://wiki.gnome.org/Apps/Music>`__ - a music player for GNOME
* `GNOME Tweak Tool <https://wiki.gnome.org/action/show/Apps/GnomeTweakTool>`__ - a tool to customize advanced GNOME 3 options
* `Gramps <https://gramps-project.org/>`__ - a genealogy program
* `Lollypop <https://gnumdk.github.io/lollypop-web/>`__ - a modern music player
* `Meld <http://meldmerge.org/>`__ - a visual diff and merge tool
* `MyPaint <http://mypaint.org/>`__ - a nimble, distraction-free, and easy tool for digital painters
* `Orca <https://wiki.gnome.org/Projects/Orca>`__ - a flexible and extensible screen reader
* `Pithos <https://pithos.github.io/>`__ - a Pandora Radio client
* `Pitivi <http://www.pitivi.org/>`__ - a free and open source video editor
* `Quod Libet <https://quodlibet.readthedocs.io/>`__ - a music library manager / player
* `Transmageddon <http://www.linuxrising.org/>`__ - a video transcoder


The following applications or libraries use PyGObject for optional features,
such as plugins or as optional backends:

* `beets <http://beets.io/>`__ - a music library manager and MusicBrainz tagger
* `gedit <https://wiki.gnome.org/Apps/Gedit>`_- a GNOME text editor
* `matplotlib <http://matplotlib.org/>`__ - a python 2D plotting library
* `Totem <https://wiki.gnome.org/Apps/Videos>`__ - a video player for GNOME



.. ::

    TODO:

    GObject
    Properties
    Signals
    VFuncs
    Interfaces
    Threading
    String handling
    Path handling