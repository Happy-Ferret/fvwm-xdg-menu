fvwm-xdg-menu
=============

This is an xdg-menu for use with fvwm and fvwm-menu-desktop.

The goal is to have an application menu in fvwm that support
the additional FreeDesktop categories out-of-the box, that
on any GNU/Linux distribution.

For now, the files will be provided without any installation
procedure. To copy them in the correct XDG locations must be
enough to make the menu to work fine.

When done, a patch for inclusion into fvwm will be done.

DONE:
 - The main skeleton of the menu.
 - Some addtional categories are included with a mechanism to
    include them into the menu. If a desktop file contain 2
    main categories and 1 additional category, the program
    will appear 2 times.
 - The additional categories until StrategyGame.
   See http://standards.freedestop.org/menu-spec/latest/apas02.html for the list.

TODO to reach the holly goal:
 - Add the remaining additional categories.

Don't make a symlink from fvwm-applications.menu to applications.menu
in /etc/xdg/menus. This doesn't arm fvwm, but can make silly bugs like
kbuildsycoca4 running forever at 100 % cpu.


This work is copyrighted under the GPL v.2, look at the LICENSE file for details.

Enjoy,
Dominique Michel