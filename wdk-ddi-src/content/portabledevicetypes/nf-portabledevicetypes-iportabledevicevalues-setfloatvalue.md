---
UID: NF:portabledevicetypes.IPortableDeviceValues.SetFloatValue
title: IPortableDeviceValues::SetFloatValue
author: windows-driver-content
description: Adds a new FLOAT value (type VT_R4) or overwrites an existing one.
old-location: wpddk\iportabledevicevalues_setfloatvalue.htm
tech.root: wpd_dk
ms.assetid: 60e4ce74-5d8e-49d4-af16-84ea66557b60
ms.author: windowsdriverdev
ms.date: 2/15/2018
ms.keywords: IPortableDeviceValues interface,SetFloatValue method, IPortableDeviceValues.SetFloatValue, IPortableDeviceValues::SetFloatValue, IPortableDeviceValuesSetFloatValue, SetFloatValue, SetFloatValue method, SetFloatValue method,IPortableDeviceValues interface, portabledevicetypes/IPortableDeviceValues::SetFloatValue, wpddk.iportabledevicevalues_setfloatvalue
ms.prod: windows-hardware
ms.technology: windows-devices
ms.topic: method
req.header: portabledevicetypes.h
req.include-header: 
req.target-type: Windows
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
-	COM
api_location:
-	PortableDeviceTypes.h
api_name:
-	IPortableDeviceValues.SetFloatValue
product: Windows
targetos: Windows
req.typenames: 
---

# IPortableDeviceValues::SetFloatValue


## -description



Adds a new <b>FLOAT</b> value (type VT_R4) or overwrites an existing one.




## -parameters




### -param key [in]

A <b>REFPROPERTYKEY</b> that specifies the item to create or overwrite.


### -param Value [in]

A <b>FLOAT</b> that contains the new value.


## -returns



The method returns an <b>HRESULT</b>. Possible values include, but are not limited to, those in the following table.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
The method succeeded.

</td>
</tr>
</table>
 




## -remarks



If an existing value has the same key that is specified by the <i>key</i> parameter, it overwrites the existing value without any warning.




## -see-also




<a href="https://msdn.microsoft.com/4a97301a-12cc-442f-a080-446ec9e1e245">IPortableDeviceValues Interface</a>



<a href="https://msdn.microsoft.com/f281c407-7d1c-48e8-ab5e-c18bf0c080e0">IPortableDeviceValues::GetFloatValue</a>
 

 
