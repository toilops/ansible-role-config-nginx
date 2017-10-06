Ansible Role Config Nginx
=========
[![Build Status](https://travis-ci.org/toilops/ansible-role-config-nginx.svg?branch=master)](https://travis-ci.org/toilops/ansible-role-config-nginx)

Role to install and configure nginx

Requirements
------------

Currently this role only supports Redhat systems. (EL - 6,7)

Role Variables
--------------

None at this time

Dependencies
------------

Role: toilops.config-epel-repo

Example Playbook
----------------

Including an example of how to include the toilops.config-nginx role.

    - hosts: servers
      tasks:
        - include_role:
            name: toilops.config-nginx
          vars:
            x: 42

License
-------

MIT

Author Information
------------------

Find me on github [@BondAnthony](https://github.com/BondAnthony)
