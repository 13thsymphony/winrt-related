---
Description: Contains any errors from processing the Signature element from the last provisioning attempt.
Search.Product: eADQiWindows 10XVcnh
title: Signature
ms.assetid: 58a2b918-192d-41ee-879c-b739b498bff0
author: mcleblanc
ms.author: markl
keywords: windows 10, uwp, schema, mobile broadband schema


ms.topic: reference
ms.date: 04/05/2017
---

# Signature


Contains any errors from processing the [**Signature**](https://msdn.microsoft.com/library/windows/apps/hh868330) element from the last provisioning attempt.

## Element hierarchy

<dl>
<dt><a href="element-carrierprovisioningresult.md">&lt;CarrierProvisioningResult&gt;</a></dt>
<dd><b>&lt;Signature&gt;</b></dd>
</dl>

## Syntax

``` syntax
<Signature errorCode = token >

  <!-- Child elements -->
  Subject,
  Thumbprint

</Signature>
```

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
<td>Yes</td>
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
<td>[Subject](element-subject.md)</td>
<td><p>Contains the X.509 certificate subject field of the [<strong>Signature</strong>](https://msdn.microsoft.com/library/windows/apps/hh868330) element from the last provisioning attempt.</p></td>
</tr>
<tr class="even">
<td>[Thumbprint](element-thumbprint.md)</td>
<td><p>Contains the [<strong>SignatureValue</strong>](https://msdn.microsoft.com/library/windows/apps/hh868332) element of the [<strong>Signature</strong>](https://msdn.microsoft.com/library/windows/apps/hh868330) from the last provisioning attempt.</p></td>
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
<td>[CarrierProvisioningResult](element-carrierprovisioningresult.md)</td>
<td><p>Contains any errors from processing the [<strong>CarrierProvisioning</strong>](https://msdn.microsoft.com/library/windows/apps/hh868289) element from the last provisioning attempt. [<strong>CarrierProvisioningResult</strong>](element-carrierprovisioningresult.md) is the unique root element for the provisioning results.</p></td>
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
<td><p>http://www.microsoft.com/networking/CarrierControlResults/v1</p></td>
</tr>
</tbody>
</table>

 

 



