# firewalld-ansible-playbook
Setting up a simple host based firewall including optionally blocking all subnets from Ptn-land and other hostile countries

# Documentation

* Tested on RHEL 7, RHEL 8, RHEL 9, Fedora 37 and newer, Ubuntu 20.04.4, Debian 12
* Examples of RFC 1918 whitelisting of networks and IPs is provided in the vars.yml
* Examples using the RFC 3849 prefix for documentation purposes for whitelisting
* Drops any package originating from Ptn-Land according to the RIPE database
