# Concept
what are we trying to achieve?

Well, Raster is going to be a desktop-environment (like KDE or GNOME) for unix-like systems.

## Global Concept
All details can be set individually for any window (e.g. all web-browser-windows might be set to non-transparent) or global (e.g. global main-color is set to red).

## Layout

By default there is a hidden panel at the top, which contains (osx-style) the window-menu for the current application.  This bar can be made visible by keyboard-shortcuts or by mouse.

There is a hidden text-only task-switcher at the left edge of the mein-screen, accessible by shortcuts.

##  Design

The default main-color will be cyan.

### Window Decoration

There wont be any bar on the top of any window. All window specific options and commands will accessible through keyboard- and mouse-shortcuts.

Windows borders will have a glowing effect in the main-color.

On every edge of any window will be straight “glowing” lines (coming and going to infinity) in the main-color. This lines are called guiding-lines.

All windows are transparent.

### Animations

Default animation for appearing or disappearing windows and dialogs will be a mix of fade-in and slide-in from one random side (orthogonal; either top, bottom, left or right). Guiding-lines appear before the window, so that the windows is “guided” by that lines (that’s where the name comes from).   
