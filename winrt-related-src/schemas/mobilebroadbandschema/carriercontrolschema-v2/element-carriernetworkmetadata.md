---
Description: CarrierNetworkMetadata
MS-HAID: CarrierControlSchema\_v2.element\_CarrierNetworkMetadata
MSHAttr:
- PreferredSiteName:MSDN
- PreferredLib:/library/windows/apps
Search.Product: eADQiWindows 10XVcnh
title: CarrierNetworkMetadata
ms.assetid: 6b8fa3df-5138-475d-ac95-305c273730fe
author: mcleblanc
ms.author: markl
keywords: windows 10, uwp, schema, mobile broadband schema
---

# CarrierNetworkMetadata


Defines the network properties and settings in a subscriber's carrier provisioning file.

## Element hierarchy

<dl>
<dt><a href="element-extensions-v2.md">&lt;Extensions_v2&gt;</a></dt>
<dd><b>&lt;CarrierNetworkMetadata&gt;</b></dd>
</dl>

## Syntax

``` syntax
<CarrierNetworkMetadata>

  <!-- Child elements -->
  NetworkSettings?,
  DataClassFriendlyNames?,
  CustomerSupportPhoneNumber?

</CarrierNetworkMetadata>
```

### Key

`?`   optional (zero or one)

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
<td>[CustomerSupportPhoneNumber](element-customersupportphonenumber.md)</td>
<td><p>Defines the phone number for customer support in a subscriber's carrier provisioning file.</p></td>
</tr>
<tr class="even">
<td>[DataClassFriendlyNames](element-dataclassfriendlynames.md)</td>
<td><p>Defines class friendly names for the standard or protocol used for mobile network data in a subscriber's carrier provisioning file.</p></td>
</tr>
<tr class="odd">
<td>[NetworkSettings](element-networksettings.md)</td>
<td><p>Defines the network settings in a subscriber's carrier provisioning file.</p></td>
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
<td>[Extensions_v2](element-extensions-v2.md)</td>
<td><p>Defines additional properties and settings in a subscriber's carrier provisioning file. [<strong>Extensions_v2</strong>](element-extensions-v2.md) is the unique root element of the [CarrierControlSchema_v2](schema-root.md) provisioning file.</p></td>
</tr>
</tbody>
</table>

 

## See also


[CarrierControlSchema schema](https://msdn.microsoft.com/library/windows/apps/hh868312)

[CarrierControlSchema\_v2 schema](schema-root.md)

## Requirements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Namespace</p></td>
<td><p>http://www.microsoft.com/networking/CarrierControl/v2</p></td>
</tr>
</tbody>
</table>

 

 



