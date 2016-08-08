nginx_source
=========

Installs NGINX from source based on version.  Based on "tobybro/ansible-nginx-source" Ansible Galaxy role.

Requirements
------------

None.

Role Variables
--------------

"nginx_src_dir" - Directory to use for building NGINX.
"nginx_version" - Version to install.
"nginx_prefix" - Install location of NGINX.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: michaelbruton.nginx-source, nginx_src_dir: "/tmp/nginx" , nginx_version: 1.10.1, nginx_prefix: "/usr/local/nginx" }

License
-------

BSD

Author Information
------------------

This role was created in 2016 by Michael Bruton (michaelbruton.com).
