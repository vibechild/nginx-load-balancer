nginx Load Balancer Role
=========

A generic software load balancer configuration using nginx

Requirements
------------

This role is intended to be included in a project with the specific variables and config files provided. This repository is the generic configuration which will be the same regardless of the specific configuration of the instances.  In other words the requirement of this repository is that it be used as a requirement in another repository.

Role Variables
--------------

Both the software and configfiles variables are optional

Dependencies
------------

This role does not require any other roles.

Example Playbook
----------------

Just call the role.  All variables are optional:

    - hosts: servers
      roles:
         - { role: nginx-load-balancer, x: 42 }


Author Information
------------------

* **Devin** - *Initial work* - [Other Projects](https://github.com/vibechild)
