# SNMP
SNMP Ansible role installs and configures SNMP.

## Variables
- snmp_master_ips: IPs from which requests will come (list)
- snmp_rocommunity: List of snmp rocommunity objects
  - string: community string
  - address: allowed address
- snmp_rwcommunity: List of snmp rwcommunity objects
  - string: community string
  - address: allowed address
- snmp_device_location: Device location ( description)
- snmp_admin_mail: snmp admin mail
