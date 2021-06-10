ansible-rabbitmq-role
=========

Support for rabbitmq management for Debian

Requirements
------------

None

Role Variables
--------------
```YAML
##
# RabbitMQ server configuration
##
rabbitmq_enabled: false
rabbitmq_version: 5.7


```
Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: methorz.rabbitmq }

License
-------

BSD

Author Information
------------------

https://twitter.com/methor_z
