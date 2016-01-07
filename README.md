PHP
=========

Easy php configuration for ubuntu

Requirements
------------

none

Role Variables
--------------

1. `php_packages`: list of php packages to instal, by default : ["php5-cli","php5-gd","php5-mysql"]
1. `pecl_packages`: list of pecl packages to instal
1.  `timezone` : timezone configuration, by default : UTC

Dependencies
------------

none

Example Playbook
----------------

    - hosts: servers
      roles:
         - virhi.php

License
-------

MIT

Author Information
------------------

http://github.com/virhi
