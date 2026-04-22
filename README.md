# Home Lab Network Project

## Overview

I built a virtual home lab network using a Windows 10 virtual machine and an Ubuntu virtual machine in Oracle VM VirtualBox. The goal was to understand basic networking concepts and establish communication between systems on an internal network.

This was my first networking project and served as the foundation for my larger homelab build — [HomeLab-Server](https://github.com/gavin-michael/HomeLab-Server).

---

## Network Configuration

* Internal Network: 192.168.10.0/24
* Windows VM IP: 192.168.10.10
* Ubuntu VM IP: 192.168.10.20
* Secondary Adapter: NAT (for internet access)

---

## What I Did

* Installed and configured a Windows 10 virtual machine
* Installed and configured an Ubuntu virtual machine
* Set up dual network adapters (Internal Network + NAT)
* Assigned static IP addresses on both systems
* Configured Ubuntu networking using Netplan
* Enabled Windows Firewall rules to allow ICMP (ping)
* Verified connectivity between systems using ping
* Troubleshot multiple issues including:

  * Network interface configuration errors
  * IP conflicts
  * Firewall blocking ICMP traffic
  * Missing packages and dependency issues

---

## Skills Demonstrated

* TCP/IP networking fundamentals
* Static IP configuration
* Subnetting basics
* Linux system configuration (Netplan)
* Windows network configuration
* Virtualization using Oracle VM VirtualBox
* Network troubleshooting and problem solving

---

## Verification

Successful communication between both systems was confirmed using ICMP (ping):

* Windows to Ubuntu
* Ubuntu to Windows

---

## Screenshots

### Windows IP Configuration

![Windows IP Config](windows-ipconfig.png)

### Ubuntu Network Configuration

![Ubuntu IP Config](ubuntu-ip.png)

### Successful Ping Test

![Ping Test](ping-test.png)

---

## Key Takeaways

* Learned how to configure and manage multiple network adapters
* Gained hands-on experience with Linux and Windows networking
* Developed troubleshooting skills for real-world networking issues
* Understood the difference between NAT, DHCP, and static IP addressing

---

## What Came Next

This project taught me the fundamentals, but I wanted to go deeper. I moved from VirtualBox to a dedicated server running Proxmox and built a production-style homelab with VLAN segmentation, an OPNsense firewall, and a full monitoring stack. That project is documented here: [HomeLab-Server](https://github.com/gavin-michael/HomeLab-Server).
