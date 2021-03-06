---
UID: NF:ntintsafe.RtlULongLongToUIntPtr
title: RtlULongLongToUIntPtr function
author: windows-driver-content
description: Converts a value of type ULONGLONG to a value of type UINT_PTR.
old-location: kernel\rtlulonglongtouintptr.htm
tech.root: kernel
ms.assetid: A6B49838-11DE-4860-9D4C-D55D21C54157
ms.author: windowsdriverdev
ms.date: 4/30/2018
ms.keywords: RtlULongLongToUIntPtr, RtlULongLongToUIntPtr function [Kernel-Mode Driver Architecture], kernel.rtlulonglongtouintptr, ntintsafe/RtlULongLongToUIntPtr
ms.prod: windows-hardware
ms.technology: windows-devices
ms.topic: function
req.header: ntintsafe.h
req.include-header: 
req.target-type: Desktop
req.target-min-winverclnt: 
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
-	Ntintsafe.h
api_name:
-	RtlULongLongToUIntPtr
product:
- Windows
targetos: Windows
req.typenames: 
---

# RtlULongLongToUIntPtr function


## -description


Converts a value of type <b>ULONGLONG</b> to a value of type <b>UINT_PTR</b>.


## -parameters




### -param ullOperand [in]

The value to be converted.


### -param puResult [out]

A pointer to the converted value. In the case where the conversion causes a truncation of the original value, the function returns STATUS_INTEGER_OVERFLOW and this parameter is not valid.


## -remarks



This is one of a set of inline functions designed to provide type conversions and perform validity checks with minimal impact on performance.



