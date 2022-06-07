Routing Instances Configuration
=========

Configure Routing Instances for Junos.

Requirements
------------


Role Variables
--------------
routing_instances: List of Dictionaries containing Routing Instances

routing_instances_settings: Dictionary containing settings for Routing Instances


Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: junos_routing_instances_config }

License
-------

BSD

Author Information
------------------

Marc Colburn Juniper
