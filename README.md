# Zabbix Resources

A collection of Zabbix add-ons & templates

## Templates
### Adding missing MIBs
On Debian/Ubuntu, the best way to globally install extended MIB libraries is to use the downloader available via the APT repositories:

    sudo apt-get install snmp-mibs-downloader
    sudo download-mibs

For other systems, locate the required MIB libraries & put them under ``/usr/share/snmp/mibs``

Remember to restart zabbix-server to load the new MIBs

## Credits
The following HP templates are fixed/improved versions of those provided by the Zabbiz team, found [here](https://share.zabbix.com/network_devices/cat-hp/template-hp-chassis-brocade-blade).
* Template_HP_Blade_Switch.xml
* Template_HP_Brocade_SAN_Switch.xml
* Template_HP_Chassis.xml
