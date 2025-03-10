---
description: "Learn more about: A failure occurred in processing X12 message on send port: No agreement for receiver and sender identifier-qualifier pairs"
title: "A failure occurred in processing X12 message on send port: No agreement for receiver and sender identifier-qualifier pairs"
ms.custom: ""
ms.date: "06/08/2017"
ms.prod: "biztalk-server"
ms.reviewer: ""
ms.suite: ""
ms.topic: "article"
---
# A failure occurred in processing X12 message on send port: No agreement for receiver and sender identifier-qualifier pairs
## Details  
  
| Field | Error Details |
|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  Product Name   |                                      [!INCLUDE[btsBizTalkServerNoVersion](../includes/btsbiztalkservernoversion-md.md)]                                       |
| Product Version |                                                  [!INCLUDE[btsEDIVersion](../includes/btsediversion-md.md)]                                                   |
|    Event ID     |                                                                               -                                                                               |
|  Event Source   |                                    [!INCLUDE[btsBizTalkServerNoVersion](../includes/btsbiztalkservernoversion-md.md)] EDI                                     |
|    Component    |                                                                          EDI Engine                                                                           |
|  Symbolic Name  |                                                                               -                                                                               |
|  Message Text   | A failure occurred in processing X12 message on send port {0}. No agreement exists for receiver and sender identifier/qualifier pairs for {1}, {2}, {3}, {4}. |
  
## Explanation  
 This Error/Warning/Information event indicates BizTalk Server was unable to resolve the party for the EDIFACT interchange because BizTalk Server was unable to match promoted sender qualifier and identifier properties, and promoted receiver qualifier and identifier properties, with the corresponding values for a party.  
  
## User Action  
 To resolve this error, ensure that the sender qualifier and identifier (ISA5 and ISA6) and receiver qualifier and identifier (ISA7 and ISA8) defined in the party's ISA Segment Definition page of the EDI Properties dialog box match the corresponding promoted properties in the context of the interchange.
