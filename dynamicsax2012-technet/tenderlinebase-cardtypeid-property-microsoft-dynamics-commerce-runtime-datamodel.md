﻿---
title: TenderLineBase.CardTypeId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CardTypeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.CardTypeId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tenderlinebase.cardtypeid(v=AX.60)
ms:contentKeyID: 62203219
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.CardTypeId
dev_langs:
- CSharp
- C++
- VB
---

# CardTypeId Property

Gets or sets the credit card type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CARDTYPEID")> _
Public Property CardTypeId As String
    Get
    Set
'Usage
Dim instance As TenderLineBase
Dim value As String

value = instance.CardTypeId

instance.CardTypeId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CARDTYPEID")]
public string CardTypeId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CARDTYPEID")]
public:
property String^ CardTypeId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TenderLineBase Class](tenderlinebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
