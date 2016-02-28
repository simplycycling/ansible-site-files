Ansible Role for Timezone
=========================

[![Build Status](https://travis-ci.org/pantarei/ansible-role-tzdata.svg?branch=master)](https://travis-ci.org/pantarei/ansible-role-tzdata)
[![GitHub tag](https://img.shields.io/github/tag/pantarei/ansible-role-tzdata.svg)](https://github.com/pantarei/ansible-role-tzdata)
[![GitHub license](https://img.shields.io/github/license/pantarei/ansible-role-tzdata.svg)](https://github.com/pantarei/ansible-role-tzdata/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/ansible/role/6087.svg)](https://galaxy.ansible.com/detail#/role/6087)

Ansible Role for Timezone Management.

Requirements
------------

This role require Ansible 2.0 or higher.

This role was designed for Ubuntu Server 14.04 LTS.

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
<th align="left">parameter</th>
<th align="left">required</th>
<th align="left">default</th>
<th align="left">choices</th>
<th align="left">comments</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">tzdata_timezone</td>
<td align="left">yes</td>
<td align="left">Etc/UTC</td>
<td align="left"></td>
<td align="left">Time zone in the <a href="https://en.wikipedia.org/wiki/Tz_database">tz database</a>, see <a href="https://en.wikipedia.org/wiki/List_of_tz_database_time_zones">list of time zones</a> for more information.</td>
</tr>
</tbody>
</table>

Dependencies
------------

No additional role dependencies.

Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: hswong3i.tzdata, tzdata_timezone: 'Asia/Hong_Kong' }

License
-------

-   Code released under [MIT](https://github.com/pantarei/ansible-role-tzdata/blob/master/LICENSE)
-   Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

Author Information
------------------

-   Wong Hoi Sing Edison
    -   <https://twitter.com/hswong3i>
    -   <https://github.com/hswong3i>

