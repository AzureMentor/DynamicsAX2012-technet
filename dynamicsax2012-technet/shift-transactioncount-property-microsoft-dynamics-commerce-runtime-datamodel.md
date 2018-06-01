﻿---
title: Shift.TransactionCount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionCount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.TransactionCount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shift.transactioncount(v=AX.60)
ms:contentKeyID: 62203626
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.TransactionCount
dev_langs:
- CSharp
- C++
- VB
---

# TransactionCount Property

Gets or sets number of transactions calculated.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TRANSACTIONSCOUNT")> _
<DataMemberAttribute> _
Public Property TransactionCount As Integer
    Get
    Set
'Usage
Dim instance As Shift
Dim value As Integer

value = instance.TransactionCount

instance.TransactionCount = value
```

``` csharp
[ColumnAttribute("TRANSACTIONSCOUNT")]
[DataMemberAttribute]
public int TransactionCount { get; set; }
```

``` c++
[ColumnAttribute(L"TRANSACTIONSCOUNT")]
[DataMemberAttribute]
public:
property int TransactionCount {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[Shift Class](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
