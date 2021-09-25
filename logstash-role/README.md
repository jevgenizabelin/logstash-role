Logstash role
=========

Роль для установки logstash на хостах с ОС: Debian, Ubuntu, CentOS, RHEL.

Requirements
------------

Поддерживаются только ОС семейств debian и RHEL.

Role Variables
--------------

| Variable name | Default | Description |
|-----------------------|----------|-------------------------|
| logstash_version | "7.14.1" | Параметр, который определяет какой версии logstash будет установлен |


Example Playbook
----------------

    - hosts: all
      roles:
         - logstash_role

License
-------

MIT

Author Information
------------------

JZ:ee.jzabelin@gmail.com
