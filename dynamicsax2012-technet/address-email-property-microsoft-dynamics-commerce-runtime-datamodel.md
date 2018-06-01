﻿---
title: Address.Email Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Email Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.Email
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.address.email(v=AX.60)
ms:contentKeyID: 49836114
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.Email
dev_langs:
- CSharp
- C++
- VB
---

# Email Property

Gets or sets the Email.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("EMAIL")> _
Public Property Email As String
    Get
    Set
'Usage
Dim instance As Address
Dim value As String

value = instance.Email

instance.Email = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("EMAIL")]
public string Email { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"EMAIL")]
public:
property String^ Email {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
