# Active Directory Infrastructure & PowerShell Administration Lab
This project documents the setup of a Windows Server 2019 Active Directory lab in VirtualBox. The environment includes a domain controller, DNS, DHCP, RRAS/NAT, a domain-joined Windows 10 client, Group Policy, delegated administration, PowerShell user provisioning, and shared folder permissions.

## Network Topology
<img width="676" height="530" alt="Active Directory Topology" src="https://github.com/user-attachments/assets/d0c41d97-ce43-4431-a5ef-1276e00b4dd8" />

## Lab Environment

- Hypervisor: VirtualBox
- Server: Windows Server 2019
- Client: Windows 10 Pro
- Domain: maindomain.com
- Internal Network: 172.16.0.0/24
- Domain Controller IP: 172.16.0.1
- DHCP Scope: 172.16.0.100–172.16.0.200
