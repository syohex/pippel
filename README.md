Pippel
============

This package is an Emacs frontend for the Python package manager pip. As pippel also uses `tabulated-list-mode`, it provides a similiar package menu like `package-list-packages`.


## Usage

To use it call `M-x pippel-list-packages`.

Shortcuts for `pippel-package-menu-mode` buffers:

 * `m`     `pippel-menu-mark-unmark` remove mark
 * `d`     `pippel-menu-mark-delete` mark for deletion
 * `U`     `pippel-menu-mark-all-upgrades` mark all upgradable
 * `u`     `pippel-menu-mark-upgrade` mark for upgrade
 * `r`     `pippel-list-packages` refresh package list
 * `i`     `pippel-install-package` prompt user for packages
 * `x`     `pippel-menu-execute` perform marked package menu actions
 * `RET`   `pippel-menu-visit-homepage` follow link


## Installation

    (require 'pippel)
    (setq pippel-package-path "/path/to/pippel")

