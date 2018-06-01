﻿---
title: LoyaltyCard.RewardPoints Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RewardPoints Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCard.RewardPoints
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltycard.rewardpoints(v=AX.60)
ms:contentKeyID: 62208457
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCard.RewardPoints
dev_langs:
- CSharp
- C++
- VB
---

# RewardPoints Property

Gets or sets the reward points on the loyalty card.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RewardPoints As IList(Of LoyaltyRewardPoint)
    Get
    Set
'Usage
Dim instance As LoyaltyCard
Dim value As IList(Of LoyaltyRewardPoint)

value = instance.RewardPoints

instance.RewardPoints = value
```

``` csharp
[DataMemberAttribute]
public IList<LoyaltyRewardPoint> RewardPoints { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<LoyaltyRewardPoint^>^ RewardPoints {
    IList<LoyaltyRewardPoint^>^ get ();
    void set (IList<LoyaltyRewardPoint^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\))\<[LoyaltyRewardPoint](loyaltyrewardpoint-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyCard Class](loyaltycard-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
