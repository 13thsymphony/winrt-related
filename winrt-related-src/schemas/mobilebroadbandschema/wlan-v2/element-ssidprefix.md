---
Description: SSIDPrefix
MS-HAID: WLAN\_v2.element\_SSIDPrefix
MSHAttr:
- PreferredSiteName:MSDN
- PreferredLib:/library/windows/apps
Search.Product: eADQiWindows 10XVcnh
title: SSIDPrefix
ms.assetid: 04783397-4119-4fcf-955f-5110cbb47d90
author: mcleblanc
ms.author: markl
keywords: windows 10, uwp, schema, mobile broadband schema
---

# SSIDPrefix


Contains the SSIDPrefix for a WLAN.

## Element hierarchy

**&lt;SSIDPrefix&gt;**

## Syntax

``` syntax
<SSIDPrefix>

  <!-- Child elements -->
  ( hex
  | name
  )

</SSIDPrefix>
```

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
<td>[hex (in SSIDPrefix)](element-1-hex.md)</td>
<td><p>Defines the SSIDPrefix of a wireless LAN in hexadecimal format.</p></td>
</tr>
<tr class="even">
<td>[name (in SSIDPrefix)](element-1-name.md)</td>
<td><p>Defines the SSIDPrefix of a wireless LAN in alphanumeric format.</p></td>
</tr>
</tbody>
</table>

 

### Parent Elements

This outermost (document) element may not be contained by any other elements.

## Remarks

The **SSIDPrefix** element is included in the version 2 schema supported on Windows 8.1, Windows Server 2012 R2, and later.

Although the [**hex**](element-1-hex.md) and [**name**](element-1-name.md) elements are optional, at least one **hex** or **name** element must appear as a child of the **SSIDPrefix** element. If both are present, the **hex** SSIDPrefix takes precedence over the **name** SSIDPrefix.

## Requirements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Namespace</p></td>
<td><p>http://www.microsoft.com/networking/CarrierControl/WLAN/v2</p></td>
</tr>
</tbody>
</table>

 

 



