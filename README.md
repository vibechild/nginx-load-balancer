nginx Load Balancer Role
=========

A generic software load balancer configuration using nginx

Requirements
------------

This role is intended to be included in a project with the specific variables and config files provided. This repository is the generic configuration which will be the same regardless of the specific configuration of the instances.  In other words the requirement of this repository is that it be used as a requirement in another repository.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

This role does not require any other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }


Author Information
------------------

* **Devin** - *Initial work* - [Other Projects](https://github.com/vibechild)
