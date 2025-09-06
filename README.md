# Implementation Summary

This project implements a Hybrid Cloud Lab connecting a local Proxmox environment with an Azure-hosted Proxmox instance. Key components and steps include:

 - Proxmox Setup – Installed and configured on both local and Azure environments.

 - pfSense Firewalls – Deployed on each Proxmox host to manage LAN/WAN segmentation and secure traffic.

 - WireGuard VPN – Configured a site-to-site tunnel between local and Azure environments for secure connectivity.

 - Azure Networking – Created VNets, subnets, and security groups to support the hybrid setup.

 - Zabbix Monitoring – Installed a central Zabbix Server on-premise and deployed Zabbix Proxies in the cloud for distributed monitoring.

 - Verification – Tested connectivity through the tunnel, validated firewall rules, and confirmed Zabbix proxies successfully reported to the server.

This lab provides a hands-on hybrid environment integrating cloud + on-prem infrastructure, VPN tunneling, and centralized monitoring.
