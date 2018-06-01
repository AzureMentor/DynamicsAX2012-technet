﻿---
title: ShiftTenderLine.AddToTenderAmountOfStoreCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AddToTenderAmountOfStoreCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.AddToTenderAmountOfStoreCurrency
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.addtotenderamountofstorecurrency(v=AX.60)
ms:contentKeyID: 62212962
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.AddToTenderAmountOfStoreCurrency
dev_langs:
- CSharp
- C++
- VB
---

# AddToTenderAmountOfStoreCurrency Property

Gets total amount added to tender in store currency.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public ReadOnly Property AddToTenderAmountOfStoreCurrency As Decimal
    Get
'Usage
Dim instance As ShiftTenderLine
Dim value As Decimal

value = instance.AddToTenderAmountOfStoreCurrency
```

``` csharp
[IgnoreDataMemberAttribute]
public decimal AddToTenderAmountOfStoreCurrency { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property Decimal AddToTenderAmountOfStoreCurrency {
    Decimal get ();
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ShiftTenderLine Class](shifttenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
