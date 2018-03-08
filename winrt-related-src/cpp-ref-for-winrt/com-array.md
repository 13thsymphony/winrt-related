---
author: stevewhims
description: A view, or span, of a contiguous series of values for passing to and from WinRT APIs.
title: winrt::com_array struct template (C++/WinRT)
dev_langs: ["C++"]
ms.author: stwhi
manager: "markl"
ms.date: 03/01/2018
ms.technology: "cpp-windows"
ms.topic: "language-reference"
ms.prod: windows
ms.technology: uwp
keywords: windows 10, uwp, standard, c++, cpp, winrt, projection, api, reference, array, view, com_array, span
ms.localizationpriority: medium
ms.workload: ["cplusplus"]
---

# winrt::com_array struct template (C++/WinRT)
> [!NOTE]
> **Some information relates to pre-released product which may be substantially modified before it’s commercially released. Microsoft makes no warranties, express or implied, with respect to the information provided here.**

A view, or span, of a contiguous series of values for passing to and from WinRT APIs. **winrt::com_array** *is a* **winrt::array_view**, so it's important to see the [winrt::array_view struct template](array-view.md) topic to learn about the members and free operators that are also available to **winrt::com_array**.

## Syntax
```cppwinrt
template <typename T>
    struct com_array : array_view<T>
```

### Template parameters
`typename T`
The type of the values (elements) that the **com_array** views, or spans.

## Requirements
**Minimum supported SDK:** Windows SDK for Windows 10, version 1803

**Namespace:** winrt

**Header** %ProgramFiles(x86)%\Windows Kits\10\Include\<WindowsTargetPlatformVersion>\cppwinrt\winrt\base.h (included by default)

## Constructors
|Constructor|Description|
|------------|-----------------|
|[com_array::com_array constructor](#comarraycomarray-constructor)|Initializes a new instance of the **com_array** struct with a copy of the input data.|

## Member functions
|Function|Description|
|------------|-----------------|
|[com_array::clear function](#comarrayclear-function)|Makes the **com_array** object empty.|

## Member operators
|Operator|Description| 
|------------|-----------------|
|[com_array::operator= (assignment operator)](#com_arrayoperator-assignment-operator)|Assigns a value to the **com_array** object.|

## Free functions
|Function|Description|
|------------|-----------------| 
|[swap function](#swap-function)|Swaps the contents of the two **com_array** parameters.| 

## com_array::com_array constructor
Initializes a new instance of the **com_array** struct with a copy of the input data.

### Syntax
```cppwinrt
com_array() noexcept
com_array(com_array&& comArrayValue) noexcept
template <typename InIt> com_array(InIt first, InIt last)
template <uint32_t N> com_array(std::array<T, N> const& arrayValue)
com_array(std::initializer_list<T> initializerListValue)
com_array(std::vector<T> const& vectorValue)
template <uint32_t N> com_array(T const(&rawArrayValue)[N])
com_array(uint32_t const count)
com_array(uint32_t const count, T const& value)
```

### Template parameters
`typename InIt`
The type of the values (elements) in the input data.

`uint32_t N`
The number of values (elements) in the input data.

### Parameters
`comArrayValue`
Another **com_array** that initializes the **com_array** object.

`first` `last`
Values with which to initialize the **com_array** object.

`arrayValue`
A `std::array` value that initializes the **com_array** object.

`initializerListValue`
An initializer list value that initializes the **com_array** object.

`vectorValue`
A `std::vector` value that initializes the **com_array** object.

`rawArrayValue`
A raw array value that initializes the **com_array** object.

`count`
The element count of the **com_array** object.

`value`
The value to give to each element of the **com_array** object.

## com_array::clear function
Makes the **com_array** object empty.

### Syntax
```cppwinrt
void clear() noexcept
```

## com_array::operator= (assignment operator)
Assigns a value to the **com_array** object.

### Syntax
```cppwinrt
com_array& operator=(com_array&& comArrayValue) noexcept
```

### Parameters
`comArrayValue`
A **com_array** value to assign to the **com_array** object.

### Return value
A reference to the **com_array** object.

## swap function
Swaps the contents of the two **com_array** parameters.

### Syntax
```cppwinrt
void swap(com_array& left, com_array& right) noexcept
```

### Parameters
`left` `right`
A **com_array** value whose contents to mutually swap with those of the other parameter.

### Example
```cppwinrt
using namespace winrt;
...
	com_array<byte> left{ 1,2,3 };
	com_array<byte> right{ 4,5,6 };
	swap(left, right);
```

## See also 
[winrt namespace (C++/WinRT)](winrt.md)
