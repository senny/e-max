e-max
=====

e-max is now known as cabbage => https://github.com/senny/cabbage

### Upgrading

For upgrading from e-max to cabbage you need to reinstall it.
The install script will move your `~/.emacs.d` with your configuration
to a backup location.
Therefore you need to reconfigure your emacs in `~/.emacs.d`.

Steps:

  1. Run the install script:

         $ /usr/bin/env bash -c "$(curl -fsSL https://raw.github.com/senny/cabbage/master/scripts/install.sh)"

     It renames your current configuration folder (``~/.emacs.d/``) to
     a backup name (e.g. ``~/.emacs.d.old-20120826-195820``).

  2. Copy the important settings from your ``~/.emacs.d.old-*`` to the
     new ``~/.emacs.d``. The structure has changed and all the
     settings and functions were renamed from `.*e-max.*` to `.*cabbage.*`.

### Mailing list

Join us in the [cabbage google group](https://groups.google.com/forum/#!forum/emacs-cabbage).
Write to the group if you experience problems while upgrading!
