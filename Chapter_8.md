
# Chapter 8

## Server Types and Services
- Servers play roles such as print server, file server, database server, application server, backup server, web server, and mail server.
- A thin server is designed to support and run a specific function or role.
- Entry-level servers contain 1 to 8 processors, mid-range servers contain 9 to 30 processors, and high-end servers contain 31 to 106 processors.
- Servers often incorporate hot-swap technology for component replacement while running.

## Small Computer Systems Interface (SCSI)
- SCSI is a bus technology for connecting multiple devices to a single controller.
- Terms like Wide, Fast, Ultra, and combinations (e.g., Ultra/Wide) indicate data transfer capabilities.
- Each SCSI device must have a unique ID number.
- SCSI devices can extend outside the server through an extender card.
- Serial-attached SCSI uses a serial port similar to SATA.

## ACPI and ACPICA
- Automatic Configuration and Power Interface (ACPI) controls power options for computer hardware.
- ACPI lets users select power conservation settings.
- ACPI Component Architecture (ACPICA) extends the original ACPI standard for nonproprietary hardware configuration.

## System Resources
- Hardware-associated system resources include DMA, IRQ, I/O port address, and memory address assignment.
- Shared resource assignments can lead to system conflicts.

## RAID Systems
- RAID is a disk array system for speed, fault tolerance, or both.
- Common RAID levels are 0 (striping), 1 (mirroring), and 5 (striping with parity).
- RAID 0 increases speed without fault tolerance.
- RAID 1 mirrors two hard drives.
- RAID 5 combines speed with fault tolerance.

## External Storage Systems
- Network-attached storage (NAS) provides storage for a LAN and shares its bandwidth.
- Storage area network (SAN) is a dedicated network for data storage, not affecting other network bandwidths.

## Fibre Channel
- Fibre Channel is a high-speed access method, often using fiber-optic cable.
- Devices use a Network Address Authority (NAA) naming standard.
- Topologies include point-to-point and arbitrated loop, similar to token ring.
- InfiniBand is a high-throughput, low-latency network communication standard.

## Internet Small Computer Systems Interface
- iSCSI is an IP-based storage technology using IPv4 and IPv6 for storage device identification.
- Advantages of iSCSI include long-distance storage and cost-effectiveness compared to Fibre Channel SANs.
- iSCSI devices are identified using iSCSI-qualified names (IQNs) or Enterprise Unique Names (EUIs).

## Virtualization
- Virtualization creates a software-based environment.
- Benefits include cost reduction, server consolidation, resource utilization, security, disaster recovery, server provisioning, application isolation, and legacy application support.

## Hypervisor
- The hypervisor mechanism provides virtual servers with resource access.
