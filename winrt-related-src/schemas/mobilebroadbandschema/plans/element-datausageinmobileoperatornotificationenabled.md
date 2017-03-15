---
Description: DataUsageInMobileOperatorNotificationEnabled
MS-HAID: Plans.element\_DataUsageInMobileOperatorNotificationEnabled
MSHAttr:
- PreferredSiteName:MSDN
- PreferredLib:/library/windows/apps
Search.Product: eADQiWindows 10XVcnh
title: DataUsageInMobileOperatorNotificationEnabled
ms.assetid: 232adaba-ec76-49a3-956c-438389548e60
author: mcleblanc
ms.author: markl
keywords: windows 10
---

# DataUsageInMobileOperatorNotificationEnabled


Indicates whether the [**NetworkOperatorNotificationTrigger**](https://msdn.microsoft.com/library/windows/apps/br224831) should include data usage notifications. If **true**, Windows raises this trigger when the data usage threshold is met.

## Element hierarchy

<dl>
<dt><a href="element-plan.md">&lt;Plan&gt;</a></dt>
<dd>
<dl>
<dt><a href="element-description.md">&lt;Description&gt;</a></dt>
<dd><b>&lt;DataUsageInMobileOperatorNotificationEnabled&gt;</b></dd>
</dl>
</dd>
</dl>

## Syntax

``` syntax
<DataUsageInMobileOperatorNotificationEnabled>

  boolean : "false"

</DataUsageInMobileOperatorNotificationEnabled>
```

### Key

`:`   default value
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
<td>[Description](element-description.md)</td>
<td><p>Defines plan information that specifies the subscriber's Mobile Network Operator (MNO) connection type.</p></td>
</tr>
</tbody>
</table>

 

## See also


[**NetworkOperatorNotificationTrigger**](https://msdn.microsoft.com/library/windows/apps/br224831)

## Requirements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Namespace</p></td>
<td><p>http://www.microsoft.com/networking/CarrierControl/Plans/v1</p></td>
</tr>
</tbody>
</table>

 

 



