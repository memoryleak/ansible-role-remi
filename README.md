memoryleak.remi
===============

Install and enable remi repos

Requirements
------------

None

Role Variables
--------------
	remi_enable_repos:
	  - remi


Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: memoryleak.remi }

License
-------

MIT

Author Information
------------------

Haydar Ciftci <haydar.ciftci@gmail.com>
