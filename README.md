# Project-Ironclad-SOHO-Lab
 CompTIA A+ Core 1 &amp; 2 Hands-On Infrastructure and Security Lab.
# Project 1: Enterprise SOHO Perimeter Firewall Deployment
**Asset Tag:** AN-IRONCLAD-GW01  
**Platform:** pfSense 2.7.0 OS on Type-2 Hypervisor (VirtualBox)

## Project Objective
To architect and configure an isolated perimeter gateway security topology for a small office/home office (SOHO) network environment, establishing clear segregation between a public WAN and a secure local zone (LAN).

## CompTIA A+ Core 1 & 2 Objectives Demonstrated
* **Domain 4.1 (Virtualization):** Provisioned a Type-2 hypervisor engine, configuring distinct memory allocation (1024MB RAM) and dynamic VDI storage constraints (16GB).
* **Domain 2.2 (SOHO Networks):** Configured dual-homed networking architecture mapping out public-facing WAN (Bridged to host controller) and private-facing LAN (Isolated internal segment).
* **Domain 1.2 (OS Installations):** Executed a full bare-metal Text User Interface (TUI) operating system installation, utilizing manual disk selection and target system file extractions.

## Real-World Troubleshooting Milestones Resolved
1. **FreeBSD Kernel Boot Error (Error 19):** Mitigated a storage controller mounting failure by updating the legacy virtual motherboard chipset configurations from PIIX3 to ICH9.
2. **Virtual Media Boot Loops:** Diagnosed and bypassed an infinite installer loop by executing a hard power cycle and manually unmounting the underlying bootable ISO image file using hypervisor device overrides.

## Current Network Status Verified
* **WAN Interface:** Active via DHCP (IPv4 & IPv6 resolution)
* **LAN Gateway IP:** Static 192.168.1.1/24 (Private Security Perimeter Active)
