---
UID: NC:d3d12umddi.PFND3D12DDI_DESTROY_METACOMMAND
title: PFND3D12DDI_DESTROY_METACOMMAND
author: windows-driver-content
description: Destroys the meta-command.
ms.assetid: 0bd395c4-a428-4db7-8ebc-43f1a8474506
ms.author: windowsdriverdev
ms.date:
ms.topic: callback
ms.prod: windows-hardware
ms.technology: windows-devices
req.header: d3d12umddi.h
req.include-header:
req.target-type:
req.target-min-winverclnt:
req.target-min-winversvr:
req.kmdf-ver:
req.umdf-ver:
req.lib:
req.dll:
req.irql:
req.ddi-compliance:
req.unicode-ansi:
req.idl:
req.max-support:
req.namespace:
req.assembly:
req.type-library:
topic_type:
-	apiref
api_type:
-	UserDefined
api_location:
-	d3d12umddi.h
api_name:
-	PFND3D12DDI_DESTROY_METACOMMAND
product: 
- Windows
targetos: Windows
tech.root: display
---

# PFND3D12DDI_DESTROY_METACOMMAND callback function

## -description

Implemented by the client driver to remove meta-command resources.

## -prototype

```
//Declaration

PFND3D12DDI_DESTROY_METACOMMAND Pfnd3d12ddiDestroyMetacommand;

// Definition

VOID Pfnd3d12ddiDestroyMetacommand
(
	 D3D12DDI_HDEVICE
	 D3D12DDI_HMETACOMMAND
)
{...}

PFND3D12DDI_DESTROY_METACOMMAND


```

## -parameters

### -param D3D12DDI_HDEVICE

A handle to the display device (graphics context).

### -param D3D12DDI_HMETACOMMAND:

A handle to a meta-command.

## -returns

This callback function does not return a value.


## -see-also