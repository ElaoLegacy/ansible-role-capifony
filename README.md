Ansible Role - Capifony
=======================

A capifony role to install capifony on elao symfony standard vagrant box

Requirements
------------

This role only run on elao symfony standard vagrant box. See https://vagrantcloud.com/elao/symfony-standard-debian

Role Variables
--------------

* version: (optionnal) Capifony version

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: elao.capifony }

License
-------

MIT

Author Information
------------------

http://www.elao.com/
