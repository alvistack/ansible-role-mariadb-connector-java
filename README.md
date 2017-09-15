Ansible Role for MariaDB Connector/J
==========================

[![Build Status](https://travis-ci.org/alvistack/ansible-role-mariadb-connector-java.svg?branch=master)](https://travis-ci.org/alvistack/ansible-role-mariadb-connector-java)
[![GitHub tag](https://img.shields.io/github/tag/alvistack/ansible-role-mariadb-connector-java.svg)](https://github.com/alvistack/ansible-role-mariadb-connector-java)
[![GitHub license](https://img.shields.io/github/license/alvistack/ansible-role-mariadb-connector-java.svg)](https://github.com/alvistack/ansible-role-mariadb-connector-java/blob/master/LICENSE)

 Ansible Role for MariaDB Connector/J Installation.

Requirements
------------

This role require Ansible 2.3 or higher.

This role was designed for Ubuntu 16.04/14.04 and CentOS 7/6.

Role Variables
--------------

No additional role variables.

Dependencies
------------

No additional role dependencies.

Example Playbook
----------------

    - hosts: all
      roles:
        - role: mariadb-connector-java
          mariadb_connector_java_dest: "/tmp"

License
-------

-   Code released under [Apache License 2.0](https://github.com/alvistack/ansible-role-mariadb-connector-java/blob/master/LICENSE)
-   Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

Author Information
------------------

-   Wong Hoi Sing Edison
    -   <https://twitter.com/hswong3i>
    -   <https://github.com/hswong3i>

