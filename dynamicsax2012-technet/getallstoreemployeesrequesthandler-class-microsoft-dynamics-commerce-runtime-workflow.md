﻿---
title: GetAllStoreEmployeesRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetAllStoreEmployeesRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAllStoreEmployeesRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.getallstoreemployeesrequesthandler(v=AX.60)
ms:contentKeyID: 62212093
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAllStoreEmployeesRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetAllStoreEmployeesRequestHandler Class

Encapsulates the workflow required to get all available employees for a store.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Class GetAllStoreEmployeesRequestHandler _
    Inherits WorkflowRequestHandler(Of GetAllStoreEmployeesRequest, GetAllStoreEmployeesResponse)
'Usage
Dim instance As GetAllStoreEmployeesRequestHandler
```

``` csharp
public class GetAllStoreEmployeesRequestHandler : WorkflowRequestHandler<GetAllStoreEmployeesRequest, GetAllStoreEmployeesResponse>
```

``` c++
public ref class GetAllStoreEmployeesRequestHandler : public WorkflowRequestHandler<GetAllStoreEmployeesRequest^, GetAllStoreEmployeesResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetAllStoreEmployeesRequest](getallstoreemployeesrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetAllStoreEmployeesResponse](getallstoreemployeesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetAllStoreEmployeesRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)
