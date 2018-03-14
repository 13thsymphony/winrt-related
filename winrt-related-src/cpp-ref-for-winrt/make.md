---
author: stevewhims
description: A factory method that returns an instance of the projected type for a runtime class when parameterized with the corresponding implementation type.
title: winrt::make function template (C++/WinRT)
dev_langs: ["C++"]
ms.author: stwhi
manager: "markl"
ms.date: 03/01/2018
ms.technology: "cpp-windows"
ms.topic: "language-reference"
ms.prod: windows
ms.technology: uwp
keywords: windows 10, uwp, standard, c++, cpp, winrt, projection, api, reference, string
ms.localizationpriority: medium
ms.workload: ["cplusplus"]
---

# winrt::make function template (C++/WinRT)
> [!NOTE]
> **Some information relates to pre-released product which may be substantially modified before it’s commercially released. Microsoft makes no warranties, express or implied, with respect to the information provided here.**

A factory method that returns an instance of the projected type for a runtime class when parameterized with the corresponding implementation type. For an explanation of the implementation type and projected type concepts, see [Implementation and projected types for a C++/WinRT runtime class](/windows/uwp/cpp-and-winrt-apis/ctors-runtimeclass-activation?branch=live). For more details, code, and a walkthrough of calling **make** in practice, see [XAML; binding a control to C++/WinRT properties and collections](/windows/uwp/cpp-and-winrt-apis/binding-prop-collection?branch=live#add-a-property-of-type-booksku-to-mainpage).

## Syntax
```cppwinrt
template <typename D, typename... Args, std::enable_if_t<!impl::has_composable<D>::value && impl::has_class_type<D>::value>* = nullptr>
auto make(Args&&... args)
```

### Template parameters
`typename D`
The implementation type for a runtime class.

### Parameters
`args`
Any constructor arguments for the constructor being invoked.

### Return value 
A newly-created instance of the projected type for the runtime class.

## Requirements
**Minimum supported SDK:** Windows SDK for Windows 10, version 1803

**Namespace:** winrt

**Header** %ProgramFiles(x86)%\Windows Kits\10\Include\<WindowsTargetPlatformVersion>\cppwinrt\winrt\base.h (included by default)

## See also 
* [winrt namespace (C++/WinRT)](winrt.md)
* [Implementation and projected types for a C++/WinRT runtime class](/windows/uwp/cpp-and-winrt-apis/ctors-runtimeclass-activation?branch=live)
* [XAML; binding a control to C++/WinRT properties and collections](/windows/uwp/cpp-and-winrt-apis/binding-prop-collection?branch=live#add-a-property-of-type-booksku-to-mainpage)