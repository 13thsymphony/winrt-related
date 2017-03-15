---
Description: HomeProviderName
MS-HAID: WWAN.element\_1\_HomeProviderName
MSHAttr:
- PreferredSiteName:MSDN
- PreferredLib:/library/windows/apps
Search.Product: eADQiWindows 10XVcnh
title: HomeProviderName
ms.assetid: 3e57b52a-a7f7-4ef6-89e9-29b72ec833b0
author: mcleblanc
ms.author: markl
keywords: windows 10
---

# HomeProviderName


Defines the name of the Home Provider for a given SIM/Device.

## Element hierarchy

<dl>
<dt><a href="element-defaultprofile.md">&lt;DefaultProfile&gt;</a></dt>
<dd><b>&lt;HomeProviderName&gt;</b></dd>
</dl>
<dl>
<dt><a href="element-purchaseprofile.md">&lt;PurchaseProfile&gt;</a></dt>
<dd><b>&lt;HomeProviderName&gt;</b></dd>
</dl>

## Syntax

``` syntax
<HomeProviderName>

  ProviderNameType

</HomeProviderName>
```

## Attributes and Elements


### Attributes

None.

### Child Elements

None.

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
<td>[DefaultProfile](element-defaultprofile.md)</td>
<td><p>Defines the default connection profile used by a subscriber to connect to a MNO. The Mobile Broadband service will use these connection settings without prompting the user for details.</p></td>
</tr>
<tr class="even">
<td>[PurchaseProfile](element-purchaseprofile.md)</td>
<td><p>Defines a purchase connection profile used by a subscriber to connect to a MNO.</p></td>
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
<td><p>http://www.microsoft.com/networking/CarrierControl/WWAN/v1</p></td>
</tr>
</tbody>
</table>

 

 



