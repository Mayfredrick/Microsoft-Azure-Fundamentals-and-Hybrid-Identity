# Week 3 – Day 5: Azure Network Security Groups

## Project Overview

The objective of this lab was to create and configure an Azure Network Security Group (NSG). During the lab, I learned how NSGs control network traffic by using inbound and outbound security rules. I also associated the NSG with the Azure network environment and tested the rules by connecting to the virtual machine using Remote Desktop Protocol (RDP).

---

## Network Security Group

Name: Homelab-NSG

Region: East US

Associated Resource: Homelab-VNet

---

## Default Security Rules

### Inbound Rules

| Rule                  | Protocol | Source            | Destination    | Action |
| --------------------- | -------- | ----------------- | -------------- | ------ |
| AllowVnetInBound      | Any      | VirtualNetwork    | VirtualNetwork | Allow  |
| AllowAzureLoadBalance | Any      | AzureLoadBalancer | Any            | Allow  |
| DenyAllInbound        | Any      | Any               | Any            | Deny   |

### Outbound Rules

| Rule                  | Protocol | Source         | Destination    | Action |
| --------------------- | -------- | -------------- | -------------- | ------ |
| AllowVnetOutBound     | Any      | VirtualNetwork | VirtualNetwork | Allow  |
| AllowInternetOutBound | Any      | Any            | Internet       | Allow  |
| DenyAllOutBound       | Any      | Any            | Any            | Deny   |

These default rules provide the basic traffic controls for the network security group.

---

## Custom Security Rule

Rule Name: Allow-RDP

Port: 3389

Protocol: TCP

Source: Any

Destination: Any

Action: Allow

This rule allows Remote Desktop Protocol traffic to reach the virtual machine.

 Security Note: Allowing RDP from any source is suitable for this controlled lab environment, but in a production environment, access should be restricted to trusted source IP addresses or managed through a more secure remote-access solution.

---

## Connectivity Test

The connectivity test was completed successfully.

 RDP connection succeeded.
 The virtual machine remained accessible.
 No connectivity problems were encountered.

---

## Lessons Learned

This lab helped me understand how Network Security Groups control network traffic in Azure. I learned how inbound and outbound rules determine which traffic is allowed or denied. I also learned how an NSG can be associated with Azure networking resources and how security rules can be used to control access to virtual machines.

---

## Conclusion

The lab was completed successfully without any errors. I created the Homelab-NSG, reviewed the default security rules, configured an RDP rule, and successfully connected to the Azure virtual machine. This lab improved my understanding of basic network security controls in Microsoft Azure.
