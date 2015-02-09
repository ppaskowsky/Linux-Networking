#
# OpenSwan Configurations
#

/etc/sysctl.conf must be modified

change protostack to netkey in ipsec.conf

disable source desitnation checks on aws instance

assign elastic ip

add route to remote network in routing table


#troubleshooting

Service Ipsec (restart, status)
ipsec verify
ipsec auto --status
/var/log/messages
/var/log/auth