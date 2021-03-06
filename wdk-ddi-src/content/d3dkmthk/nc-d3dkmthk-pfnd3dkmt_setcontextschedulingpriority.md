---
UID: NC:d3dkmthk.PFND3DKMT_SETCONTEXTSCHEDULINGPRIORITY
title: PFND3DKMT_SETCONTEXTSCHEDULINGPRIORITY (d3dkmthk.h)
description: The PFND3DKMT_SETCONTEXTSCHEDULINGPRIORITY callback function sets the scheduling priority for a device context.
ms.assetid: ab05421f-7cbf-4e2b-8a26-387ecad8b482
ms.date: 10/19/2018
keywords: ["PFND3DKMT_SETCONTEXTSCHEDULINGPRIORITY callback function"]
f1_keywords:
 - "d3dkmthk/PFND3DKMT_SETCONTEXTSCHEDULINGPRIORITY"
req.header: d3dkmthk.h
req.include-header:
req.target-type:
req.target-min-winverclnt:
req.target-min-winversvr:
req.kmdf-ver:
req.umdf-ver:
req.lib:
req.dll:
req.irql: 
req.ddi-compliance:
req.unicode-ansi:
req.idl:
req.max-support:
req.namespace:
req.assembly:
req.type-library: 
topic_type: 
- apiref
api_type: 
- UserDefined
api_location: 
- d3dkmthk.h
api_name: 
- PFND3DKMT_SETCONTEXTSCHEDULINGPRIORITY
product:
- Windows
targetos: Windows
ms.custom: RS5
dev_langs:
 - c++
tech.root: display
---

# PFND3DKMT_SETCONTEXTSCHEDULINGPRIORITY callback function

## -description

The PFND3DKMT_SETCONTEXTSCHEDULINGPRIORITY callback function sets the scheduling priority for a device context.

## -prototype

```cpp
//Declaration

PFND3DKMT_SETCONTEXTSCHEDULINGPRIORITY Pfnd3dkmtSetcontextschedulingpriority; 

// Definition

NTSTATUS Pfnd3dkmtSetcontextschedulingpriority 
(
	const D3DKMT_SETCONTEXTSCHEDULINGPRIORITY *
)
{...}

```

## -parameters

### -param Arg1

Pointer to a [D3DKMT_SETCONTEXTSCHEDULINGPRIORITY](ns-d3dkmthk-_d3dkmt_setcontextschedulingpriority.md) structure.

## -returns

Returns NTSTATUS.


## -remarks




## -see-also
