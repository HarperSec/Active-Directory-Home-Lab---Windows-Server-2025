# Promoting Server to Domain Controller

## Overview
After installing the Active Directory Domain Services (AD DS) role, the Windows Server 2025 virtual machine was promoted to a Domain Controller.

A Domain Controller (DC) is a server that hosts Active Directory Domain Services and manages authentication, authorization, and directory information for users, computers, and network resources.

## Purpose
Promoting the server to a Domain Controller allows it to manage an Active Directory domain. In an enterprise environment, Domain Controllers are responsible for:

- Authenticating users when they sign in
- Managing computer accounts
- Storing Active Directory objects
- Applying security policies
- Providing DNS services required for domain communication

## Domain Configuration
A new Active Directory forest and domain were created for this lab.

Domain Name: harper.local
Domain Controller: Harper-7476
Forest Functional Level: Windows Server 2025

## Promotion Process
The server was promoted using Server Manager.

Steps performed:

1. Opened Server Manager.
2. Selected the notification flag.
3. Chose "Promote this server to a domain controller."
4. Selected "Add a new forest."
5. Created the new domain name.
6. Configured the Directory Services Restore Mode (DSRM) password.
7. Reviewed configuration settings.
8. Installed Active Directory Domain Services.
9. Restarted the server.

## Active Directory Components Created
The promotion process created:

- Active Directory forest
- Active Directory domain
- Domain Controller
- DNS integration
- SYSVOL folder

## Verification
After restarting, the server was verified as a Domain Controller by:

- Logging in with the domain administrator account
- Opening Active Directory Users and Computers
- Confirming the domain structure was available

## Screenshots
### Domain Name
[![Domain](path/to/image.png)]((https://github.com/HarperSec/Active-Directory-Home-Lab---Windows-Server-2025/blob/main/screenshots/12.%20Domain.png))
### Forest Level
[![Forest Level](path/to/image.png)](https://github.com/HarperSec/Active-Directory-Home-Lab---Windows-Server-2025/blob/main/screenshots/13.%20Forest%20Level.png)
### Review 
[![Review](path/to/image.png)](https://github.com/HarperSec/Active-Directory-Home-Lab---Windows-Server-2025/blob/main/screenshots/14.%20Review.png)




## Lessons Learned

Promoting a Windows Server to a Domain Controller transforms the server from a standalone system into the central identity management server for an Active Directory environment.

This process demonstrated how organizations use Domain Controllers to centrally manage users, computers, authentication, and security policies.
