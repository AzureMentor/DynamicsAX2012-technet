﻿---
title: InsertSalesTransactionTablesDataRequest.PropertiesTable Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: PropertiesTable Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertSalesTransactionTablesDataRequest.PropertiesTable
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.insertsalestransactiontablesdatarequest.propertiestable(v=AX.60)
ms:contentKeyID: 65319639
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertSalesTransactionTablesDataRequest.PropertiesTable
dev_langs:
- CSharp
- C++
- VB
---

# PropertiesTable Property

Gets the properties table.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property PropertiesTable As DataTable
    Get
    Private Set
'Usage
Dim instance As InsertSalesTransactionTablesDataRequest
Dim value As DataTable

value = instance.PropertiesTable
```

``` csharp
public DataTable PropertiesTable { get; private set; }
```

``` c++
public:
property DataTable^ PropertiesTable {
    DataTable^ get ();
    private: void set (DataTable^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  
Returns [DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md).  

## See Also

#### Reference

[InsertSalesTransactionTablesDataRequest Class](insertsalestransactiontablesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)
