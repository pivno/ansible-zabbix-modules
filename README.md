# Ansible modules for managing Zabbix

This repository contains modules for managing [Zabbix](https://www.zabbix.com). There are plans to bring these modules into [Ansible](https://www.ansible.com).

These modules are already shipped with Ansible:

- [zabbix_group](https://docs.ansible.com/ansible/zabbix_group_module.html) - Zabbix host groups creates/deletes
- [zabbix_host](https://docs.ansible.com/ansible/zabbix_host_module.html) - Zabbix host creates/updates/deletes
- [zabbix_hostmacro](https://docs.ansible.com/ansible/zabbix_hostmacro_module.html) - Zabbix host macro creates/updates/deletes
- [zabbix_maintenance](https://docs.ansible.com/ansible/zabbix_hostmacro_module.html) - Create Zabbix maintenance windows
- [zabbix_screen](https://docs.ansible.com/ansible/zabbix_screen_module.html) - Zabbix screen creates/updates/deletes
 
These modules are pending review:

- [zabbix_link_template](https://github.com/ansible/ansible-modules-extras/pull/3223) - This module allows to link hosts with templates in Zabbix (1.8 - 3.0 version)
- [zabbix_webscenario](https://github.com/ansible/ansible-modules-extras/pull/3215) - This module provides support for create/delete/update zabbix webscenario`

So far, following modules have been developed:

- none yet

# Dependencies
- [zabbix-api](https://pypi.python.org/pypi/zabbix-api)
- Zabbix 3.0 LTS

# How to install
Download desired modules and place it under library/ directory in your playbook  directory.

# Future development and desired modules
We plan to develop more modules. The list of following modules, which we will be working on in the near future:

- zabbix_user_group - Manage Zabbix user groups
- zabbix_media_type - Manage Zabbix media types
- zabbix_user - Manage Zabbix user
- zabbix_user_media - Manage Zabbix user’s media in Zabbix
- zabbix_discovery_rule - Manage Zabbix discovery rules
- zabbix_template - Manage Zabbix templates
- zabbix_proxy - Manage Zabbix proxies configuration
- zabbix_value_map - Manage Zabbix value maps
- zabbix_globalmacro - Manage Zabbix global macros
- zabbix_item - Manage Zabbix items
- zabbix_it_service - Manage Zabbix IT services
- zabbix_script - Manage Zabbix script
- zabbix_map - Manage Zabbix maps
- zabbix_action - Manage Zabbix actions

### Other ideas
We are also open to new ideas for modules and collaboration.

### Authors

- [Adam Števko](https://github.com/xen0l)
- [Martin Pivarník](https://github.com/pivno)

