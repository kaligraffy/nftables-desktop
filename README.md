# nftables_desktop
Basic firewall setup script for linux using nftables

Usage:
- update nftables.conf with your changes
- sudo ./nftables_desktop 

The default conf:
- Logs everything, limits dropped packets
- Drops anything not matching one of the rules (increased privacy)
- Allows http/https/dns/dns over tls/outbound ssh by default
- Applies rules in both ip4 and ip6
- Allows ping outbound

Tested on Debian            

Outputs logs to the syslog
