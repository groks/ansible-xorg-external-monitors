xorg-external-monitors
========

An [ansible role](https://galaxy.ansibleworks.com/list#/roles/214) which enables
additional monitor resolution choices.

Some monitors do not communicate their resolution when plugged into a laptop VGA
port, for example. There is a graphical interface for configuring this, but the
options are too conservative and don't offer 1920x1080 (Full HD).

This role does not set a specific resolution for any external monitor, it adds
extra configuration options to the configuration interface. Select a resolution
via the GUI and it will be remembered the next time you plug it in; no need to
hack on the `xorg.conf` file.

    ---
    - hosts: localhost

      roles:
        - groks.xorg-external-monitors

Requirements
------------

An installation of [Fedora](https://fedoraproject.org/get-fedora) Linux.

Role Variables
--------------

None.

Dependencies
------------

None.

License
-------

BSD
