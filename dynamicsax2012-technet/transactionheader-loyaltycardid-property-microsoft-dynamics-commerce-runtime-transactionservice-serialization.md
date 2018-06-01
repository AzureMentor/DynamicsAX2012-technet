﻿---
title: TransactionHeader.LoyaltyCardId Property  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: LoyaltyCardId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionHeader.LoyaltyCardId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.transactionheader.loyaltycardid(v=AX.60)
ms:contentKeyID: 62209592
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionHeader.LoyaltyCardId
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyCardId Property

Gets or sets the loyalty card number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property LoyaltyCardId As String
    Get
    Set
'Usage
Dim instance As TransactionHeader
Dim value As String

value = instance.LoyaltyCardId

instance.LoyaltyCardId = value
```

``` csharp
public string LoyaltyCardId { get; set; }
```

``` c++
public:
property String^ LoyaltyCardId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The loyalty card number.  

## See Also

#### Reference

[TransactionHeader Class](transactionheader-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)
