[![Build Status](https://travis-ci.org/wtanaka/ansible-role-mysql.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-mysql)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-mysql.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-mysql)

wtanaka.mysql
=============

Installs mysql server

Example Playbook
----------------

    - hosts: servers
      roles:
         - wtanaka.mysql

### `mysql_should_shortcircuit`

Default: True

When True, this role short-circuits itself if it detects that it is
alrady installed.  Currently, this just looks for a `mysql` in the
path, this might be improved in the future to look for a server
binary.

### All variables

The full set of configuration options available are visible in
[defaults/main.yml](defaults/main.yml)

License
-------

GPLv2

Author Information
------------------

https://wtanaka.com/
