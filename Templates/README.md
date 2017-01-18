# Zabbix Templates

## Adding missing MIBs
On Debian/Ubuntu, the best way to globally install extended MIB libraries is to use the downloader available via the APT repositories:

    sudo apt-get install snmp-mibs-downloader
    sudo download-mibs

For other systems, locate the required MIB libraries & put them under ``/usr/share/snmp/mibs``

Remember to restart zabbix-server to load the new MIBs