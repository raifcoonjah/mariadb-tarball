Ansible Role: MariaDB Tarball
=========

An Ansible role that installs MariaDB Tarball, version 10.4.32

Requirements
------------

No specific requirements. 

Role Variables
--------------

Default Variables are listed below: 

```shell
# MariaDB URL
mariadb_url: "https://mirror.23m.com/mariadb/mariadb-10.4.32/bintar-linux-systemd-x86_64/mariadb-10.4.32-linux-systemd-x86_64.tar.gz"
mysql_path: /home/mysql
mycnf_path: /etc/mysql
mariadb: 'mariadb-10.4.32-linux-systemd-x86_64.tar.gz'
mariadb_path: 'mariadb-10.4.32-linux-systemd-x86_64'
```

Dependencies
------------

No special dependecies required

Example Playbook
----------------

Role can be run using the play.yml playbook:

```shell
---
- name: Install MariaDB tarball
  hosts: localhost
  
  roles:
  - mariadb-tarball
```

License
-------

MIT

Author Information
------------------

This role was created in 2023 by Raif Coonjah and was reviews by Yash for the ansible training.
