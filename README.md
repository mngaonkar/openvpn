# OpenVPN setup with Ansible

## Objective
This is an ansible script to spin a VPN server on Ubuntu 16.04

## Steps
1. Update hosts file with IP address
2. Make sure Python 2.7 is installed on the remote server
`apt-get install python`
3. Run `ansible-playbook playbook.yml`
4. Client configuration is downloaded in the current directory as client.ovpn
5. Use OpenVPN client for connecting to VPN server


