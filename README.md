xorg-external-monitors
========

An [ansible role](https://galaxy.ansibleworks.com/) which enables additional
monitor reolution choices.

Some monitors do not communicate their resolution when plugged into a laptop VGA
port, for example. There is a graphical interface for configuring this, but the
options are too conservative, not offering for example 1920x1080 (Full HD).

This role does not set a specific resolution for any external monitor, it adds
extra configuration options to the configuration interface. Once you select
a resolution, it should be remembered for the future; no need to hack on the
`xorg.conf` file.

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
