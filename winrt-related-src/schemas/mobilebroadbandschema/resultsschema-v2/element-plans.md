---
Description: Contains any errors from processing the Plans element from the last provisioning attempt.

Search.Product: eADQiWindows 10XVcnh
title: Plans
ms.assetid: f6bdcd56-748b-4d9e-86fd-10467df0e7f3
author: mcleblanc
ms.author: markl
keywords: windows 10, uwp, schema, mobile broadband schema


ms.topic: reference
ms.date: 04/05/2017
---

# Plans


Contains any errors from processing the [**Plans**](https://msdn.microsoft.com/library/windows/apps/hh868299) element from the last provisioning attempt.

## Element hierarchy

<dl>
<dt><a href="element-carrierprovisioningresult.md">&lt;CarrierProvisioningResult&gt;</a></dt>
<dd><b>&lt;Plans&gt;</b></dd>
</dl>

## Syntax

``` syntax
<Plans errorCode? = token >

  <!-- Child elements -->
  Plan+

</Plans>
```

### Key

`?`   optional (zero or one)
`+`   required (one or more)

## Attributes and Elements


### Attributes

<table>
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th>Attribute</th>
<th>Description</th>
<th>Data type</th>
<th>Required</th>
<th>Default value</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>errorCode</strong></td>
<td><p>S_OK if schema processed successfully. Otherwise, the HRESULT returned during the provisioning attempt formatted as eight hexadecimal characters [0-9a-f].</p></td>
<td>token</td>
<td>No</td>
<td></td>
</tr>
</tbody>
</table>

 

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
<td><a href="element-plan.md">Plan</a> </td>
<td><p>Contains any errors from processing a <a href="https://msdn.microsoft.com/library/windows/apps/hh868298"><strong>Plan</strong></a>  element from the last provisioning attempt.</p></td>
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
<td><a href="element-carrierprovisioningresult.md">CarrierProvisioningResult</a> </td>
<td><p>Contains any errors from processing the <a href="https://msdn.microsoft.com/library/windows/apps/hh868289"><strong>CarrierProvisioning</strong></a>  element from the last provisioning attempt. <a href="https://msdn.microsoft.com/library/windows/apps/hh868380"><strong>CarrierProvisioningResult</strong></a> is the unique root element for the provisioning results.</p></td>
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
<td><p>http://www.microsoft.com/networking/CarrierControlResults/v2</p></td>
</tr>
</tbody>
</table>

 

 



