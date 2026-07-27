# Install Windows Server 2025

## Overview  
Windows Server is Microsoft's server operating system used to provide services such as Active Directory, DNS, DHCP, file sharing, and virtualization.  

Organizations use Windows Server to centrally manage users, computers, permissions, and network resources.  

Virtualization allows multiple operating systems to run on one physical computer, making it easier to build labs while reducing hardware costs.

## Objective  
Install Windows Server 2025 in a VMware virtual machine to create the foundation for an Active Directory lab.

## Environment  
Host OS: Windows 11  
Hypervisor: VMware Workstation Pro  
Guest OS: Windows Server 2025  
RAM Allocated: 4 GB   
CPU: 2 vCPUs  
Disk Size: 60 GB

## Steps Performed  
Created a new virtual machine in VMware Workstation Pro.  
Attached the Windows Server 2025 ISO.  
Allocated virtual hardware resources.  
Started the VM.  
Selected language, keyboard, and time settings.  
Chose Windows Server 2025 Standard (Desktop Experience).  
Accepted the license agreement.  
Selected Custom Installation.  
Installed Windows Server on the virtual disk.  
Completed the initial setup and created the Administrator password.

## Result  
Windows Server 2025 installed successfully.  
Logged in using the Administrator account.  
Server booted without errors.  

## Screenshot  
[![Windows Server](path/to/image.png)](https://github.com/HarperSec/Active-Directory-Home-Lab---Windows-Server-2025/blob/main/screenshots/01-Windows%20Server%202025.png)
[![Installation Process](path/to/image.png)](https://github.com/HarperSec/Active-Directory-Home-Lab---Windows-Server-2025/blob/main/screenshots/02.%20Installation%20Process.png)



## Lessons Learned  
Learned how to deploy Windows Server in a virtual environment.  
Became familiar with the Windows Server installation process.  
Verified the server was ready for Active Directory configuration.  
