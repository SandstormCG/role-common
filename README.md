Common
=========

Ansible galaxy role for common apps & configs

Role Variables
--------------

* zt_network --> zerotier network id.
* st_device --> Variable with nested values for adding syncthing device. Example:
    `st_device:
      sid: syncthing_device_id
      name: device_name`
* user --> Username for the installation user
* group --> Group name for the user
* ansible_host --> host name of pc in which the playbook is post installing
* syncthing_mountdep --> syncthing unit for device in systemd. To get unit list (archwiki)[https://wiki.archlinux.org/title/syncthing] (**User service: on mount**) `systemctl list-units -t mount` 


License
-------

Yet to be determined

Author Information
------------------

[Sandstorm](https://github.com/SandstormCG)
