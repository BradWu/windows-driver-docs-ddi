---
UID: NF:netadapter.NetAdapterSetCurrentLinkState
title: NetAdapterSetCurrentLinkState function
author: windows-driver-content
description: Sets the current link state of the of the network adapter.
ms.assetid: 5c06c275-4eb8-46ba-9b90-50ca192c9a47
ms.author: windowsdriverdev
ms.date: 02/06/2018
ms.topic: function
ms.keywords: NetAdapterSetCurrentLinkState
req.header: netadapter.h
req.include-header: netadaptercx.h
req.target-type: Universal
req.target-min-winverclnt:
req.target-min-winversvr:
req.kmdf-ver: 1.21
req.umdf-ver:
req.lib:
req.dll:
req.irql: "<= DISPATCH_LEVEL"
req.ddi-compliance:
req.unicode-ansi:
req.idl:
req.max-support:
req.namespace:
req.assembly:
req.type-library: 
req.alt-api:
req.alt-loc:
req.typenames: NetAdapterSetCurrentLinkState
topictype: 
-	apiref
apitype: 
-	HeaderDef
apilocation: 
-	netadapter.h
apiname: 
-	NetAdapterSetCurrentLinkState
product:
-	Windows
targetos: Windows
product:
- Windows
---

# NetAdapterSetCurrentLinkState function


## -description

> [!WARNING]
> Some information in this topic relates to prereleased product, which may be substantially modified before it's commercially released. Microsoft makes no warranties, express or implied, with respect to the information provided here.
>
> NetAdapterCx is preview only in Windows 10, version 1809.

Sets the current link state of the of the network adapter.

## -parameters

### -param Adapter
The network adapter object that the client created in a prior call to [**NetAdapterCreate**](nf-netadapter-netadaptercreate.md).

### -param CurrentLinkState
A pointer to an allocated and initialized [**NET_ADAPTER_LINK_STATE**](ns-netadapter-_net_adapter_link_state.md) structure that describes the current link state of the adapter.

## -returns
This method does not return a value.

## -remarks
The client driver calls **NetAdapterSetCurrentLinkState** when starting a net adapter, before it calls [**NetAdapterStart**](nf-netadapter-netadapterstart.md). It can also call this method later when it needs to change the current link state.



## -see-also

[**NET_ADAPTER_LINK_STATE_INIT**](nf-netadapter-net_adapter_link_state_init.md)

[**NET_ADAPTER_LINK_STATE_INIT_DISCONNECTED**](nf-netadapter-net_adapter_link_state_init_disconnected.md)