Samba Server Role
=================

[![Release](https://github.com/abarrak/samba-ansible-role/actions/workflows/release.yml/badge.svg)](https://github.com/abarrak/samba-ansible-role/actions/workflows/release.yml)

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

    ansible-galaxy install abarrak.samba_ansible_role

Include it to run the setup tasks:

    - hosts: samba-server
      import_role:
        name: abarrak.samba_ansible_role

License
-------

MIT.

Author
------

Abdullah Barrak (@abarrak).
