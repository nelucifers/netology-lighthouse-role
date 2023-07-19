Ansible role: lighthouse
=========

This role installs lighthouse on the server.


Role Variables
--------------

User variables are located in (defaults/main.yml[defaults/main.yml])

| Name | Default Value | Description |
|------|---------------|-------------|
| lighthouse_dir | /etc/lighthouse | Path to directory with lighthouse |
| lighthouse_port | 80 | Port for lighthouse |
| nginx_user_name | root | Username for nginx |


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
