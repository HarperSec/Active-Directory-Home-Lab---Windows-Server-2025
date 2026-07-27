# Active Directory Users

## Overview
Active Directory user accounts represent individual employees or accounts that require access to resources within a domain environment.

Organizations use Active Directory user accounts to centrally manage authentication, permissions, and access control. Instead of creating separate accounts on each computer, users can sign in using a domain account managed by the Domain Controller.

## Purpose
In this lab, user accounts were created to simulate employees within different departments of an organization.

Creating users allowed me to practice:

- Creating Active Directory accounts
- Organizing users into Organizational Units (OUs)

## Users Created
The following user accounts were created:

| User | Department |

| John Smith | IT |
| Issac Long | IT |
| Jane Doe | HR |
| Sarah Johnson | Finance |

## User Organization
Users were placed into the appropriate Organizational Units based on department.

Example:

IT: John Smith, Issac Long
HR: Jane Doe
Finance: Sarah Johnson


## User Creation Process
Users were created using Active Directory Users and Computers.

Steps performed:

1. Opened Server Manager.
2. Selected Tools.
3. Opened Active Directory Users and Computers.
4. Navigated to the appropriate Organizational Unit.
5. Created a new user account.
6. Configured user information and password settings.

## Security Considerations
In an enterprise environment, user accounts must be managed carefully to maintain security.

Common security practices include:

- Enforcing strong password policies
- Applying the principle of least privilege
- Assigning permissions through security groups
- Disabling inactive accounts
- Monitoring account activity through event logs

## Screenshots
### Creating a User Account
[![Creating User](path/to/image.png)](https://github.com/HarperSec/Active-Directory-Home-Lab---Windows-Server-2025/blob/main/screenshots/17.%20Create%20User.png)


## Lessons Learned

Creating user accounts demonstrated how Active Directory provides centralized identity management. By combining Organizational Units and Security Groups, administrators can organize users and control access based on job roles and responsibilities.
