﻿---
title: IManifestStream.AvailableTracks Property
TOCTitle: AvailableTracks Property
ms:assetid: ec5b3617-0399-4f8b-becd-59daed21480f
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ822865(v=VS.90)
ms:contentKeyID: 50079619
ms.date: 11/19/2012
mtps_version: v=VS.90
dev_langs:
- csharp
- c++
- jscript
---

# IManifestStream.AvailableTracks Property

**Applies to:** Windows Store apps only

Gets the available tracks in the current stream.

## Syntax

``` csharp
IVectorView<IManifestTrack> AvailableTracks { get; }
```

``` c++
property IVectorView<IManifestTrack^>^ AvailableTracks {
IVectorView<IManifestTrack^>^ get ();
}
```

``` jscript
function get AvailableTracks () : IVectorView<IManifestTrack>
```

## Property Value

List of available tracks.

## Requirements

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Minimum supported client</strong></p></td>
<td><p>Windows 8</p></td>
</tr>
<tr class="even">
<td><p><strong>Minimum supported server</strong></p></td>
<td><p>Not Supported</p></td>
</tr>
<tr class="odd">
<td><p><strong>Metadata</strong></p></td>
<td><p>Microsoft.Media.AdaptiveStreaming.winmd</p></td>
</tr>
</tbody>
</table>
