# Week 3 – Day 6: Azure Monitoring and Backup

## Overview

This lab focused on monitoring and protecting the Azure virtual machine created earlier in Week 3. I used Azure Monitor to review VM performance and activity and configured Azure Backup to create a recovery point for the virtual machine.

## Lab Environment

| Resource                | Configuration                                |
| ----------------------- | -------------------------------------------- |
| Resource Group          | Homelab-RG                                   |
| Virtual Machine         | Homelab-VM01                                 |
| Operating System        | Windows Server 2025 Datacenter Azure Edition |
| Region                  | East US                                      |
| VNet                    | Homelab-VNet                                 |
| Subnet                  | Server-Subnet                                |
| Private IP              | 10.10.1.4                                    |
| Recovery Services Vault | Homelab-RecoveryVault                        |

## Tasks Completed

* Reviewed the Azure VM monitoring options.
* Reviewed CPU, network, and disk metrics.
* Enabled enhanced VM monitoring.
* Reviewed VM activity logs.
* Created a Recovery Services vault.
* Configured backup for Homelab-VM01.
* Ran a backup.
* Verified the backup status.
* Reviewed the available recovery point.

## Monitoring

Azure Monitor was used to review the performance and health information for Homelab-VM01.

The metrics reviewed included:

* CPU usage
* Network traffic
* Disk activity

## Backup

I created the `Homelab-RecoveryVault` Recovery Services vault and configured Azure Backup for `Homelab-VM01`.

The backup was completed successfully and a recovery point was available.

## Security and Reliability

Monitoring helps an administrator identify performance and operational problems. Backup provides a way to recover the virtual machine and its data after a failure or other problem.

Using both monitoring and backup improves the reliability of the environment.

## Lessons Learned

1. Azure Monitor can be used to review the performance of Azure virtual machines.
2. Platform metrics provide information such as CPU, network, and disk activity.
3. Enhanced monitoring provides additional information about the guest operating system.
4. Activity Logs help administrators review changes and management operations.
5. Azure Backup provides recovery points that can be used for VM recovery.
6. Monitoring and backup serve different purposes but are both important for system administration.

## Conclusion

This lab helped me understand how Azure administrators monitor virtual machines and protect them with backup. I was able to review VM performance information, examine activity logs, configure Azure Backup, and verify a recovery point.

## Errors Encountered

No errors were encountered during this lab.
