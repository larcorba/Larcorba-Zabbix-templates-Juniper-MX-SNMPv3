Zabbix template
======

Intro
------
Check out Zabbix share and drop a rating/comment! :)

https://share.zabbix.com/network_devices/juniper/juniper-mx-snmpv3


Features
------
- Interface discovery
  - General disovery interfaces rule
    - Interface Utilization trigger
  - IRB disovery rule
- Hardware discovery
- Inventory items


Macros
------
Do not forget the add the macro's:

User: {$JUN_V3_USER}

Password: {$JUN_V3_AUTHPASS}

Inventory
------
Make sure to add the inventory 'automatic' options at your host if you want to use the invetory option.
