# Network & System Administration Labs

This repository contains a collection of labs created to demonstrate my skills in system and network administration. Each lab focuses on a specific core service—ranging from DHCP and DNS to NAT, monitoring, secure file transfer, and firewall installing.

These labs not only showcase my technical capabilities but also serve as practical tutorials for setting up and securing these services in real-world environments.

---

## Labs Overview

### DHCP

This lab covers the setup of a DHCP server to automatically assign IP addresses and essential network configuration to clients. It includes step-by-step instructions for configuring ranges, reservations, and network settings to ensure consistent client configuration.

### DHCP Multihomed

Demonstrates how to configure a DHCP server in a multihomed environment (with multiple interfaces or networks). This setup is useful for managing IP assignments across different subnets or VLANs, ensuring each segment receives appropriate network information.

### DHCP Security Best Practices

In this section, I provided security best practice recommendations for DHCP deployments. These include guidance on limiting IP ranges, using static reservations, and isolating untrusted segments to reduce exposure to rogue DHCP servers and misconfigurations.

### DNS

Covers the deployment of a local DNS server for internal name resolution and external forwarding. The lab includes DNS zone creation, A/CNAME record setup, and forwarding configuration to optimize resolution performance and reliability.

### DDNS (Dynamic DNS)

This lab demonstrates how to set up Dynamic DNS, enabling clients to update their DNS records automatically when their IP address changes. It's especially useful for dynamic networks where IPs aren't static.

### NAT & Port Forwarding

Explains how to set up Network Address Translation (NAT) and port forwarding to allow private network clients to access the internet and expose internal services securely to external users.

### Routing & Firewall (pfSense Lab)

One of the labs uses pfSense to demonstrate routing and firewall configuration. It includes setting up interfaces, firewall rules, to control traffic flow.

### Zabbix Monitoring

This lab details how to deploy and configure Zabbix, a powerful monitoring tool.

### SFTP Server

Walks through setting up a secure SFTP server for encrypted file transfers. Includes user management, directory isolation (chroot), and SSH hardening to ensure secure and compliant file exchange.
