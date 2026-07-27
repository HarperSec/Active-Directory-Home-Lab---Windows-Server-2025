# Active Directory Home Lab - Windows Server 2025
## Overview
This project documents the creation and configuration of a Windows Server 2025 Active Directory home lab environment using virtualization.

The goal of this lab was to gain hands-on experience with Windows Server administration, Active Directory Domain Services, identity management, Group Policy, and security event monitoring.

This project simulates a small business environment where a Windows Server Domain Controller manages users, computers, security groups, and organizational policies.


# Lab Environment

## Virtualization Platform
- VMware Workstation Pro

## Operating Systems
- Windows Server 2025 (Domain Controller)
- Windows 11 Client (Future Expansion)

## Domain Information
Domain Name: harper.local  
Domain Controller: Harper-7476  
Network Configuration: IP Address: 192.168.42.50  
Subnet Mask: 255.255.255.0  
Gateway: 192.168.42.2  

# Technologies Demonstrated

## Active Directory Domain Services (AD DS)
- Installed Active Directory Domain Services
- Promoted Windows Server to Domain Controller
- Created Active Directory domain

## Organizational Units (OUs)
Created organizational structure for:
- IT
- HR
- Finance
- Workstations
- Servers

## User Management
Created and managed:
- Domain user accounts
- Department-based users
- User organization within OUs

## Security Groups
Configured groups for:
- IT_Admins
- Help_Desk
- HR
- Finance

Demonstrated managing access through group membership.

## Group Policy
Created and configured Group Policy Objects to enforce security settings.
Examples:

- Password requirements
- Centralized configuration management

## Event Monitoring
Used Windows Event Viewer to analyze:
- Successful logons
- Failed authentication attempts
- User account creation events

# Skills Demonstrated
- Windows Server Administration
- Active Directory Administration
- Identity and Access Management (IAM)
- User and Group Management
- Group Policy Management
- Security Logging and Monitoring
- Basic Incident Investigation
- Virtualization

# Lab Phases
| Phase | Description |

| 1 | Windows Server Installation |  
| 2 | Static IP Configuration |  
| 3 | Server Manager Overview |  
| 4 | Installing Active Directory Domain Services |  
| 5 | Promoting Server to Domain Controller |  
| 6 | Creating Organizational Units |  
| 7 | Creating User Accounts |  
| 8 | Creating Security Groups |  
| 9 | Configuring Group Policy |  
| 10 | Reviewing Event Logs |  

Detailed documentation and screenshots can be found in the `/docs` folder.

# Lessons Learned
Through this project, I gained practical experience building and managing an Active Directory environment.

I learned how organizations use Windows Server to provide centralized identity management, control access through security groups, enforce security policies, and monitor system activity through logs.

# Future Improvements
Future additions to this lab include:

- Adding a Windows 11 client machine
- Joining client computers to the domain
- Creating shared folders with NTFS permissions
- Implementing additional Group Policies
- Configuring DHCP and DNS services
- Simulating security events for investigation
