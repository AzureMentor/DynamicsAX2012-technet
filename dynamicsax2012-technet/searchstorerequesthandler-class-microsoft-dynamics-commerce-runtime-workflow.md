﻿---
title: SearchStoreRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: SearchStoreRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.SearchStoreRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.searchstorerequesthandler(v=AX.60)
ms:contentKeyID: 62213404
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.SearchStoreRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# SearchStoreRequestHandler Class

Search the store information for the given search criteria.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Class SearchStoreRequestHandler _
    Inherits WorkflowRequestHandler(Of SearchStoreRequest, SearchStoreResponse)
'Usage
Dim instance As SearchStoreRequestHandler
```

``` csharp
public class SearchStoreRequestHandler : WorkflowRequestHandler<SearchStoreRequest, SearchStoreResponse>
```

``` c++
public ref class SearchStoreRequestHandler : public WorkflowRequestHandler<SearchStoreRequest^, SearchStoreResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[SearchStoreRequest](searchstorerequest-class-microsoft-dynamics-commerce-runtime-messages.md), [SearchStoreResponse](searchstoreresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.SearchStoreRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)
