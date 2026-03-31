# Home Lab Network Project

## Overview

I built a virtual home lab network using a Windows 10 virtual machine and an Ubuntu virtual machine in Oracle VM VirtualBox. The goal was to understand basic networking concepts and establish communication between systems on an internal network.

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

* Windows → Ubuntu
* Ubuntu → Windows

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

## Future Improvements

* Add Wireshark for packet analysis
* Simulate network failures and recovery scenarios
* Expand lab with additional virtual machines
* Implement basic Active Directory environment

---
