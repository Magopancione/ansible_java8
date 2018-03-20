Role Name
=========

Installs Oracle Java8

Requirements
------------

None

Role Variables
--------------

```
---
# defaults file for ansible-oracle-java8
jdk8:
  id: 'EEA14886'
  keyserver: 'hkp://keyserver.ubuntu.com:80'
  repo: 'deb http://ppa.launchpad.net/webupd8team/java/ubuntu xenial main'
```

Dependencies
------------

None

Example Playbook
----------------

```
---
- hosts: all
  become: true
  vars:
  roles:
    - role: jdk8
  tasks:
```

License
-------

BSD

Author Information
------------------

Larry Smith Jr.
- @mrlesmithjr
- http://everythingshouldbevirtual.com
- mrlesmithjr [at] gmail.com
