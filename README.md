Role Name
=========

This role is mostly here to test ansible and will get actions to set a server state the way I like it.

Requirements
------------

None

Role Variables
--------------

hosts -> expects a string to set in the hosts file example: "127.0.0.5 test1 \n 127.0.0.6 test2"

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - ansible-role-common

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
