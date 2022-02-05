# Creation of VyOS vagrant box for the libvirt provider

Packer config for VyOS Vagrant/libvirt box autocreation

After installing packer, use this command to create a Vagrant/libvirt box file:

packer build vyos.json

Note: vyos-rolling-latest.iso can be downloaded from here: https://downloads.vyos.io/?dir=rolling/current/amd64 - this has beed tested on version 1.4.
