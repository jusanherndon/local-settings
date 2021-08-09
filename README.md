local-settings
=========

This role sets up the local settings for the machine like timezone and local text settings

Requirements
------------


Role Variables
--------------

timezone: Your loccal timezone as defined in timedatectl

Dependencies
------------


Example Playbook
----------------

    - hosts: servers
      roles:
         - jusanherndon.local_settings

License
-------

BSD

Author Information
------------------

