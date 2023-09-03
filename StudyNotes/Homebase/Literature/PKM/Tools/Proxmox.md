---
Aliases: PROXMOX, Proxmox
---
#PKC 

[[Proxmox]] is an open-source server virtualization management platform that allows users to manage and deploy virtual machines (VMs) and containers. It is based on Debian Linux and provides a web-based interface for easy management of the virtualization infrastructure.

Proxmox can be integrated with [[Network Attached Storage|Network-Attached Storage]] (NAS) devices to store and manage VM images, backups, and other data. NAS systems provide centralized storage that can be accessed by multiple Proxmox hosts, allowing for better scalability and flexibility. Proxmox supports various NAS protocols such as NFS (Network File System), CIFS (Common Internet File System), and iSCSI (Internet Small Computer System Interface).

## Can Proxmox run in Nix OS

Yes, Proxmox can run on [[NixOS|NixOS]]. NixOS is a Linux distribution known for its declarative and reproducible approach to system configuration. Proxmox can be installed on top of NixOS using virtualization technologies such as KVM (Kernel-based Virtual Machine) or QEMU (Quick Emulator). By setting up the necessary virtualization components and dependencies, Proxmox can be successfully deployed and used within a NixOS environment.

## Can Nix OS run in Proxmox

Yes, NixOS can run in Proxmox. Proxmox is a virtualization platform that supports various operating systems, including Linux distributions like NixOS. You can create a new virtual machine in Proxmox and install NixOS on it just like any other guest operating system.
# Conclusion
Overall, Proxmox provides a comprehensive solution for managing virtual machines and containers in a data center or cloud environment. Its integration with NAS systems enhances storage capabilities while PKC enables efficient resource utilization through lightweight containerization.