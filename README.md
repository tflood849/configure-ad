<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

# Active Directory Home Lab

## Objective
This project demonstrates my hands-on experience building and managing a basic Active Directory environment similar to what is used in corporate enterprises and academic IT environments.

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

---

## Environment Setup

### Virtual Lab Configuration

<img width="1919" height="1079" alt="Screenshot 2026-01-18 164808" src="https://github.com/user-attachments/assets/30ff0dd0-192e-466f-b3b8-67fbaf357864" />

I Configured 2 virtual environments using VirtualBox with a Windows Server domain controller - Windows 2022 and a Windows client machine - Windows 11.



### Windows Server Installation
Server Manager <img width="1019" height="766" alt="Screenshot 2026-01-18 165104" src="https://github.com/user-attachments/assets/aa644ad5-da95-4f63-bbf3-00f19a3c5142" />

Installed Windows Server and verified system configuration using Server Manager.


### Creating Static IP
<img width="1019" height="764" alt="Screenshot 2026-01-18 171249" src="https://github.com/user-attachments/assets/be1d1c17-9739-4131-b8d9-b3025465fd4b" />
- Created a static IP for the windows server so that the client machine can connect to the server reliably 

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
