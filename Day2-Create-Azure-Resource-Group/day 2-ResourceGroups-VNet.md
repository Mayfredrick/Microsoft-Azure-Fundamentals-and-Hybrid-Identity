# Week 3 – Day 2: Azure Resource Groups and Virtual Networks

## Project Overview

The objective of today's lab was to create and manage Azure Resource Groups and Virtual Networks. During this lab, I learned how Azure organizes resources, how to create a virtual network and subnet, and how these components provide secure communication between Azure resources.

## Resource Group
Name: Homelab-RG
Region: East US
Purpose:
A Resource Group is a logical container that holds related Azure resources for a specific project or solution. It allows administrators to organize, monitor, and manage resources from a central location throughout their lifecycle.

## Virtual Network
Name: Homelab-VNet
Address Space: 10.10.0.0/16
Purpose:
The Virtual Network (VNet) provides a private network for Azure resources to communicate securely with one another. It functions similarly to a traditional network in an on-premises environment while allowing Azure resources to connect securely.

## Subnet
Name: Server-Subnet
Address Range: 10.10.1.0/24
Purpose:
A subnet divides a virtual network into smaller network segments. This makes it easier to organize resources, improve security, and apply different network policies to different groups of resources.

## Lessons Learned
During this lab, I learned how Azure uses Resource Groups to organize cloud resources and how Virtual Networks provide secure communication between Azure services. I also learned how subnets help separate resources into logical network segments, making the environment easier to manage and secure.

## Conclusion
This lab provided a practical introduction to Azure networking. I successfully created a Resource Group, a Virtual Network, and a subnet while gaining a better understanding of how Azure organizes and manages cloud resources. These concepts provide the foundation for deploying Azure Virtual Machines and other cloud services in future labs.
