# Network Configuration

## Overview
Before installing Active Directory Domain Services (AD DS), the Windows Server 2025 virtual machine was configured with a static IP address. A Domain Controller requires a consistent network address because client computers and other services need to reliably locate the server for authentication, DNS, and directory services.

## VMware Network Configuration
The Windows Server 2025 virtual machine was configured using VMware Workstation Pro. The virtual network adapter was configured using a VMware NAT network, allowing the server to communicate with the host system and access external network resources.

## Static IP Configuration
The server was changed from a dynamically assigned DHCP address to a manually assigned static IP address.

Configuration:

- IP Address: 192.168.42.50
- Subnet Mask: 255.255.255.0
- Default Gateway: 192.168.42.2
- Preferred DNS Server: 192.168.42.2

## Why Static IP Is Important
A static IP address is important for servers because network devices need a predictable address to communicate with them. In an enterprise environment, Domain Controllers use static IP addresses so that users and computers can consistently connect to Active Directory services.

## Verification
After applying the static IP configuration, the settings were verified using the Windows command: ipconfig /all

## Screenshot
### Default Computer Name Before and After
[![Before Change](path/to/image.png)](https://github.com/HarperSec/Active-Directory-Home-Lab---Windows-Server-2025/blob/main/screenshots/03.%20Default%20Computer%20Name.png)  
[![After Change](path/to/image.png)](https://github.com/HarperSec/Active-Directory-Home-Lab---Windows-Server-2025/blob/main/screenshots/16.%20After%20OU.png)
### Static IP and Validation
[![Static IP](path/to/image.png)](https://github.com/HarperSec/Active-Directory-Home-Lab---Windows-Server-2025/blob/main/screenshots/05.%20Static%20IP.png)
[![Validation](path/to/image.png)](https://github.com/HarperSec/Active-Directory-Home-Lab---Windows-Server-2025/blob/main/screenshots/06.%20IP%20Configuration%20Verification.png)
