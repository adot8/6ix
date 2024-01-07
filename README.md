# 6ix
Script for Active Directory mitm6 and ntlmrelayx attack


## Tools used
* impacket-netlmrelayx - https://github.com/fortra/impacket
* mitm6 - https://github.com/dirkjanm/mitm6

## Installation
Packages required:
* impacket
* mitm6
* scapy
* twisted
* netifaces
* xterm
  
`pip install -r requirements.txt`

`chmod +x 6ix`

## Usage
```
usage: ./6ix [-h] [-t] [-d] [-i] 

-h			display help message
-t TARGET		domain controller ip
-d DOMAIN		domain name
-i INTERFACE		interface

ex: sudo ./6ix -t 192.168.1.129 -d WRENCH.local -i eth0
```
