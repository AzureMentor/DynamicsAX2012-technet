﻿---
title: SalesOrderCollectionResponse.SalesOrders Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: SalesOrders Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrderCollectionResponse.SalesOrders
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.salesordercollectionresponse.salesorders(v=AX.60)
ms:contentKeyID: 62203295
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrderCollectionResponse.SalesOrders
dev_langs:
- CSharp
- C++
- VB
---

# SalesOrders Property

A collection of sales orders.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SalesOrders As IEnumerable(Of SalesOrder)
    Get
    Set
'Usage
Dim instance As SalesOrderCollectionResponse
Dim value As IEnumerable(Of SalesOrder)

value = instance.SalesOrders

instance.SalesOrders = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<SalesOrder> SalesOrders { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<SalesOrder^>^ SalesOrders {
    IEnumerable<SalesOrder^>^ get ();
    void set (IEnumerable<SalesOrder^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[SalesOrder](salesorder-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[SalesOrderCollectionResponse Class](salesordercollectionresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)
