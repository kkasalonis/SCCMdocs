---
title: "SMS_InventoryReportClass Class | Microsoft Docs"
ms.custom: ""
ms.date: "09/20/2016"
ms.prod: "configuration-manager"
ms.reviewer: ""
ms.suite: ""
ms.technology:
  - "configmgr-other"
ms.tgt_pltfrm: ""
ms.topic: "article"
applies_to:
  - "System Center Configuration Manager (current branch)"
ms.assetid: c49d5284-56e0-46ae-9c3d-e29d677dcffc
caps.latest.revision: 6
author: "shill-ms"
ms.author: "v-suhill"
manager: "mbaldwin"
---
# SMS_InventoryReportClass Server WMI Class
The `SMS_InventoryReportClass` Windows Management Instrumentation (WMI) class is an SMS Provider server class embedded in `SMS_InventoryReport` that represents the classes that are enabled to be collected in this inventory report.  

 The following syntax is simplified from Managed Object Format (MOF) code and includes all inherited properties.  

## Syntax  

```  
Class SMS_InventoryReportClass :    
{  
    String Filter;  
    String ReportProperties[];  
    String SMSClassID;  
    UInt32 Timeout;  
};  
```  

## Methods  
 The `SMS_InventoryReportClass` class does not define any methods.  

## Properties  
 `Filter`  
 Data type: `String`  

 Access type: Read/Write  

 Qualifiers: none  

 Reserved for future use.  

 `ReportProperties`  
 Data type: `String Array`  

 Access type: Read/Write  

 Qualifiers: none  

 The property name in this class to collect.  

 `SMSClassID`  
 Data type: `String`  

 Access type: Read/Write  

 Qualifiers: [key]  

 The class id that uniquely identifies this class.  

 `Timeout`  
 Data type: `UInt32`  

 Access type: Read/Write  

 Qualifiers: [not_null]  

 The timeout for the query.  

## Remarks  

## Requirements  

## Runtime Requirements  
 For more information, see [Configuration Manager Server Runtime Requirements](../../../../../develop/core/reqs/server-runtime-requirements.md).  

## Development Requirements  
 For more information, see [Configuration Manager Server Development Requirements](../../../../../develop/core/reqs/server-development-requirements.md).
