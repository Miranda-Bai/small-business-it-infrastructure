# Small Business IT Infrastructure

A hands-on enterprise IT portfolio project demonstrating the deployment and administration of a Windows-based business environment.

Design and deploy a complete enterprise IT environment supporting 20 simulated users, including Active Directory, Windows Server, Microsoft 365 administration, Group Policy, DNS, DHCP, file permissions, PowerShell automation, technical documentation, and end-user support scenarios.

## Technologies

- Windows Server 2022
- Active Directory
- DNS
- DHCP
- Group Policy
- Windows 11
- Microsoft 365
- PowerShell
- File Server

## Background
I'm an IT support professional helping a newly started tourism company to design and deploy its IT environment.

**Company name:** Southern Alps Adventure Ltd

**Employees:**

There are five employees in phase one, and it will be extended to 20.

| **Name**    | **Department** |
| ----------- | ---------- |
| Emma Wilson | Manager    |
| Miranda Bai | IT         |
| Jack Chen   | Reception  |
| Sarah Lee   | Finance    |
| David Brown | Marketing  |

The **goal** of phase one is to build and administer a Windows Active Directory environment supporting multiple departments.

## Day 1

### Network Infrastructure

                Internet
                     │
             Home Router
                     │
         -----------------------
         │                     │
   Windows Server         Windows 11 Client
      192.168.10.10        DHCP

In the future will add 

- Printer
- NAS
- Backup
- WiFi
- Microsoft 365

### Server Configuration

Windows Server 2022

```bash
Hostname
SRV-DC01

# IP
192.168.10.10

# Subnet
255.255.255.0

# Gateway
192.168.10.1

# DNS
192.168.10.10
```
