Redis
=========

Ansible role for redis db (Ubuntu server).

Role Variables
--------------

    redis_password: password
    redis_bind: 127.0.0.1
    set_redis_password: 0

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: webbylab.redis
           redis_bind: 0.0.0.0
           redis_password: password
           set_redis_password: 0

License
-------

MIT

Author Information
------------------

WebbyLab (http://webbylab.com)
