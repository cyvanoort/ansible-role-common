ansible-role-common
=========

This role is mostly here to test ansible and will get actions to set a server state the way I like it.

Requirements
------------

None

Role Variables
--------------

Hosts (Required)
hosts: 
  - { ip: '127.0.0.5', hostname: 'example1' }
  - { ip: '127.0.0.6', hostname: 'example2' }

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - common

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
