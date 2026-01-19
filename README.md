<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

# Active Directory Home Lab

## Objective
This project demonstrates hands-on experience building and managing a basic Active Directory environment similar to what is used in enterprise and academic IT environments.

## Tools & Technologies
- VirtualBox
- Windows Server 2022
- Windows 10
- Active Directory Domain Services (AD DS)

## Lab Overview
The lab consists of:
- One Windows Server acting as a Domain Controller
- One Windows 11 client joined to the domain
- Centralized authentication and management using Active Directory

## Skills Demonstrated
- Windows Server installation and configuration
- Active Directory Domain Services setup
- Domain controller promotion
- DNS configuration
- Domain-joined client management
- User authentication and troubleshooting

## Lab Sections
- Environment Setup
- User & Organizational Unit Management
- Password Resets & Account Unlocks
- Group Policy Configuration
- Client Verification
- Help Desk Scenarios

---

## Environment Setup

### Virtual Lab Configuration
![VirtualBox Setup](screenshots/virtualbox-overview.png)

Configured a virtual environment using VirtualBox with a Windows Server domain controller and a Windows client machine.

### Windows Server Installation
![Server Manager](screenshots/server-manager.png)

Installed Windows Server and verified system configuration using Server Manager.

### Active Directory Installation
![AD Installed](screenshots/ad-installed.png)

Installed Active Directory Domain Services and DNS.

### Domain Controller Configuration
![Domain Controller](screenshots/domain-controller.png)

Promoted the server to a domain controller and created a new Active Directory domain.

### Client Joined to Domain
![Client Joined](screenshots/client-domain-join.png)

Joined a Windows 10 client machine to the domain.

### Domain User Login
![Domain Login](screenshots/domain-user-login.png)

Verified domain authentication by logging in with a domain user account.
