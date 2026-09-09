# Week 3 – Day 3: Azure Virtual Machine

## Project Overview

The objective of this lab was to deploy and manage a Windows Server virtual machine in Microsoft Azure. During the lab, I created a virtual machine, configured its network settings, connected to it using Remote Desktop Protocol (RDP), and verified that it was operating correctly. This exercise provided practical experience with deploying and managing cloudbased virtual machines.

## Virtual Machine Configuration

Resource Group: HomelabRG

Virtual Machine Name: Homelab-VM01

Operating System: Microsoft Windows Server 2025 Datacenter: Azure Edition

Region: East US

VM Size: Standard_D2as_v7 (2 vCPUs, 8 GiB memory)

OS Disk Size: 127 GB

## Network Configuration

Virtual Network: Homelab-VNet

Subnet: ServerSubnet (10.10.1.0/24)

Private IP Address: 10.10.1.4

## Virtual Machine Management

The following management tasks were completed successfully:
 Started the virtual machine.
 Stopped (deallocated) the virtual machine.
 Restarted the virtual machine.
 Verified that the virtual machine returned to a running state after each operation.

## Lessons Learned

This lab helped me understand the process of deploying and managing an Azure Virtual Machine. I learned how to configure networking, connect to a virtual machine using Remote Desktop, and perform basic management tasks such as starting, stopping, and restarting the virtual machine. I also gained a better understanding of how Azure integrates compute and networking resources to provide a secure and flexible cloud environment.

## Conclusion

The lab was completed successfully without any issues. I deployed a Windows Server virtual machine, connected to it using Remote Desktop, and verified that all management tasks worked as expected. This lab strengthened my understanding of Azure Virtual Machines and prepared me for more advanced Azure administration tasks.
