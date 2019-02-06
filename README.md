isset.docker-compose [![pipeline status](https://gitlab.isset.nl/operations/isset.docker-compose/badges/master/pipeline.svg)](https://gitlab.isset.nl/operations/isset.docker-compose/commits/master)
=========

_Installs docker-compose and installs a optimized profile for root._

Requirements
------------

Ansible 2.5 or above is highly recommended.

Role Variables
--------------

	n/a

Dependencies
------------

    n/a

Example Playbook
----------------

    - hosts: all
      become: yes
      roles:
        - role: isset.docker-compose

License
-------

MIT

Author Information
------------------

Gerben Geijteman <gerben@isset.nl>
