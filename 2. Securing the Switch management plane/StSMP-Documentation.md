## PROJECT
Securing the switch management plane

## OVERVIEW

 * Problem: 
  - When any unknown contractor can enter the office during off-hours, there is no quarantee that no unauthorized indidviduals won't plug into the switch to alter network settings or monitor sensitive traffic.

 * Solution: 
  - This project introduces Cisco IOS administration and basic device hardening. I configured a Virtual Local Area Network (VLAN) interface to give the switch itself as an IP address, allowing it to be managed across the network. 


## TECHNOLOGY USED
 - Cisco IOS software
 - Switch Virtual Interface (SVI)
 - Line Virtual Teletype (VTY 0 15)
 - Password Encryption Service, SHA/MD5 enable secret hashing protocal


## CONFIGURATIONS
 - Named the device and secure privileged access <name: Dept-Switch, Password: Dept-Switch>>
 - Secured the physical console port <<password: SecureConsole12>
 - Configured the switch  Virtual Interface (SVI) management IP
 - Secured the remote access virtual lines
 - Encrypted the system password
 - Configured static IP address to the end point devices
 - Disconnected the console cable and remotely connected the switch using telnet with the Admin-PC on the network line.
 -Everything <ping> and verification was succesful



## I secure the console port, restrict access to privileged executive mode and establish secure remote management access. The hardened switch can only be managed by authenticated administrators.