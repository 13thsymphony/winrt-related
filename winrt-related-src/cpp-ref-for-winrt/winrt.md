---
author: stevewhims
description: API reference content for the winrt namespace from C++/WinRT.
title: winrt namespace (C++/WinRT)
dev_langs: ["C++"]
ms.author: stwhi
manager: "markl"
ms.date: 04/10/2018
ms.technology: "cpp-windows"
ms.topic: "language-reference"
ms.prod: windows
ms.technology: uwp
keywords: windows 10, uwp, standard, c++, cpp, winrt, projection, api, reference
ms.localizationpriority: medium
ms.workload: ["cplusplus"]
---

# winrt namespace (C++/WinRT)
The **winrt** namespace provides custom data types belonging to [C++/WinRT](/windows/uwp/cpp-and-winrt-apis/index)&mdash;the standard, modern C++17 language projection for Windows Runtime (WinRT) APIs. These custom types provide appropriate conversions to and from standard types so that, much of the time, you can continue to use the standard C++ language features that you're accustomed to using, and the source code that you already have.

Also provided in the **winrt** namespace are functions (for creating runtime class instances, boxing and unboxing, etc.), smart pointers, and other facilities.

## Types
| Type | Description |
| - | - |
| [array_view struct template](array-view.md) | A view, or span, of a contiguous series of values. |
| [attach_abi function](attach-abi.md) | A helper function that attaches a C++/WinRT object to a handle, or to a raw pointer that owns a reference to its target. |
| [box_value function template](box-value.md) | A function template that wraps (or *boxes*) a scalar value inside a reference class object so that it can be passed to a function that expects **IInspectable**. |
| [com_array struct template](com-array.md) | A view, or span, of a contiguous series of values for passing to and from WinRT APIs. |
| [com_ptr struct template](com-ptr.md) | A reference-counted COM smart pointer template. |
| [copy_from_abi function](copy-from-abi.md) | A helper function that copies to a C++/WinRT object from a handle, or from a raw pointer. |
| [copy_to_abi function](copy-to-abi.md) | A helper function that copies from a C++/WinRT object to a handle, or to a pointer. |
| [detach_abi function](detach-abi.md) | A helper function that detaches from the handle, or from the referenced interface. |
| [get_abi function](get-abi.md) | A helper function that retrieves a pointer to a C++/WinRT object's underlying [IUnknown interface](https://msdn.microsoft.com/library/windows/desktop/ms680509). |
| [hstring struct](hstring.md) | A sequential collection of UTF-16 Unicode characters representing a text string. |
| [implements struct template](implements.md) | A base struct template that implements one or more Windows Runtime interfaces on behalf of a derived type. |
| [make function template](make.md) | A factory method that returns an instance of the projected type for a runtime class when parameterized with the corresponding implementation type. |
| [make_self function template](make-self.md) | A factory method that returns a [com_ptr](com-ptr.md) to an instance of the implementation type for a runtime class. |
| [make_weak function template](make-weak.md) | A helper function that returns a [weak_ref](weak-ref.md) object, representing a weak reference to a C++/WinRT object. |
| [put_abi function](put-abi.md) | A helper function that retrieves the address of a C++/WinRT object's underlying IUnknown interface pointer so that it can be set to another value. |
| [swap function](swap.md) | A helper function that swaps the contents of two values. |
| [unbox_value function template](unbox-value.md) | A function template that unwraps (or *unboxes*) a scalar value from inside a reference class object so that it can be processed in a function that expects **IInspectable**. |
| [unbox_value_or function template](unbox-value-or.md) | A function template that unwraps (or *unboxes*) a scalar value from inside a reference class object, with a fallback value, so that it can be processed in a function that expects **IInspectable**. |
| [weak_ref struct template](weak-ref.md) | A type representing a weak reference to a C++/WinRT object or interface. |
| [Windows::Foundation::IUnknown struct](windows-foundation-iunknown.md) | Every C++/WinRT runtime class (whether a Windows or a third party runtime class) derives from winrt::Windows::Foundation::IUnknown. |
| [xaml_typename function template](xaml-typename.md) | A helper function that returns the type name of a Windows Runtime type, in the form of a [Windows::UI::Xaml::Interop::TypeName](/uwp/api/windows.ui.xaml.interop.typename) object. |

## See also 
[C++/WinRT](/windows/uwp/cpp-and-winrt-apis/index)
