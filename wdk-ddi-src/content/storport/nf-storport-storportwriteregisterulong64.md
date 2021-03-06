---
UID: NF:storport.StorPortWriteRegisterUlong64
title: StorPortWriteRegisterUlong64 macro
author: windows-driver-content
description: This StorPortWriteRegisterUlong64 routine writes a ULONG64 value to the specified register address.
old-location: storage\storportwriteregisterulong64.htm
tech.root: storage
ms.assetid: FFBC7A27-B980-49AF-9207-237E0F0292FA
ms.author: windowsdriverdev
ms.date: 3/29/2018
ms.keywords: StorPortWriteRegisterUlong64, StorPortWriteRegisterUlong64 routine [Storage Devices], storage.storportwriteregisterulong64, storport/StorPortWriteRegisterUlong64
ms.prod: windows-hardware
ms.technology: windows-devices
ms.topic: macro
req.header: storport.h
req.include-header: Storport.h
req.target-type: Universal
req.target-min-winverclnt: Available starting with Windows 8.
req.target-min-winversvr: 
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
-	storport.h
api_name:
-	StorPortWriteRegisterUlong64
product:
- Windows
targetos: Windows
req.typenames: 
---

# StorPortWriteRegisterUlong64 macro


## -description


This <b>StorPortWriteRegisterUlong64</b> routine writes a <b>ULONG64</b> value to the specified register address.


## -parameters




### -param h

<p>Pointer to the register where the data is written to. The register must be a mapped range in memory space</p>


### -param r

<p>A <b>ULONG64</b> value to write to the register.</p>


### -param v

TBD






#### - Register [in]

Pointer to the register where the data is written to. The register must be a mapped range in memory space


#### - Value [in]

A <b>ULONG64</b> value to write to the register.


## -remarks



The <b>StorPortWriteRegisterUlong64</b> routine is only available on the 64-bit version of Windows.




## -see-also




<a href="https://msdn.microsoft.com/library/windows/hardware/hh967741">StorPortReadRegisterUlong64</a>
 

 

