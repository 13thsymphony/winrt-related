---
author: stevewhims
description: A marker type used to indicate that your type is not agile, and consequently does not implement the IAgileObject interface.
title: winrt::non_agile marker struct (C++/WinRT)
dev_langs: ["C++"]
ms.author: stwhi
manager: "jillfra"
ms.date: 04/13/2018
ms.technology: "cpp-windows"
ms.topic: "language-reference"
ms.prod: windows
ms.technology: uwp
keywords: windows 10, uwp, standard, c++, cpp, winrt, projection, api, reference, marker, type
ms.localizationpriority: medium
ms.workload: ["cplusplus"]
---

# winrt::non_agile marker struct ([C++/WinRT](/windows/uwp/cpp-and-winrt-apis/intro-to-using-cpp-with-winrt))
A marker type used to indicate to the [**implements**](implements.md) base struct that your type is not agile. As a result, **implements** does not implement the [IAgileObject interface](https://msdn.microsoft.com/library/windows/desktop/hh802476). For a usage example, see [Marker types](implements.md#marker-types).

## Syntax
```cppwinrt
struct winrt::non_agile : impl::marker
```

## Requirements
**Minimum supported SDK:** Windows SDK version 10.0.17134.0 (Windows 10, version 1803)

**Namespace:** winrt

**Header** %WindowsSdkDir%Include\<WindowsTargetPlatformVersion>\cppwinrt\winrt\base.h (included by default)

## See also 
* [winrt namespace](winrt.md)
