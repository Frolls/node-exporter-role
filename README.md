Node-exporter-role
====================

Устанавливает, настраивает и запускает node_exporter

Requirements
------------

Отсутствуют

Role Variables
--------------

Смотри `defaults/main.yml`

Dependencies
------------

None

Example Playbook
----------------

```yml
- name: Install Node Exporter
  hosts: all
  roles:
    - role: node-exporter-role
```

License
-------

BSD

Author Information
------------------

Frolls
