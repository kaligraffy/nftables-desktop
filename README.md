# nftables_desktop
Basic firewall setup script for linux using nftables

Logs everything, limits dropped packets

Drops anything not matching one of the rules (increased privacy)

Applies rules in both ip4 and ip6

Allows ping outbound

Disallows any 'new' connections inbound

You may need to add some rules for inbound SSH 

If you do, change the script or use the iptables --insert so your rules don't end up under the default drop rules.

Tested for debian (uses apt)

Outputs logs to the syslog

Usage: set your config nftables.conf
./nftables_desktop -e to enable it
