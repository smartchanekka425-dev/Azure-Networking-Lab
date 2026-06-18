# Azure-Networking-Lab

## Overview

This project demonstrates the deployment and configuration of Azure networking resources, including Virtual Networks (VNets), subnets, Network Security Groups (NSGs), and Windows Server virtual machines.

The goal of this lab was to gain hands-on experience with Azure infrastructure, network segmentation, and cloud administration while documenting the environment in a professional GitHub portfolio.

---

## Technologies Used

* Microsoft Azure
* Azure Virtual Networks (VNets)
* Azure Subnets
* Azure Network Security Groups (NSGs)
* Windows Server 2022
* Azure Virtual Machines
* Public and Private IP Addressing
* GitHub

---

## Environment Configuration

### Virtual Network

| Component     | Configuration     |
| ------------- | ----------------- |
| VNet Name     | Azure-Network-Lab |
| Address Space | 10.0.0.0/16       |

### Subnets

| Subnet         | Address Range |
| -------------- | ------------- |
| Default Subnet | 10.0.0.0/24   |
| Web-Subnet     | 10.0.2.0/24   |

### Virtual Machines

| VM Name | Purpose                          |
| ------- | -------------------------------- |
| AdminVM | Administrative/Management Server |
| WebVM   | Web/Application Server           |

---

## Architecture Diagram

Internet
│
▼
Network Security Group (NSG)
│
▼
Azure Virtual Network (10.0.0.0/16)
│
├── Default Subnet (10.0.0.0/24)
│      └── AdminVM
│
└── Web-Subnet (10.0.2.0/24)
└── WebVM

---

## Implementation Steps

1. Created Azure Resource Group.
2. Deployed Azure Virtual Network.
3. Configured address space and subnet segmentation.
4. Created Default and Web subnets.
5. Deployed Windows Server virtual machines.
6. Associated virtual machines with appropriate subnets.
7. Configured Network Security Groups.
8. Verified VM deployment and connectivity.
9. Documented architecture and screenshots.
10. Published project to GitHub.

---

## Screenshots

### VNet Overview

![VNet Overview](Screenshots/01-VNet-Overview.png)

### Subnet Configuration

![Subnet Configuration](Screenshots/02-Subnet-Configuration.png)

### AdminVM Network Settings

![AdminVM](Screenshots/03-AdminVM-Networking.png)

### WebVM Network Settings

![WebVM](Screenshots/04-WebVM-Networking.png)

### Architecture Diagram

![Architecture](Screenshots/05-Azure-Network-Diagram.png)

---

## Skills Demonstrated

* Azure Virtual Network Design
* Subnet Planning and Segmentation
* Azure VM Deployment
* Network Security Groups
* Public and Private IP Management
* Cloud Infrastructure Administration
* Infrastructure Documentation
* GitHub Portfolio Development

---

## Resume Project Summary

Designed and deployed a segmented Azure Virtual Network with multiple subnets, deployed Windows Server virtual machines, configured network security controls, and documented cloud infrastructure architecture using GitHub.
