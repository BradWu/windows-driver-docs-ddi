---
UID: NF:netrequest.NetRequestWdmGetNdisOidRequest
title: NetRequestWdmGetNdisOidRequest function
author: windows-driver-content
description: Retrieves the traditional WDM NDIS_OID_REQUEST structure for the NETREQUEST.
ms.assetid: 12b97789-3b90-475a-ac7c-cb4a08e9dea3
ms.author: windowsdriverdev
ms.date: 02/08/2018
ms.topic: function
ms.keywords: NetRequestWdmGetNdisOidRequest
req.header: netrequest.h
req.include-header: netadaptercx.h
req.target-type: Universal
req.target-min-winverclnt:
req.target-min-winversvr:
req.kmdf-ver: 1.21
req.umdf-ver:
req.lib:
req.dll:
req.irql: <= DISPATCH_LEVEL
req.ddi-compliance:
req.unicode-ansi:
req.idl:
req.max-support:
req.namespace:
req.assembly:
req.type-library: 
req.alt-api:
req.alt-loc:
topictype: 
-	apiref
apitype: 
-	HeaderDef
apilocation: 
-	netrequest.h
apiname: 
-	NetRequestWdmGetNdisOidRequest
product:
-	Windows
targetos: Windows
product:
- Windows
---

# NetRequestWdmGetNdisOidRequest function


## -description

> [!WARNING]
> Some information in this topic relates to prereleased product, which may be substantially modified before it's commercially released. Microsoft makes no warranties, express or implied, with respect to the information provided here.
>
> NetAdapterCx is preview only in Windows 10, version 1809.

Retrieves the traditional WDM [NDIS_OID_REQUEST](../ndis/ns-ndis-_ndis_oid_request.md) structure for the NETREQUEST.

## -parameters

### -param Request
A handle to a network request object.

## -returns
A pointer to the [NDIS_OID_REQUEST](../ndis/ns-ndis-_ndis_oid_request.md) structure.

## -remarks


## -see-also