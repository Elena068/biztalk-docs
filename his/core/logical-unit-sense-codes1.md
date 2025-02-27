---
description: "Learn more about: Logical Unit Sense Codes"
title: "Logical Unit Sense Codes1"
ms.custom: ""
ms.date: "11/30/2017"
ms.prod: "host-integration-server"
ms.reviewer: ""
ms.suite: ""
ms.topic: "article"
---
# Logical Unit Sense Codes
This section lists the sense codes used by [!INCLUDE[hisHostIntServNoVersion](../includes/hishostintservnoversion-md.md)].  
  
 [!INCLUDE[hisHostIntServNoVersion](../includes/hishostintservnoversion-md.md)] sense codes are sent on either a negative response to an outbound data stream or an LUSTAT that notifies the host of a change in the secondary logical unit (LU) state. The sense codes generated by a 3270 emulator program are shown in the following tables.  
  
### Negative response sense codes  
  
|Value|Meaning|  
|-----------|-------------|  
|0802|Intervention required (LU 1/LU 3 printer soft error).|  
|0814|Bracket bid reject  RTR forthcoming.|  
|081B|Receiver in transmit mode.|  
|081C|Request not executable (hard error).|  
|0821|Invalid session parameters (negotiable BIND request).|  
|0829|Change direction required.|  
|082B|Presentation space integrity lost.|  
|082D|LU busy (usually local copy print in progress).|  
|082E|Intervention required (local copy print soft error).|  
|082F|Request not executable (local copy print hard error).|  
|0843|WCC print command bit not sent (RQD or RQE, CD, EB).|  
|0863|Referenced character set does not exist.|  
|0871|Read partition state error (SLU in retry state).|  
|1003|Function not supported.|  
|1005|Parameter modifying a control function is invalid.|  
|1007|Category not supported (SSCP data for host printer).|  
  
### LUSTAT sense codes  
  
|Value|Meaning|  
|-----------|-------------|  
|0001 B000|Host initialized local copy soft error recovery.|  
|081C 0000|Soft error changed to hard error (LU 1/LU 3).|  
|081C B000|Soft error changed to hard error (local copy).|  
|082B 0000|LU session changed from SSCP to PLU (SYSREQ).|
