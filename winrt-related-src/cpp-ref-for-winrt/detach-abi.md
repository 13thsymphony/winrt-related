---
author: stevewhims
description: A helper function that detaches from the handle, or from the referenced interface.
title: winrt::detach_abi function (C++/WinRT)
dev_langs: ["C++"]
ms.author: stwhi
manager: "markl"
ms.date: 04/11/2018
ms.technology: "cpp-windows"
ms.topic: "language-reference"
ms.prod: windows
ms.technology: uwp
keywords: windows 10, uwp, standard, c++, cpp, winrt, projection, api, reference, detach_abi
ms.localizationpriority: medium
ms.workload: ["cplusplus"]
---

# winrt::detach_abi function (C++/WinRT)
A helper function that detaches from the handle, or from the referenced interface. Detaching from an interface is done without decrementing the reference count, perhaps to return it to a caller.

## Syntax
```cppwinrt
template <typename T, typename = std::enable_if_t<!std::is_base_of_v<winrt::Windows::Foundation::IUnknown, std::decay_t<T>> && !std::is_convertible_v<T, std::wstring_view>>>
auto detach_abi(T&& object)

void* detach_abi(winrt::Windows::Foundation::IUnknown& object) noexcept

void* detach_abi(winrt::Windows::Foundation::IUnknown&& object) noexcept

constexpr void* detach_abi(std::nullptr_t) noexcept

template <typename T>
auto detach_abi(winrt::com_ptr<T>& object) noexcept

HSTRING detach_abi(winrt::hstring& object) noexcept

HSTRING detach_abi(winrt::hstring&& object) noexcept

HSTRING detach_abi(std::wstring_view const& value)

template <typename T>
auto detach_abi(winrt::com_array<T>& object) noexcept

template <typename T>
auto detach_abi(winrt::com_array<T>&& object) noexcept
```

### Parameters
`object`
A C++/WinRT object to operate on.

### Return value
The handle, or a pointer to the raw interface, referenced by the C++/WinRT object.

## Requirements
**Minimum supported SDK:** Windows SDK version 10.0.17133.0 (Windows 10, version 1803)

**Namespace:** winrt

**Header** %WindowsSdkDir%Include\<WindowsTargetPlatformVersion>\cppwinrt\winrt\base.h (included by default)

## See also 
* [winrt namespace](winrt.md)
* [winrt::com_array struct template](com-array.md)
* [winrt::com_ptr struct template](com-ptr.md)
* [winrt::hstring struct](hstring.md)
* [Windows::Foundation::IUnknown struct](windows-foundation-iunknown.md)
