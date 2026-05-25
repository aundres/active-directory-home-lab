# Active Directory Home Lab

## Overview
Built a simulated enterprise environment using Windows Server 2022 
and Windows 10 client VMs in VirtualBox. Configured a domain 
controller, user accounts, organizational units, Group Policy, 
DHCP, and DNS.

## Tools Used
- VirtualBox
- Windows Server 2022
- Windows 10 Pro
- Active Directory Domain Services (AD DS)

## Lab Diagram
[paste a simple diagram here or describe it]

## What I Built
- Promoted Windows Server to Domain Controller
- Created Organizational Units for departments
- Added user accounts and assigned them to OUs
- Configured Group Policy to enforce password policies
- Set up DHCP scope to automatically assign IPs to clients
- Joined Windows 10 VM to the domain

## Screenshots
**Active Directory Users and Computers**
<img width="753" height="528" alt="ad-users" src="https://github.com/user-attachments/assets/8d1453e4-315a-4b7e-873b-6deb7652fc69" />

**DHCP Scope**
<img width="799" height="623" alt="dhcp-scope" src="https://github.com/user-attachments/assets/02d1b64d-54b6-413d-8038-90d477257943" />

**Windows 10 Domain Join Confirmed**
<img width="896" height="622" alt="domain-joined" src="https://github.com/user-attachments/assets/5e888385-3e8d-473b-bc13-a00300c3152c" />

**Group Policy Management**
<img width="1022" height="732" alt="group-policy" src="https://github.com/user-attachments/assets/ac1dafaa-7e92-4b69-b9bc-1e1d5c8b371c" />

## What I Learned
- How domain authentication works vs local accounts
- Why organizations use centralized AD management
- How Group Policy pushes settings to all domain machines
- How DHCP and DNS work together in a domain environment
