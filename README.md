Ansible module used by OSAS to enable mariadb (or MySQL if too old)

[![Build Status](https://travis-ci.org/OSAS/ansible-role-mariadb.svg?branch=master)](https://travis-ci.org/OSAS/ansible-role-mariadb)


## Variables

- **rdbms_root_pw**: a database root password is automatically generated, but you can use this variable to set it to a fixed value
- **rdbms_backup**: enable regular database backup in /var/backups/mariadb/ (default is True)

