isset.docker-compose [![pipeline status](https://gitlab.isset.nl/operations/isset.docker-compose/badges/master/pipeline.svg)](https://gitlab.isset.nl/operations/isset.docker-compose/commits/master)
=========

_Installs docker-compose._

Requirements
------------

Ansible 2.5 or above is highly recommended.

Role Variables
--------------

    isset_docker_compose_state: present
    isset_docker_compose_path: /usr/local/bin/docker-compose
    isset_docker_compose_version: 1.23.2
    isset_docker_compose_url: "https://github.com/docker/compose/releases/download/{{ isset_docker_compose_version }}/docker-compose"

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
