Ansible Role for MariaDB Connector/J
====================================

[![Build Status](https://travis-ci.org/alvistack/ansible-role-mariadb-connector-java.svg?branch=master)](https://travis-ci.org/alvistack/ansible-role-mariadb-connector-java)
[![GitHub tag](https://img.shields.io/github/tag/alvistack/ansible-role-mariadb-connector-java.svg)](https://github.com/alvistack/ansible-role-mariadb-connector-java)
[![GitHub license](https://img.shields.io/github/license/alvistack/ansible-role-mariadb-connector-java.svg)](https://github.com/alvistack/ansible-role-mariadb-connector-java/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/galaxy-alvistack.mariadb--connector--java-blue.svg)](https://galaxy.ansible.com/alvistack/mariadb-connector-java)

Ansible Role for MariaDB Connector/J Installation.

Requirements
------------

This role require Ansible 2.4 or higher.

This role was designed for Ubuntu 16.04/14.04 and CentOS 7/6.

Role Variables
--------------

<table>
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th>parameter</th>
<th>required</th>
<th>default</th>
<th>choices</th>
<th>comments</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>mariadb_connector_java_dest</td>
<td>yes</td>
<td><code>/tmp/mariadb-connector-java.jar</code></td>
<td></td>
<td>Absolute path of where to download the file to</td>
</tr>
<tr class="even">
<td>mariadb_connector_java_group</td>
<td>yes</td>
<td><code>daemon</code></td>
<td></td>
<td>Name of the group that should own the file</td>
</tr>
<tr class="odd">
<td>mariadb_connector_java_mode</td>
<td>yes</td>
<td><code>0644</code></td>
<td></td>
<td>Mode the file should be</td>
</tr>
<tr class="even">
<td>mariadb_connector_java_owner</td>
<td>yes</td>
<td><code>daemon</code></td>
<td></td>
<td>Name of the user that should own the file</td>
</tr>
<tr class="odd">
<td>mariadb_connector_java_url</td>
<td>yes</td>
<td><code>ttps://downloads.mariadb.com/Connectors/java/connector-java-2.1.1/mariadb-java-client-2.1.1.jar</code></td>
<td></td>
<td>URL for download MariaDB Connector/J JAR</td>
</tr>
</tbody>
</table>

Dependencies
------------

No additional role dependencies.

Example Playbook
----------------

    - hosts: all
      roles:
        - role: mariadb-connector-java
          mariadb_connector_java_dest: "/opt/atlassian/jira/lib/mariadb-connector-java.jar"

License
-------

-   Code released under [Apache License 2.0](https://github.com/alvistack/ansible-role-mariadb-connector-java/blob/master/LICENSE)
-   Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

Author Information
------------------

-   Wong Hoi Sing Edison
    -   <https://twitter.com/hswong3i>
    -   <https://github.com/hswong3i>

