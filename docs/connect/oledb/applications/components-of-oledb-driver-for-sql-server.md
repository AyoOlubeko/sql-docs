---
title: "Components of OLE DB Driver for SQL Server | Microsoft Docs"
description: "Components of OLE DB Driver for SQL Server"
ms.custom: ""
ms.date: "03/26/2018"
ms.prod: "sql-non-specified"
ms.prod_service: "database-engine, sql-database, sql-data-warehouse, pdw"
ms.service: ""
ms.component: "oledb|applications"
ms.reviewer: ""
ms.suite: "sql"
ms.technology:
  - "drivers"
ms.tgt_pltfrm: ""
ms.topic: "reference"
helpviewer_keywords:
  - "data access [OLE DB Driver for SQL Server], components"
  - "components [OLE DB Driver for SQL Server]"
  - "MSOLEDBSQL, about OLE DB Driver for SQL Server"
author: "pmasl"
ms.author: "Pedro.Lopes"
manager: "jhubbard"
ms.workload: "Inactive"
---
# Components of OLE DB Driver for SQL Server
[!INCLUDE[appliesto-ss-asdb-asdw-pdw-md](../../../includes/appliesto-ss-asdb-asdw-pdw-md.md)]

[!INCLUDE[Driver_OLEDB_Download](../../../includes/driver_oledb_download.md)]

  OLE DB Driver for SQL Server contains the following components:  

|Component|Description|  
|---------------|-----------------|  
|msoledbsql.dll|The dynamic-link library (DLL) file that contains all of the OLE DB Driver for SQL Server functionality.|  
|msoledbsqlr.rll|The accompanying resource file for the OLE DB Driver for SQL Server library.|   
|msoledbsql.h|The OLE DB Driver for SQL Server header file that contains all of the new definitions needed in order to use OLE DB Driver for SQL Server. This header file replaces the sqloledb.h header file.<br /><br /> Note: You can reference msoledbsql.h and sqloledb.h in same program as long as sqloledb.h is defined first.|  
|msoledbsql.lib|The library file needed to directly call the **bcp** utility functions that are part of the OLE DB Driver for SQL Server.<br /><br /> Note: If you do reference the msoledbsql.lib file in your programming code, you need to make sure that the msoledbsql.dll file is in your system path, and in the system path of the users that make use of your application.|  

## See Also  
 [Building Applications with OLE DB Driver for SQL Server](../../oledb/applications/building-applications-with-oledb-driver-for-sql-server.md)  