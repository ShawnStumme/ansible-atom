Atom
=========

An Ansible role to install the [Atom](https://www.atom.io) editor for Ubuntu using the apt package manager.

Requirements
------------

Ansible >= 2.5

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: atom
           become: yes

License
-------

MIT

Author Information
------------------

This role was created by Shawn Stumme as a derivative of [ansible-role-atom](https://github.com/TonyApuzzo/ansible-role-atom) by Tony Apuzzo.
