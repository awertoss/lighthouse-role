Role lighthouse-role
=========

Role can install lighthouse and nginx, git.
Create nginx config.
Create lighthouse config.

Requirements
------------
Git, nginx. Если в системе нет этих сервисов, тогда роль установит их.

Role Variables
--------------

|Переменная|Описание| 
|-|--------|
Переменные для установки кредов default/main.yml:
|lighthouse_vcs|ссылка на репозиторий git lighthouse|

Dependencies
------------

Требуется роль clickhouse-role <br/>
[https://github.com/awertoss/clickhouse-role]

Example Playbook
----------------
```
hosts: lighthouse
roles:
  - role: lighthouse-role
```
License
-------

MIT

Author Information
------------------
Awertoss
