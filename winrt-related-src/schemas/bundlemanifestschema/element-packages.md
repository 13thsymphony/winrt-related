---
Description: Defines the app packages and resource packages that are contained in the bundle.
Search.Product: eADQiWindows 10XVcnh
title: Packages
ms.assetid: 2e6638ac-df50-43a8-be6a-7190c8e4486f
author: laurenhughes
ms.author: lahugh
keywords: windows 10, uwp, schema, bundle manifest
ms.prod: windows
ms.technology: winrt-reference
ms.topic: reference
ms.date: 04/05/2017
---

# Packages

Defines the app packages and resource packages that are contained in the bundle.

## Element hierarchy

<dl>
<dt><a href="element-bundle.md">&lt;Bundle&gt;</a></dt>
<dd><b>&lt;Packages&gt;</b></dd>
</dl>

## Syntax

``` syntax
<Packages>

  <!-- Child elements -->
  Package{1,10000}

</Packages>
```

### Key

`{}`   specific range of occurrences
## Attributes and Elements


### Attributes

None.

### Child Elements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Child Element</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>[Package](element-package.md)</td>
<td><p>Defines one of the app packages or resource packages in the bundle.</p></td>
</tr>
</tbody>
</table>

 

### Parent Elements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Parent Element</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>[Bundle](element-bundle.md)</td>
<td><p>Defines the root element of a bundle manifest. The manifest describes the structure and capabilities of the software to the system.</p></td>
</tr>
</tbody>
</table>

 

## Requirements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Namespace</p></td>
<td><p>http://schemas.microsoft.com/appx/2013/bundle</p></td>
</tr>
</tbody>
</table>

 

 



