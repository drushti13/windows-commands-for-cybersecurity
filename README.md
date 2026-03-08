# Windows Commands for Cybersecurity

This repository contains useful Windows Command Prompt commands for cybersecurity, system troubleshooting, and network investigation.

Windows environments are widely used in enterprise networks, making these commands important for security analysts.


## Networking Commands

nslookup  
Looks up a host or domain and returns its IP address.

Example:
nslookup google.com

Use case:
Investigating DNS resolution issues.

tracert  
Traces the network route taken to reach a target host.

Example:
tracert google.com

Use case:
Identifying where network delays or failures occur.

ipconfig  
Displays network configuration information.

Example:
ipconfig

Detailed information:
ipconfig /all

Shows MAC address, DNS servers, and DHCP information.

ping  
Tests connectivity between your computer and another host.

Example:
ping google.com

Use case:
Checking whether a server is reachable.

netstat  
Displays active network connections and listening ports.

Example:
netstat -ano

Use case:
Detecting suspicious network activity.

## File System Commands

chkdsk  
Checks disk volumes for errors and bad sectors.

Example:
chkdsk C:

Use case:
Detecting disk errors and corruption.

## System Information

driverquery  
Displays a list of installed device drivers.

Example:
driverquery

Use case:
Investigating system configuration.

sfc /scannow  
Scans and repairs corrupted Windows system files.

Example:
sfc /scannow

Use case:
Repairing damaged system files.


## Command Prompt Utilities

/?  
Displays help information for most commands.

Example:
ipconfig /?

Display text files

more file.txt

Displays the contents of a text file page by page.

Pipe output

some_command | more

Displays long command output one page at a time.
