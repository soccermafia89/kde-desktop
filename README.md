Role Name
=========

Installs KDE desktop.  Expects to be run within a chroot environment.

Requirements
------------

None

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

```
- name: Mount Chroot
  hosts: localhost
  connection: chroot
  roles:
   - kde-desktop
```

License
-------

BSD

Author Information
------------------

Alex Ethier, the Mitre Corporation.
