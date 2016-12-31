Role Name
=========

This role installs a hibiscus payment service on linux server. 

Requirements
------------

You need to have a running database 

Role Variables
--------------

please see defaults/main.yml

Dependencies
------------

none

Example Playbook
----------------

Simple use goes as follow:

    - hosts: hibiscus 
      roles:
         - { role: verges.hibiscus }

License
-------

BSD

Author Information
------------------

Martin Verges
