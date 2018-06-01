﻿---
title: WishListLine.Quantity Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: Quantity Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.WishListLine.Quantity
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.wishlistline.quantity(v=AX.60)
ms:contentKeyID: 62201797
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.WishListLine.Quantity
dev_langs:
- CSharp
- C++
- VB
---

# Quantity Property

Gets or sets the wish list line quantity.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Quantity As Decimal
    Get
    Set
'Usage
Dim instance As WishListLine
Dim value As Decimal

value = instance.Quantity

instance.Quantity = value
```

``` csharp
[DataMemberAttribute]
public decimal Quantity { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal Quantity {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[WishListLine Class](wishlistline-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)
