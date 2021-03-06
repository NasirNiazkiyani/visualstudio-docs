---
title: "IDebugArrayObject::GetRank | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.technology: 
  - "vs-ide-sdk"
ms.topic: "conceptual"
f1_keywords: 
  - "IDebugArrayObject::GetRank"
helpviewer_keywords: 
  - "IDebugArrayObject::GetRank method"
ms.assetid: 9948551a-e334-4ff6-979c-08dab633b9b6
author: "gregvanl"
ms.author: "gregvanl"
manager: douge
ms.workload: 
  - "vssdk"
---
# IDebugArrayObject::GetRank
Gets the rank of the array, that is, the number of dimensions.  
  
## Syntax  
  
```cpp  
HRESULT GetRank(   
   DWORD* pdwRank  
);  
```  
  
```csharp  
int GetRank(  
   out uint pdwRank  
);  
```  
  
#### Parameters  
 `pdwRank`  
 [out] Returns the rank.  
  
## Return Value  
 If successful, returns S_OK; otherwise, returns an error code.  
  
## Remarks  
 Use the [GetDimensions](../../../extensibility/debugger/reference/idebugarrayobject-getdimensions.md) method to retrieve the size of each dimension of the array object.  
  
## See Also  
 [IDebugArrayObject](../../../extensibility/debugger/reference/idebugarrayobject.md)