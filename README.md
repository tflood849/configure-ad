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



---

## Environment Setup

### Virtual Lab Configuration




These images shows the virtual machine settings That I used to  sucessfully install and configure the domain controller and the client machine, including memory allocation, CPU resources, storage, and networking.

<img width="1631" height="917" alt="Screenshot 2026-01-18 164808" src="https://github.com/user-attachments/assets/30ff0dd0-192e-466f-b3b8-67fbaf357864" />
<img width="1631" height="917" alt="Screenshot 2026-01-19 135457" src="https://github.com/user-attachments/assets/b3fcbafe-7c97-4d07-82a8-79bc45af55a3" />


<br>
<br>

### Windows Server Installation

Here, I installed the Windows Server 2022 Server Manager that I used to configure the local server and install roles and features as part of this Active Directory home lab.

Server Manager <img width="1631" height="917" alt="Screenshot 2026-01-18 165104" src="https://github.com/user-attachments/assets/aa644ad5-da95-4f63-bbf3-00f19a3c5142" />


<br>
<br>

### Creating Static IP

This is where I manually configured a static IP address on the server to ensure that the client machine can consistently locate and connect to the Domain Controller within the Active Directory.

<img width="1631" height="917" alt="Screenshot 2026-01-18 171249" src="https://github.com/user-attachments/assets/be1d1c17-9739-4131-b8d9-b3025465fd4b" />

 
<br>
<br>

### Active Directory Installation

I verified that the Active Directory was installed successfully by accessing the Active Directory Users and Computers console and viewing default domain users, groups, and security objects.

<img width="1631" height="917" alt="Screenshot 2026-01-18 174640" src="https://github.com/user-attachments/assets/9cc7967c-d4a6-4a5d-902c-2d195739dc98" />


<br>
<br>

### Domain Controller Configuration

Then I confirmed domain controller setup by validating the server name (DC01), domain (lab.local), and static IP configuration (192.168.56.10) in the Local Server console.

<img width="1631" height="917" alt="Screenshot 2026-01-18 174857" src="https://github.com/user-attachments/assets/eef3798b-1a53-4d62-acc6-7411ebc7b2be" />


<br>
<br>

### Creating Organizational Units in Active Directory

I added Organizational Units (Accounts and Groups) in Active Directory to organize users and security groups within the lab.local domain.

<img width="1631" height="917" alt="Screenshot 2026-01-18 175757" src="https://github.com/user-attachments/assets/e25cd399-04fa-4530-ba19-4b675bf4715d" />


<br>
<br>

### Configuring Windows 11 Client to Connect to Domain Controller

I updated client DNS settings so the Windows 11 machine can communicate with the Domain Controller which is the static IP of 192.168.56.10.

<img width="1631" height="917" alt="Screenshot 2026-01-19 093147" src="https://github.com/user-attachments/assets/db9448f0-877d-4526-84c6-f7828246d2b4" />


<br>
<br>

### Windows 11 Client Successfully Joined to Active Directory Domain

I confirmed that the client machine joined the domain by viewing the computer account in Active Directory.

<img width="1631" height="917" alt="Screenshot 2026-01-19 104357" src="https://github.com/user-attachments/assets/bcbe1c9a-d3d3-4876-a82d-74359de8f20e" />

