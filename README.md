ansible-mongodb-docker
=========

Ansible role for install MongoDB in docker

Requirements
------------

Ubuntu 18.04 as host.

Role Variables
--------------

- `mongodb_docker_tag` - MongoDB tag
- `mongodb_docker_container_name` - name of docker container
- `mongodb_docker_volume_data` - name of docker volume
- `mongodb_docker_network` - name of docker network
- `mongodb_docker_root_username` - Root username
- `mongodb_docker_root_password` - Password for root user
- `mongodb_docker_memory` - memory limit
- `mongodb_docker_port` - port for mapping


Example Playbook
----------------


    - hosts: db
      roles:
         - { role: kirill_zak.ansible-mongodb-docker }

License
-------

MIT