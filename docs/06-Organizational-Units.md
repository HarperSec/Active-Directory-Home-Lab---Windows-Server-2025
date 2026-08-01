# Organizational Units (OUs)

## Overview
An Organizational Unit (OU) is a container within Active Directory used to organize and manage users, computers, groups, and other objects inside a domain.

Organizations use OUs to create a logical structure that represents departments, locations, or job functions. OUs make it easier for administrators to apply Group Policy settings, delegate permissions, and manage resources efficiently.

## Purpose
In this lab, Organizational Units were created to organize Active Directory objects and simulate how an organization might structure its domain environment.

Using OUs allows administrators to:

- Organize users and computers
- Apply different security policies to specific groups
- Delegate administrative responsibilities
- Simplify Active Directory management

## Lab OU Structure

The following Organizational Units were created:
IT, HR, Finance, Servers, Workstations


## Creating Organizational Units
The OUs were created using Active Directory Users and Computers.

Steps performed:

1. Opened Server Manager.
2. Selected Tools.
3. Opened Active Directory Users and Computers.
4. Right-clicked the domain name.
5. Selected New → Organizational Unit.
6. Created department-based OUs.

## Active Directory Users and Computers Before and After 
### Before
![Before](../screenshots/15-Before%20OU.png)  
### After
![After](../screenshots/16-After%20OU.png)

## Real-World Use Case
In an enterprise environment, OUs allow administrators to manage thousands of users and computers efficiently.

Example:
The IT department may require different permissions than the Finance department. Administrators can apply specific Group Policies to each OU without affecting the entire organization.

## Verification
The Organizational Units were verified using Active Directory Users and Computers by confirming that the new OU structure appeared under the domain.

## Lessons Learned
Creating Organizational Units demonstrated how Active Directory objects can be organized for easier administration. OUs are an important part of enterprise Active Directory because they allow administrators to apply policies and manage resources based on organizational needs.
