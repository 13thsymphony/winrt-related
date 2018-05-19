---
author: stevewhims
description: Captures the thread context within a coroutine so that it can be restored later.
title: winrt::apartment_context struct (C++/WinRT)
dev_langs: ["C++"]
ms.author: stwhi
ms.date: 05/17/2018
ms.technology: "cpp-windows"
ms.topic: "language-reference"
ms.prod: windows
ms.technology: uwp
keywords: windows 10, uwp, standard, c++, cpp, winrt, projection, api, reference
ms.localizationpriority: medium
ms.workload: ["cplusplus"]
---

# winrt::apartment_context struct ([C++/WinRT](/windows/uwp/cpp-and-winrt-apis/intro-to-using-cpp-with-winrt))
Captures the thread context within a coroutine so that it can be restored later. You instantiate a **winrt::apartment_context** value, and then later you `co_await` it. For more info, and a code example, see [Programming with thread affinity in mind](/windows/uwp/cpp-and-winrt-apis/concurrency.md#programming-with-thread-affinity-in-mind).

## Syntax
```cppwinrt
struct apartment_context
```

## Requirements
**Minimum supported SDK:** Windows SDK version 10.0.17134.0 (Windows 10, version 1803)

**Namespace:** winrt

**Header** %WindowsSdkDir%Include\<WindowsTargetPlatformVersion>\cppwinrt\winrt\base.h (included by default)

## See also 
* [winrt namespace](winrt.md)
* [winrt::apartment_context function](apartment-context.md)
* [winrt::resume_background function](resume-foreground.md)
* [Concurrency and asynchronous operations with C++/WinRT](/windows/uwp/cpp-and-winrt-apis/concurrency.md)
