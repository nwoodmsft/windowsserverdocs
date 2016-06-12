---
title: Designing the Site Topology
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.service: active-directory
ms.suite: na
ms.technology: 
  - active-directory-domain-services
ms.tgt_pltfrm: na
ms.assetid: e3a6521b-ad89-44b6-a998-c23a923b2689
author: Femila
---
# Designing the Site Topology
A directory service site topology is a logical representation of your physical network. Designing a site topology for Active Directory Domain Services \(AD DS\) involves planning for domain controller placement and designing sites, subnets, site links, and site link bridges to ensure efficient routing of query and replication traffic.  
  
Designing a site topology helps you efficiently route client queries and Active Directory replication traffic. A well\-designed site topology helps your organization achieve the following benefits:  
  
-   Minimize the cost of replicating Active Directory data.  
  
-   Minimize administrative efforts that are required to maintain the site topology.  
  
-   Schedule replication that enables locations with slow or dial\-up network links to replicate Active Directory data during off\-peak hours.  
  
-   Optimize the ability of client computers to locate the nearest resources, such as domain controllers and Distributed File System \(DFS\) servers. This helps to reduce network traffic over slow wide area network \(WAN\) links, improve logon and logoff processes, and speed up file download operations.  
  
Before you begin to design your site topology, you must understand your physical network structure. In addition, you must first design your Active Directory logical structure, including the administrative hierarchy, forest plan, and domain plan for each forest. You must also complete your Domain Name System \(DNS\) infrastructure design for AD DS. For more information about designing your Active Directory logical structure and DNS infrastructure, see [Designing the Logical Structure for Windows Server 2008 AD DS](Designing-the-Logical-Structure-for-Windows-Server-2008-AD-DS.md).  
  
After you complete your site topology design, you must verify that your domain controllers meet the hardware requirements for  Windows Server 2008 Standard ,  Windows Server 2008 Enterprise , and  Windows Server 2008 Datacenter .  
  
## In this guide  
  
-   [Understanding Active Directory Site Topology](../../active-directory-domain-services/plan/Understanding-Active-Directory-Site-Topology.md)  
  
-   [Collecting Network Information](../../active-directory-domain-services/plan/Collecting-Network-Information.md)  
  
-   [Planning Domain Controller Placement](../../active-directory-domain-services/plan/Planning-Domain-Controller-Placement.md)  
  
-   [Creating a Site Design](../../active-directory-domain-services/plan/Creating-a-Site-Design.md)  
  
-   [Creating a Site Link Design](../../active-directory-domain-services/plan/Creating-a-Site-Link-Design.md)  
  
-   [Creating a Site Link Bridge Design](../../active-directory-domain-services/plan/Creating-a-Site-Link-Bridge-Design.md)  
  
-   [Finding Additional Resources for Windows Server 2008 Active Directory Site Topology Design](../../active-directory-domain-services/plan/Finding-Additional-Resources-for-Windows-Server-2008-Active-Directory-Site-Topology-Design.md)  
  
