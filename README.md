Ansible role: lighthouse
=========

This role installs lighthouse with web server nginx on the server.

Dependence
----------

Web server nginx latest version is installed from the OS repository


Role Variables
--------------

User variables are located in [defaults/main.yml](defaults/main.yml)

| Name | Default Value | Description |
|------|---------------|-------------|
| lighthouse_dir | /etc/lighthouse | Path to directory with lighthouse |
| lighthouse_port | 80 | Port for lighthouse |
| nginx_user_name | root | Username for nginx |


Templates
---------

Template for file configuration lighthouse is [templates/lighthouse.conf.j2](templates/lighthouse.conf.j2).
Template for file configuration nginx is [templates/nginx.conf.j2](templates/nginx.conf.j2).


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - lighthouse

License
-------

This project is licensed under MIT License.

Author Information
------------------

Kirill B.
