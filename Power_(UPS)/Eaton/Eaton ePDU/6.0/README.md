# EATON ePDU

## Overview

This template is based on Valentin Stangaciu one.

It is valid for Eaton Rack PDU G4 and also Eaton Rack PDU G3 without Daisy Chain. 

But, because Zabbix doesn't support cascaded devices and multiple SNMPINDEX, it's not possible to load correctly the template for other devices than host if daisy chain is existing... And it means that Daisy Chain for PDU G3 is not supported. 

A workaround can consist to clone this template, with all information rewritten for each part of the daisy chain.


tested with 
- EATON ePDU G3 Switched
- EATON ePDU G3 Managed
- Eaton Rack PDU G4 Metered Input
- Eaton Rack PDU G4 Metered Output
- Eaton Rack PDU G4 Managed



Created in Zabbix v6.4



## Author

Quentin Renard : quentin.renard@gmail.com based on works made by Valentin Stangaciu - valentin.stangaciu@cs.upt.ro

## Macros used

There are no macros links in this template.

## Discovery Rules

There are 10 Discovery rules to verify and generate : 
- Number of Phases
- Input Current
- Input Power
- Input Voltage
- Number of Outlets
- Outlet Current
- Outlet Power


## Template links

Template Module Generic SNMP

