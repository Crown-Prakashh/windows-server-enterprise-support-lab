Windows Server Enterprise Support Lab
Overview
This project demonstrates enterprise IT support and systems administration fundamentals using Windows Server 2025 and Windows 11 virtual machines in UTM on Apple Silicon. The lab simulates a small business environment with centralized identity management, networking services, domain-joined clients, shared drive permissions, and common IT support troubleshooting scenarios.

Lab Architecture
Windows Server 2025 (SERVER01)

Active Directory Domain Services
DNS Server
DHCP Server

Windows 11 Client (CLIENT01)

Domain-joined workstation
DHCP client
Remote Desktop client

Internal virtual network using UTM.

Technologies Used
Windows Server 2025, Windows 11, Active Directory, DNS, DHCP, Remote Desktop Protocol (RDP), UTM Virtualization, GitHub

Configurations Completed

Installed and configured Active Directory Domain Services
Created domain: prakashlab.local
Configured DNS and DHCP scope/leasing
Created organizational users and security groups
Joined Windows 11 client to domain
Configured shared network drives and permissions
Tested DNS resolution (nslookup), DHCP renewal (ipconfig /release & /renew), and Remote Desktop connectivity


User Accounts & Security Groups
UsernameDepartmentGroupjohn.supportIT SupportIT-Supportsarah.financeFinanceFinancerestricted.userStandard UserStandard-Users

Troubleshooting Scenarios

Password reset and account unlock
DNS resolution verification
DHCP lease renewal troubleshooting
Shared drive permission testing
Access denied troubleshooting
Remote Desktop connectivity testing


Skills Demonstrated

Windows Server administration & Active Directory management
Enterprise networking fundamentals (DNS, DHCP, RDP)
IT support troubleshooting
User, group, and permissions management
Domain administration and infrastructure documentation


Project Goal
To strengthen practical desktop support and systems administration skills in a simulated enterprise environment.
