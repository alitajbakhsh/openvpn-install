# Install OpenVpn on UBUNTU**



first run this command as root:

`
curl -O https://raw.githubusercontent.com/alitajbakhsh/openvpn-install/master/openvpn-install.sh
chmod +x openvpn-install.sh
`



# then run this command:

`
./openvpn-install.sh
`


# then you have to answer some questions or leave them to their default values like below:


APPROVE_INSTALL=y

APPROVE_IP=y

IPV6_SUPPORT=n

PORT_CHOICE=1

PROTOCOL_CHOICE=1

DNS=1

COMPRESSION_ENABLED=n

CUSTOMIZE_ENC=n

CLIENT=clientname

PASS=1


# after that you can choose to:

1: Add a client

2: Remove a client

3: uninstall Ovpn

# after you created a user just install Filezilla and download the client that you created it and use it.

# to go back to the create USER menu just run the command below again: 

`
./openvpn-install.sh
`


that's it
