# nftables_desktop
Basic firewall setup script for linux using nftables

Usage:
- update nftables.conf with your changes
- sudo ./nftables_desktop ARG1

ARG1 can be:
-i or install - installs nftables
-e or enable - enable firewall
-d or disable - disable firewall
-h or help - prints this help message

The default conf:
- Logs everything, limits dropped packets
- Drops anything not matching one of the rules (increased privacy)
- Allows http/https/dns/dns over tls/outbound ssh by default
- Applies rules in both ip4 and ip6
- Allows ping outbound

Tested on Debian            

Outputs logs to the syslog
