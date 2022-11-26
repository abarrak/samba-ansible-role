Samba Server Role
=================

This role contains the setup for minimal Samba server, translated from [this article](https://www.redhat.com/sysadmin/getting-started-samba).

Requirements
------------

CentOS/RHEL based Linux.

Role Variables
--------------

The default variables are defined in `defaults/main.yml`, and should be overriden as convenient

Example Playbook
----------------

Install the role:

    ansible-galaxy install abarrak.samba

Include it to run the setup tasks:

    - hosts: samba-server
      import_role:
        name: abarrak.samba

License
-------

MIT.

Author
------

Abdullah Barrak (@abarrak).
