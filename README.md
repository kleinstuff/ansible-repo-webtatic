[![Build Status](https://travis-ci.org/kleinstuff/ansible-zabbix-agent.png)](https://travis-ci.org/kleinstuff/ansible-zabbix-agent)

kleinstuff.repo-webtatic
=========

Install Webtatic PHP Repository for RHEL/CentOS
Currently supports:
* CentOS/RHEL 7

Requirements
------------

No extra requirements needed.

Role Variables
--------------

Only the repository URL is needed, but is already set on defaults/main.yml


Dependencies
------------

No deps.

Example Playbook
----------------

```
    - hosts: servers
      roles:
         - { role: kleinstuff.repo-webtatic }
```
License
-------

GPL

Author Information
------------------

If you want to suggest changes or request new features, please feel free to create a issue or send a pull request.
