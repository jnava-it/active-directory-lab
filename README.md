# Active Directory Home Lab

## Project Overview
Built a fully functional Active Directory environment using VirtualBox to simulate a real enterprise IT infrastructure. This lab demonstrates hands-on experience with Windows Server administration, user management, and Group Policy configuration.

## Environment
- **Domain Controller:** Windows Server 2022 (DC01)
- **Client Machine:** Windows 11 Enterprise (CLIENT01)
- **Domain:** helplab.local
- **Platform:** Oracle VirtualBox

## What I Built
- Deployed and configured a Windows Server 2022 domain controller
- Installed and configured Active Directory Domain Services (AD DS), DNS, and DHCP
- Created Organizational Units (OUs): IT, HR, Finance, Contractors
- Created 10 user accounts across all OUs
- Created security groups: IT-Staff, HR-Staff, Finance-Staff
- Configured Group Policy Objects (GPOs): Password Policy, Desktop Settings, Drive Map
- Joined a Windows 11 client machine to the domain
- Practiced tier 1 help desk tasks: password resets, account unlocks, user provisioning/deprovisioning

## Skills Demonstrated
- Active Directory administration
- Windows Server 2022 configuration
- User and group management
- Group Policy Object (GPO) creation and linking
- DNS and DHCP configuration
- Domain join procedures
- Help desk troubleshooting workflows

## Screenshots

![AD Users and Computers](01-AD-IT-OU.png)
![GPO Management](08-AD-GPOs.png)
![Server Manager](09-AD-Server-Manager.png)
![Domain Joined Client](10-CLIENT-Domain-Joined.png)
![Computers in AD](11-AD-Computers.png)
![Ping Test](12-CLIENT-Ping-DC.png)
