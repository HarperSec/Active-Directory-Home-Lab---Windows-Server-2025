# Installing Active Directory Domain Services (AD DS)

## Overview
Active Directory Domain Services (AD DS) is a Windows Server role that provides centralized management of users, computers, and network resources within a domain environment. Organizations use Active Directory to control authentication, authorization, and access to resources.

In this lab, I installed the Active Directory Domain Services role on a Windows Server 2025 virtual machine as the first step toward creating a Domain Controller.


## Purpose
The purpose of installing AD DS is to enable the Windows Server system to manage identities and resources through Active Directory.

Active Directory allows administrators to:

- Create and manage user accounts
- Organize computers and users
- Apply security policies
- Control access permissions
- Provide centralized authentication


## Installation Process
The Active Directory Domain Services role was installed using Server Manager.

Steps performed:

1. Opened Server Manager.
2. Selected **Manage → Add Roles and Features**.
3. Selected **Role-based or feature-based installation**.
4. Chose the Windows Server 2025 machine.
5. Selected **Active Directory Domain Services (AD DS)**.
6. Added required features.
7. Confirmed the installation selections.
8. Installed the AD DS role.


## Why AD DS Is Important
In enterprise environments, Active Directory provides a centralized method for managing thousands of users, computers, and services.

For example, an organization can use Active Directory to:

- Allow employees to sign into company computers using domain accounts.
- Apply security policies to departments.
- Manage permissions for shared resources.
- Maintain user and computer records.


## Verification
After installation, Server Manager displayed a notification indicating that additional configuration was required to promote the server to a Domain Controller.

The next step in this lab is promoting the server to a Domain Controller and creating an Active Directory domain.


## Screenshots
### Add Roles and Features Wizard
[![Wizard](path/to/image.png)](https://github.com/HarperSec/Active-Directory-Home-Lab---Windows-Server-2025/blob/main/screenshots/08.%20Wizard%20Beginning.png)  
[![Add Roles](path/to/image.png)](https://github.com/HarperSec/Active-Directory-Home-Lab---Windows-Server-2025/blob/main/screenshots/09.%20Add%20Roles.png)
### Installation Progress and Completion 
[![Installation Progress](path/to/image.png)](https://github.com/HarperSec/Active-Directory-Home-Lab---Windows-Server-2025/blob/main/screenshots/10.%20Install%20Progress.png)  
[![description](path/to/image.png)](https://github.com/HarperSec/Active-Directory-Home-Lab---Windows-Server-2025/blob/main/screenshots/11.%20ADDS%20Installed.png)



## Lessons Learned

Installing the AD DS role does not automatically create a domain. The role only adds the necessary components to the server. The server must still be promoted to a Domain Controller before Active Directory can be used.
