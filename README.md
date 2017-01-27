hosts.d
=======

Parse and monitor files in `/etc/hosts.d` to configure `/etc/hosts`.

Should allow easier management of your hosts file and easy enabling / disabling
of some hosts.

install
-------

When you start using hosts.d initially install it. The installation will copy
your current `/etc/hosts` file into the hosts.conf that will be outputted first
in the now generated `/etc/hosts` file.

usage
-----

Run hosts.d this 'daemon' will watch the `/etc/hosts.d/` folder for changes and
apply those to the `/etc/hosts` file.

All 'hosts' that will be applied must end on `*.conf`, all other files will be
ignored. So it will be very easy to disable something.

