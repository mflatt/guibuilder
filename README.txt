The "guibuilder" package is a DrRacket plug-in that adds an "Insert
GUI" item to DrRacket's "Insert" menu, and a "Show GUI Toolbar" item
to DrRacket's "View" menu. Using those menu items, a programmer can
drop a GUI template into any definition context (in an otherwise
textual program) and grpahically configure basic properties of the
GUI.

A graphical GUI element expands to a set of definitions that generate
a GUI of the same shape as created in the editor, assuming that
`racket/gui/base` and `racket/class` are imported (or the program is
written in `#lang racket/gui`). The definitions bind elements of the
GUI as Racket objects, which can be manipulated through all the usual
methods of the `racket\gui\base` classes.
