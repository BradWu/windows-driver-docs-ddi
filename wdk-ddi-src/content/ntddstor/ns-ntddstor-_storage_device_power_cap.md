---
UID: NS:ntddstor._STORAGE_DEVICE_POWER_CAP
title: "_STORAGE_DEVICE_POWER_CAP"
author: windows-driver-content
description: This structure is used as an input and output buffer for the IOCTL_STORAGE_DEVICE_POWER_CAP.
old-location: storage\storage_device_power_cap.htm
tech.root: storage
ms.assetid: B13D311F-FFC4-4A40-AF0C-6E7115174FD1
ms.author: windowsdriverdev
ms.date: 3/29/2018
ms.keywords: "*PSTORAGE_DEVICE_POWER_CAP, PSTORAGE_DEVICE_POWER_CAP, PSTORAGE_DEVICE_POWER_CAP structure pointer [Storage Devices], STORAGE_DEVICE_POWER_CAP, STORAGE_DEVICE_POWER_CAP structure [Storage Devices], _STORAGE_DEVICE_POWER_CAP, ntddstor/PSTORAGE_DEVICE_POWER_CAP, ntddstor/STORAGE_DEVICE_POWER_CAP, storage.storage_device_power_cap"
ms.prod: windows-hardware
ms.technology: windows-devices
ms.topic: struct
req.header: ntddstor.h
req.include-header: Ntddstor.h
req.target-type: Windows
req.target-min-winverclnt: Windows 10
req.target-min-winversvr: Windows Server 2016
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
-	APIRef
-	kbSyntax
api_type:
-	HeaderDef
api_location:
-	ntddstor.h
api_name:
-	STORAGE_DEVICE_POWER_CAP
product:
- Windows
targetos: Windows
req.typenames: STORAGE_DEVICE_POWER_CAP, *PSTORAGE_DEVICE_POWER_CAP
---

# _STORAGE_DEVICE_POWER_CAP structure


## -description


This structure is used as an input and output buffer for the <a href="https://msdn.microsoft.com/library/windows/hardware/dn932064">IOCTL_STORAGE_DEVICE_POWER_CAP</a>.


## -struct-fields




### -field Version

The version of this structure. This should be set to STORAGE_DEVICE_POWER_CAP_VERSION_V1.


### -field Size

The size of this structure.


### -field Units

The units of the MaxPower value.


### -field MaxPower

Contains the value of the actual maximum power consumption level of the device. This may be equal to, less than, or greater than the desired threshold, depending on what the device supports.

