ansible-ansible
===============

[![Build Status](https://travis-ci.org/wrboyce/ansible-ansible.png)](https://travis-ci.org/wrboyce/ansible-ansible)

Bootstrap ansible on Debian/Ubuntu based systems.

Role Variables
--------------

`ansible_deploy_key` holds the authorized ssh key for the ansible user.

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: wrboyce.ansible
           ansible_deploy_key: "ssh-rsa ... user@host"

License
-------

BSD

Author Information
------------------

* Will Boyce
