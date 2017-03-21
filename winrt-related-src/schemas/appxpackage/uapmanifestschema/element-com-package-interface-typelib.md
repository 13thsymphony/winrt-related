---
author: laurenhughes
ms.assetid: 2fb1ff8b-0c47-44b8-b1c3-b814d10685d1
title: com:TypeLib (in Package/Extensions)
description: A type library for an interface.
ms.author: lahugh
ms.date: 03/29/2017
ms.topic: article
ms.prod: windows
ms.technology: uwp
keywords: windows 10, uwp, schema, manifest, com
---


# com:TypeLib (in Package/Extensions)

## -description
A type library for an interface.

## -element-hierarchy
<dl>
<dt><a href="element-package.md">&lt;Package&gt;</a></dt>
<dd>
<dl>
<dt><a href="element-extensions.md">&lt;Extensions&gt;</a></dt>
<dd>
<dl>
<dt><a href="element-extension.md">&lt;Extension&gt;</a></dt>
<dd>
<dl>
<dt><a href="element-com-package-cominterface.md">&lt;ComInterface&gt;</a></dt>
<dd>
<dl>
<dt><a href="element-com-package-interface.md">&lt;Interface&gt;</a></dt>
<dd><b>&lt;TypeLib&gt;</b></dd>
</dl>
</dd>
</dl>
</dd>
</dl>
</dd>
</dl>
</dd>
</dl>


## -syntax
```syntax
<TypeLib
    Id = A GUID in the form xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx. 
    VersionNumber? = One to three alphanumeric characters separated by a period followed by one to three more alphanumeric characters, e.g., 1.5a >
</TypeLib>
```

## -key
`?`    optional (zero or one) 

## -attributes

| Attribute | Description | Data type | Required |
|-----------|-------------|-----------|----------|
| Id      | The type library ID. | A GUID in the form xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx. | Yes |
| VersionNumber | The version of the type library. | One to three alphanumeric characters separated by a period followed by one to three more alphanumeric characters, e.g., 1.5a | No |

## -remarks

## -examples

## -requirements
<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Namespace</p></td>
<td><p>http://schemas.microsoft.com/appx/manifest/com/windows10</p></td>
</tr>
</tbody>
</table>