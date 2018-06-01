﻿---
title: GetChannelCurrencyRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetChannelCurrencyRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetChannelCurrencyRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.getchannelcurrencyrequesthandler(v=AX.60)
ms:contentKeyID: 62207756
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetChannelCurrencyRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelCurrencyRequestHandler Class

Encapsulates the workflow required to retrieve supported channel currency amounts.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Class GetChannelCurrencyRequestHandler _
    Inherits WorkflowRequestHandler(Of GetChannelCurrencyAmountRequest, GetChannelCurrencyAmountResponse)
'Usage
Dim instance As GetChannelCurrencyRequestHandler
```

``` csharp
public class GetChannelCurrencyRequestHandler : WorkflowRequestHandler<GetChannelCurrencyAmountRequest, GetChannelCurrencyAmountResponse>
```

``` c++
public ref class GetChannelCurrencyRequestHandler : public WorkflowRequestHandler<GetChannelCurrencyAmountRequest^, GetChannelCurrencyAmountResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetChannelCurrencyAmountRequest](getchannelcurrencyamountrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetChannelCurrencyAmountResponse](getchannelcurrencyamountresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetChannelCurrencyRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)
