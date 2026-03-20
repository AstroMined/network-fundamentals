
# Chapter 7

## Brief History of Microsoft Network Operating Systems
- The first network operating system from Microsoft was Windows for Workgroups and Windows NT 3.1, released in 1993.
- Computers in a Microsoft peer-to-peer network are grouped as workgroups.
- A workgroup is a group of computers that share resources.
- Computers in a Microsoft client/server network are grouped together in a domain.
- A domain is a logical grouping of users and equipment as defined by the network administrator.

## Windows Server 2016
- Windows Server 2016 is Microsoft’s latest server operating system.
- Three different editions of Windows Server 2016 include Standard, Datacenter, and Essentials.
- Features included in Windows Server 2016 are BranchCache, DirectAccess, Failover Cluster, Hyper-V, Internet Information Service, Network Access Protection, Remote Access, Server Core, and Nano Server.
- Failover cluster is the name Microsoft uses to refer to what other vendors generally call a server cluster, which is a group of individual servers connected both physically and logically to ensure constant service to clients.

## Common Windows Server Administrative Components
- A domain is a logical grouping of users and equipment as defined by the network administrator; a workgroup is a group of computers that share resources such as files and hardware; and a HomeGroup is a group of computers on a residential network that can share files and printers. HomeGroup membership is optional, whereas membership to a workgroup or domain is not.
- Group accounts are collections of users that typically share a common job-oriented goal or similar function.
- Security policies are set before users are added to the network. Two types of security policies are local and global policies.
- Windows native file-sharing protocol is Server Message Block (SMB).
- The New Technology File System (NTFS) is the native file format for Windows NT and Windows Server operating systems.
- The NTFS file system is an improvement over FAT16 and FAT32.
- NTFS can create partition sizes as large as 16 EB. NTFS file names can be as long as 255 characters and have multiple extensions.
- FAT16 is limited to a 2-GB partition and to an eight-character file name with a three-character extension.
- FAT32 is limited to a 32-GB partition.
- Dynamic disk is an improved version of NTFS and is referred to as NTFS 5.0.

## Network Shares
- Network shares have assigned permissions, such as Full Control, Modify, Read, and Write.
- Administrative shares are indicated by a dollar sign symbol.

## Active Directory Domain Services
- Active Directory uses LDAP and HTTP to transfer information between domain controllers.
- The Active Directory structure consists of trees, forests, organizational units, and objects.
- A tree is a collection of domains that have a contiguous namespace and share a common Active Directory database.
- A forest is a collection of domains that have a disjointed namespace and share a common Active Directory database.
- An organizational unit is a container that holds objects or other organizational units and serves to organize a network into manageable units.
- The two processes that handle authentication in a Windows network are interactive logon and network authentication.
- Windows Server networks use the Kerberos protocol for authentication.
- A Windows 2000–2016 server can support one of three roles: domain controller (DC), member server, and stand-alone server.
- Windows Server 2000–2016 supports multimaster replication.
- A trust relationship between Windows domains allows the free flow of data and communication between domains. Forests can also form trust relationships with other forests.

## Windows Server Administration
- The Microsoft Management Console (MMC) is a utility used to organize commonly used utilities.
- The Active Directory Users and Computers utility is used to add user and group accounts to a Windows domain.

## POSIX
- A POSIX-compliant operating system can run on numerous hardware platforms.

## Network Interoperability
- A gateway service provides communication between dissimilar network systems.
- A gateway is also the device used to provide a connection between the local area network and the Internet.
