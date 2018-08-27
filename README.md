alpm-hooks
==========
A collection of alpm hooks.

All scripts and hooks are tested under [Arch Linux][1] and [Arch Linux 32][2].

Please [let me know][3], if and what changes are needed to support current
Arch Linux packages.

Available hooks
---------------
*   **linux.hook**, **linux-lts.hook**:
    Update initcpio images if kernel, systemd, firmware or drivers are updated.
*   **paccache-old.hook**:
    Remove old packages from cache.
*   **paccache-uninstalled.hook**:
    Remove uninstalled packages from cache.

Installation
------------
1. Create `/etc/pacman.d/hooks` if it does not exists yet.
2. Copy desired hooks and associated scripts into the directory.

License
-------
[MIT License][4]


[1]: https://www.archlinux.org/
[2]: https://www.archlinux32.org/
[3]: https://github.com/rscholer/alpm-hooks/issues
[4]: LICENSE
