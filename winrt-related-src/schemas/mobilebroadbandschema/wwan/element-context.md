---
Description: Context
MS-HAID: WWAN.element\_Context
MSHAttr:
- PreferredSiteName:MSDN
- PreferredLib:/library/windows/apps
Search.Product: eADQiWindows 10XVcnh
title: Context
ms.assetid: ddf2b145-59b3-46bf-a297-6992f00a06e0
author: mcleblanc
ms.author: markl
keywords: windows 10
---

# Context


Defines the parameters required to setup a data connection.

## Element hierarchy

<dl>
<dt><a href="element-defaultprofile.md">&lt;DefaultProfile&gt;</a></dt>
<dd><b>&lt;Context&gt;</b></dd>
</dl>
<dl>
<dt><a href="element-purchaseprofile.md">&lt;PurchaseProfile&gt;</a></dt>
<dd><b>&lt;Context&gt;</b></dd>
</dl>

## Syntax

``` syntax
<Context>

  <!-- Child elements -->
  AccessString?,
  UserLogonCred?,
  Compression?,
  AuthProtocol?

</Context>
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
<td>[AccessString](element-accessstring.md)</td>
<td><p>Defines the Access Point Name (APN) or dial string to be used to establish a data connection. Must be less than 100 characters.</p></td>
</tr>
<tr class="even">
<td>[AuthProtocol](element-authprotocol.md)</td>
<td><p>Defines the authentication protocol to be used for activating a Packet Data Protocol (PDP) context:</p>
<p></p>
<ul>
<li><strong>NONE</strong> - No authentication protocol.</li>
<li><strong>PAP</strong> - Unencrypted password authentication.</li>
<li><strong>CHAP</strong> - Challenge Handshake Authentication Protocol(CHAP).</li>
<li><strong>MsCHAPv2</strong> - Microsoft’s Challenge Handshake Authentication Protocol(CHAP) v2.0.</li>
</ul></td>
</tr>
<tr class="odd">
<td>[Compression](element-compression.md)</td>
<td><p>If <strong>ENABLE</strong>, the packet header and data transferred over the connection is compressed. Otherwise, <strong>DISABLE</strong>.</p></td>
</tr>
<tr class="even">
<td>[UserLogonCred](element-userlogoncred.md)</td>
<td><p>Defines logon credentials for a connection.</p></td>
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

 

 



