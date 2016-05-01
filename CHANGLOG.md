ansible-playbook ec2-hosts.yml --extra-vars '{"CleanupVPC":"false"}'

Changes By Release
==========================

## 1.0.2 TBD - Finish subnet config

###ProposedChanges

* Fix CIDR blocks for subnet so they can be spread accross availablity zones


## 1.0.1 Setup vpn-network config

###Major Changes:

* Setup routing table for public subnet
* Renamed ec2-hosts role to vpn-network to represent role functionality
* Set subnet dictionary in group vars
* Added Availablity zone to subnet configuration


