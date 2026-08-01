# Group Policy

## Overview
Group Policy is a Windows Server feature that allows administrators to centrally configure and enforce settings for users and computers in an Active Directory environment.

## Purpose
In this lab, Group Policy was used to create security settings that can be applied across the domain.

Organizations use Group Policy to:

- Enforce password requirements
- Configure security settings
- Restrict user actions
- Deploy software
- Manage Windows systems

## Policy Created
A Group Policy Object named "Domain Password Policy" was created.

Settings configured:

- Minimum password length: 12 characters
- Password complexity: Enabled
- Password history: 5 passwords remembered

## Implementation
The GPO was created using Group Policy Management and linked to an Active Directory Organizational Unit/domain.

## Group Policy Management

![Group Policy Management](../screenshots/19-Group%20Policy%20Management.png)

### Created GPO

![Created GPO](../screenshots/20-Created%20GPO.png)

### Password Policy Settings

![Password Policy Settings](../screenshots/21-Password%20Policy%20Settings.png)

### GPO Linked

![GPO Linked](../screenshots/22-GPO%20Linked.png)


## Lessons Learned
Group Policy allows administrators to manage security settings centrally instead of configuring each computer individually. This improves consistency and reduces administrative effort.
