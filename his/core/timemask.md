---
description: "Learn more about: timeMask"
title: "timeMask"
ms.custom: ""
ms.date: "11/30/2017"
ms.prod: "host-integration-server"
ms.reviewer: ""
ms.suite: ""
ms.topic: "article"
---
# timeMask
The timeMask element contains a db2ToSql or sqlToDb2 to indicate the direction, and a sourceFormat and a targetFormat to specify the mapping.  
  
 \<hostIntegration.drdaAs.drdaService>  
\<services>  
\<service>  
\<conversionFormats>  
\<timeMasks>  
  
## Syntax  
  
```  
<hostIntegration.drdaAs.drdaService>        <services>                <service>                        <conversionFormats>                                <timeMasks>                                        <timeMask>                                        </timeMask>                                </timeMasks>                        </conversionFormats>                </service>        </services></hostIntegration.drdaAs.drdaService>  
```  
  
## Attributes and Elements  
 The following sections describe attributes, child elements, and parent elements.  
  
### Attributes  
 None  
  
### Child Elements  
  
|Element|Description|Occurrence Constraint|  
|-------------|-----------------|---------------------------|  
||The db2ToSql defines the direction from DB2 to SQL Server.|1|  
||The sqlToDb2 defines the direction from SQL Server to DB2.|1|  
  
### Parent Elements  
  
|Element|Description|  
|-------------|-----------------|  
||The DRDA Service will process string literal time values within DB2 and SQL Server TIME, CHAR (8), and VARCHAR (8) data types, to convert from DB2 time format to SQL Server time format, and to convert from SQL Server time format to DB2 time format. The timeMasks contains one or more timeMask elements to define time mappings.|
