﻿---
title: CurrencyAmount.CurrencyCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CurrencyCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CurrencyAmount.CurrencyCode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.currencyamount.currencycode(v=AX.60)
ms:contentKeyID: 62202822
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CurrencyAmount.CurrencyCode
dev_langs:
- CSharp
- C++
- VB
---

# CurrencyCode Property

Gets or sets the currency code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CURRENCYCODE")> _
<KeyAttribute> _
Public Property CurrencyCode As String
    Get
    Set
'Usage
Dim instance As CurrencyAmount
Dim value As String

value = instance.CurrencyCode

instance.CurrencyCode = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CURRENCYCODE")]
[KeyAttribute]
public string CurrencyCode { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CURRENCYCODE")]
[KeyAttribute]
public:
property String^ CurrencyCode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CurrencyAmount Class](currencyamount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
