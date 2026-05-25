# 🔥 Azure Firewall Configuration & Network Security Lab

## 📌 Overview
This lab demonstrates Azure Firewall configuration and network security management in a Microsoft Azure environment. The project focuses on creating firewall rules, controlling inbound and outbound traffic, and testing secure communication between Azure resources.

The lab simulates real-world cloud networking and security tasks commonly performed by cloud administrators and network administrators.

---

# 🧰 Technologies Used
- Microsoft Azure
- Azure Firewall
- Windows Server
- Windows 10/11
- Virtual Networks (VNets)
- Network Security
- TCP/IP Networking

---

# 🖥️ Lab Environment

| Resource | Role |
|---|---|
| `dc-1` | Domain Controller |
| `client-1` | Client Machine |
| `Azure Firewall` | Network Traffic Filtering |

- Domain: `helpdesklab.local`
- Virtual Network: `hd-vnet`
- Resource Group: `hd-lab`

---

# 🔬 Lab Activities

## Azure Firewall Deployment

### Objective
Deploy and configure Azure Firewall within the virtual network.

### Tasks Performed
- Created Azure Firewall resource
- Configured firewall subnet
- Associated firewall with the virtual network

### Screenshot
(Add screenshot here)

---

## Firewall Rule Configuration

### Objective
Create network rules to allow and restrict traffic between systems.

### Tasks Performed
- Configured inbound and outbound firewall rules
- Allowed ICMP and RDP traffic
- Tested traffic filtering behavior

### Screenshot
(Add screenshot here)

---

## Network Connectivity Testing

### Objective
Verify communication between Azure resources after firewall configuration.

### Commands Used
```powershell
ping dc-1
```

### Tasks Performed
- Tested connectivity between systems
- Verified firewall rule functionality
- Confirmed successful traffic filtering

### Screenshot
(Add screenshot here)

---

## Traffic Restriction Testing

### Objective
Test blocked network communication through firewall policies.

### Tasks Performed
- Attempted restricted network connections
- Verified blocked traffic behavior
- Confirmed firewall policy enforcement

### Screenshot
(Add screenshot here)

---

# 🛠️ Troubleshooting Scenarios

## Firewall Rule Troubleshooting
- Verified rule priority and configuration
- Tested inbound and outbound traffic
- Confirmed proper network rule processing
## Connectivity Troubleshooting
- Diagnosed blocked communication between resources
- Verified subnet and firewall configuration
- Tested connectivity after modifying firewall rules


# 💡 Skills Demonstrated
- Azure Firewall deployment
- Network security management
- Firewall rule configuration
- Cloud networking
- Traffic filtering
- Connectivity troubleshooting
- Azure infrastructure administration
