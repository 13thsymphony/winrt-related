---
author: stevewhims
description: A helper function that returns a [weak_ref](weak-ref.md) object, representing a weak reference to a C++/WinRT object or interface.
title: winrt::make_weak function template (C++/WinRT)
dev_langs: ["C++"]
ms.author: stwhi
manager: "markl"
ms.date: 04/10/2018
ms.technology: "cpp-windows"
ms.topic: "language-reference"
ms.prod: windows
ms.technology: uwp
keywords: windows 10, uwp, standard, c++, cpp, winrt, projection, api, reference, weak
ms.localizationpriority: medium
ms.workload: ["cplusplus"]
---

# winrt::make_weak function template ([C++/WinRT](/windows/uwp/cpp-and-winrt-apis/intro-to-using-cpp-with-winrt))
A helper function that returns a [weak_ref](weak-ref.md) object, representing a weak reference to a C++/WinRT object or interface. For more info, and code examples, see [Weak references in C++/WinRT](/windows/uwp/cpp-and-winrt-apis/weak-references).

## Syntax
```cppwinrt
template <typename T>
weak_ref<impl::wrapped_type_t<T>> make_weak(T const& object)
```

### Template parameters
`typename T`
The type of C++/WinRT object or interface to make a weak reference to.

### Parameters
`object`
The C++/WinRT object or interface to make a weak reference to.

### Return value 
A [weak_ref](weak-ref.md) representing a weak reference to the C++/WinRT object or interface.

## Requirements
**Minimum supported SDK:** Windows SDK version 10.0.17133.0 (Windows 10, version 1803)

**Namespace:** winrt

**Header** %WindowsSdkDir%Include\<WindowsTargetPlatformVersion>\cppwinrt\winrt\base.h (included by default)

## See also 
* [winrt namespace](winrt.md)
* [winrt::weak_ref struct template](weak-ref.md)
* [Weak references in C++/WinRT](/windows/uwp/cpp-and-winrt-apis/weak-references)
