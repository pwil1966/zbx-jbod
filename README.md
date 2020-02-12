# zbx-jbod

Zabbix templates for Western Digital Ultrastar Data60 and Data102 JBOD enclosures. Needs a host with group Templates/Server Hardware and host macro {$JBOD_IP} assigned to the IP address of the IOM to monitor. For dual IOM systems, suggest using two hosts with host macros assigned appropriately for redundancy. I use the visible name to identify the JBOD (and IOM A or IOM B). 
