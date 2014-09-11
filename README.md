Redis
=========

Ansible role for redis db (Ubuntu server).

Role Variables
--------------

    redis_password: ''
    redis_bind: 127.0.0.1
    redis_password_present: 0

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: webbylab.redis
           redis_bind: 0.0.0.0
           redis_password: password
           redis_password_present: 1

License
-------

MIT

Author Information
------------------

WebbyLab (http://webbylab.com)
