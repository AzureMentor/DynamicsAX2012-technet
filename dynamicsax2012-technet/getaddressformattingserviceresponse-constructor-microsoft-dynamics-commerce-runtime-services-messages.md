﻿---
title: GetAddressFormattingServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetAddressFormattingServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressFormattingServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormattingInfo})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getaddressformattingserviceresponse.getaddressformattingserviceresponse(v=AX.60)
ms:contentKeyID: 62210173
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressFormattingServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetAddressFormattingServiceResponse Constructor

Initializes a new instance of the [GetAddressFormattingServiceResponse](getaddressformattingserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    formatLines As IEnumerable(Of AddressFormattingInfo) _
)
'Usage
Dim formatLines As IEnumerable(Of AddressFormattingInfo)

Dim instance As New GetAddressFormattingServiceResponse(formatLines)
```

``` csharp
public GetAddressFormattingServiceResponse(
    IEnumerable<AddressFormattingInfo> formatLines
)
```

``` c++
public:
GetAddressFormattingServiceResponse(
    IEnumerable<AddressFormattingInfo^>^ formatLines
)
```

#### Parameters

  - formatLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[AddressFormattingInfo](addressformattinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetAddressFormattingServiceResponse Class](getaddressformattingserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)
