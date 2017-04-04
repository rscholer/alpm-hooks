alpm-hooks
==========
A collection of alpm hooks.

Available hooks
---------------
*   **mirrorlist.hook**:
    Update pacman's mirrorlist with reflector.
    Make sure to add `/etc/pacman.d/mirrorlist` to NoExtract in pacman.conf.
*   **mkinitcpio.hook**:
    Update initcpio images if systemd or a video driver is updated.
*   **paccache-old.hook**:
    Remove old packages from cache.
*   **paccache-uninstalled.hook**:
    Remove uninstalled packages from cache.
