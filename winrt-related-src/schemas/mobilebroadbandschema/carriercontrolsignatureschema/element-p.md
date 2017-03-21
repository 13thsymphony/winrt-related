---
Description: Defines a prime modulus meeting the DSAwithSHA1 requirements as specified in XML DSIG.
Search.Product: eADQiWindows 10XVcnh
title: P
ms.assetid: d2720356-bd59-40bb-bb0f-9113f5d47010
author: mcleblanc
ms.author: markl
keywords: windows 10, uwp, schema, mobile broadband schema
---

# P


Defines a prime modulus meeting the [DSAwithSHA1](http://www.w3.org/2000/09/xmldsig#dsa-sha1 ) requirements as specified in [XML DSIG](http://www.w3.org/TR/xmldsig-core/).

## Element hierarchy

<dl>
<dt><a href="element-signature.md">&lt;Signature&gt;</a></dt>
<dd>
<dl>
<dt><a href="element-keyinfo.md">&lt;KeyInfo&gt;</a></dt>
<dd>
<dl>
<dt><a href="element-keyvalue.md">&lt;KeyValue&gt;</a></dt>
<dd>
<dl>
<dt><a href="element-dsakeyvalue.md">&lt;DSAKeyValue&gt;</a></dt>
<dd><b>&lt;P&gt;</b></dd>
</dl>
</dd>
</dl>
</dd>
</dl>
</dd>
</dl>

## Syntax

``` syntax
<P>

  base64Binary

</P>
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
<td>[DSAKeyValue](element-dsakeyvalue.md)</td>
<td><p>Defines a Digital Signature Algorithm (DSA) public key as specified in [XML DSIG](http://www.w3.org/TR/xmldsig-core/).</p></td>
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
<td><p>http://www.w3.org/2000/09/xmldsig#</p></td>
</tr>
</tbody>
</table>

 

 



