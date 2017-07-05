Role Name
=========

Deploys MongoDB

The role is for installing from the official MongoDB apt repositories on Ubuntu
machines.

Requirements
------------

N/A

Role Variables
--------------

    mongodb_version: '3.4.5'

Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: servers
      roles:
         - bigjust.mongodb

License
-------

GPLv3

Author Information
------------------

Justin Caratzas <bigjust@lambdaphil.es>
