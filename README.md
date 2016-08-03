ansible-role-debianUtils
=========
[![Travis](https://img.shields.io/travis/louwandre90/ansible-role-debianUtils.svg?style=flat-square)](https://travis-ci.org/louwandre90/ansible-role-debianUtils)
[![Ansible Role](https://img.shields.io/badge/role-louwandre90.debianUtils-blue.svg?style=flat-square)](https://galaxy.ansible.com/louwandre90/debianUtils/)

This role installs the following packages for Debian:
- Samba Server
- Adobe Flash

Installation is done via apt and some basic configuration is done after installation. 

Requirements
------------

None

Role Variables
--------------

The following defaults are set:

    username: jarvis

To pass different variables:

    ansible-playbook playbook.yml -e 'username=myuser'
    
Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: louwandre90.debianUtils }

License
-------

BSD

Author Information
------------------

This role was created in 2016 by Andre Louw.
