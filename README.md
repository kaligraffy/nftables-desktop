# nftables_desktop
Basic firewall setup script for linux using nftables

Usage:
- update nftables.conf with your changes 
- sudo ./nftables_desktop ARG1

ARG1 can be:
- -i or install - installs nftables
- -e or enable - enable firewall
- -d or disable - disable firewall
- -h or help - prints this help message

Tested on Debian            

Outputs logs to the syslog
