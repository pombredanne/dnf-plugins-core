===================
DNF builddep Plugin
===================

Install whatever is needed to build the given .src.rpm, .nosrc.rpm or .spec file.

--------
Synopsis
--------

``dnf builddep <file>...``

---------
Arguments
---------

``<file>``
    The path to .src.rpm, .nosrc.rpm or .spec file, to read the needed build requirements from.

--------
Examples
--------

``dnf builddep foobar.spec``
    Install the needed build requirements, defined in the foobar.spec file.

``dnf builddep foobar-1.0-1.src.rpm``
    Install the needed build requirements, defined in the foobar-1.0-1.src.rpm file.
