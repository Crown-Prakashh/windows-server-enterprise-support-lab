# Windows Server Enterprise Support Lab

# Overview
This project demonstrates enterprise IT support and systems administration fundamentals using Windows Server 2025 and Windows 11 virtual machines in UTM on Apple Silicon.

The lab simulates a small business environment with:
- Centralized identity management
- Networking services
- Domain-joined clients
- Shared drive permissions
- Common IT support troubleshooting scenarios
# Lab Architecture
# Windows Server 2025 — SERVER01
- Active Directory Domain Services
- DNS Server
- DHCP Server
# Windows 11 Client — CLIENT01
- Domain-joined workstation
- DHCP client
- Remote Desktop client

# Network
- Internal virtual network using UTM

# Technologies Used
| Category | Technology |
|---|---|
| Servers & Clients | Windows Server 2025, Windows 11 |
| Directory Services | Active Directory |
| Networking | DNS, DHCP |
| Remote Access | Remote Desktop Protocol (RDP) |
| Virtualization | UTM (Apple Silicon) |
| Version Control | GitHub |
# Configurations Completed
# Active Directory & Domain

- Installed and configured Active Directory Domain Services
- Created domain: `prakashlab.local`
- Created organizational users and security groups
- Joined Windows 11 client to domain
# Networking

- Configured DNS services
- Configured DHCP scope and leasing
# Access & Permissions
 Configured shared network drives and permissions
# Testing & Verification
- Tested DNS resolution with `nslookup`
- Tested DHCP functionality with `ipconfig /release` and `ipconfig /renew`
- Tested Remote Desktop connectivity
- 
# User Accounts
| Username | Department |
|---|---|
| john.support | IT Support |
| sarah.finance | Finance |
| restricted.user | Standard User |

# Security Groups
| Group Name | Description |
|---|---|
| IT-Support | IT support staff |
| Finance | Finance department users |
| Standard-Users | General restricted users |

# Troubleshooting Scenarios

| Scenario | Area |
|---|---|
| Password reset and account unlock | Active Directory |
| DNS resolution verification | Networking |
| DHCP lease renewal troubleshooting | Networking |
| Shared drive permission testing | File Services |
| Access denied troubleshooting | Permissions |
| Remote Desktop connectivity testing | Remote Access |

# Skills Demonstrated
# Administration
- Windows Server administration
- Active Directory management
- Domain administration

# Networking
- Enterprise networking fundamentals
- DNS and DHCP configuration

# Support & Security
- IT support troubleshooting
- User and permissions management
- Infrastructure documentation

# Screenshots
Screenshots and configuration walkthroughs will be uploaded throughout the project build.

# Project Goal
To strengthen practical desktop support and systems administration skills in a simulated enterprise environment.
