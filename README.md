# arpak
[NOTE] This repo is not where mainline arpak is hosted. If you'd like, you may goto https://github.com/archimaxlinux/arpak/ for upstream source.
Arpak - A package manager for Arch Linux based distros with APT-like syntax!

Basic features:
- install: install/upgrade a package
- localinstall: install a local package
- remove: remove a package
- search: search for a package
- update: update all repos
- list: list all installed packages
- upgrade: upgrade all packages that can be upgraded

Compiling:
To compile arpak, you must use pyinstaller. To get started, run the following command:
``pip install pyinstaller``

From there on, run this from the arpak source directory:
``pyinstaller --onefile arpak.py``

Then, you can look in dist/ to see arpak. It is recommended to move arpak into /usr/bin for ease of access.

