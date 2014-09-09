logrotate
=========

Ansible role for redis db (Ubuntu server).

Role Variables
--------------

    redis_password: 6Ja2E7T8TG
    redis_bind: 0.0.0.0

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: webbylab.redis
           redis_bind: 0.0.0.0
           redis_password: 6Ja2E7T8TG
           set_redis_password: 0

License
-------

MIT

Author Information
------------------

WebbyLab (http://webbylab.com)