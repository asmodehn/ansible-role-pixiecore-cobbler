Pixiecore Cobbler Nginx
=======================

This is:

- an ansible role
- a docker container

Which provides:

- PXE boot out of the box for your network ( only DHCP required - can be done by your router ) via pixiecore
- Baremetal machine provisioning from iso (ubuntu provisioning and more) via Cobbler
- Cobbler Web interface from a small webserver via Nginx and uwsgi

You can use: 

- Ansible role to deploy this on a machine, for maximum customization
- Docker container to deploy this on a network, for minimum disturbance

