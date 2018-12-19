﻿---
title: InstallerFile.TrackingUrl Property  (Microsoft.Web.PlatformInstaller)
TOCTitle: TrackingUrl Property
ms:assetid: P:Microsoft.Web.PlatformInstaller.InstallerFile.TrackingUrl
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.platforminstaller.installerfile.trackingurl(v=VS.90)
ms:contentKeyID: 22049661
ms.date: 05/02/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.PlatformInstaller.InstallerFile.TrackingUrl
- Microsoft.Web.PlatformInstaller.InstallerFile.get_TrackingUrl
dev_langs:
- CSharp
- JScript
- VB
- c++
api_location:
- Microsoft.Web.PlatformInstaller.dll
api_name:
- Microsoft.Web.PlatformInstaller.InstallerFile.get_TrackingUrl
- Microsoft.Web.PlatformInstaller.InstallerFile.TrackingUrl
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# TrackingUrl Property

Gets the URL used for tracking the current installer file.

**Namespace:**  [Microsoft.Web.PlatformInstaller](microsoft-web-platforminstaller-namespace.md)  
**Assembly:**  Microsoft.Web.PlatformInstaller (in Microsoft.Web.PlatformInstaller.dll)

## Syntax

``` vb
'Declaration
PublicReadOnlyPropertyTrackingUrlAsUriGet
'Usage
DiminstanceAsInstallerFileDimvalueAsUrivalue = instance.TrackingUrl
```

``` csharp
publicUriTrackingUrl { get; }
```

``` c++
public:
propertyUri^ TrackingUrl {
    Uri^ get ();
}
```

``` jscript
function getTrackingUrl () : Uri
```

#### Property Value

Type: Uri  
A Uri instance.  

## Permissions

  - Full trust for the immediate caller. This member cannot be used by partially trusted code. For more information, see <https://msdn.microsoft.com/en-us/library/8skskf63(v=vs.90)>.

## See Also

#### Reference

[InstallerFile Class](installerfile-class-microsoft-web-platforminstaller.md)

[InstallerFile Members](installerfile-members-microsoft-web-platforminstaller.md)

[Microsoft.Web.PlatformInstaller Namespace](microsoft-web-platforminstaller-namespace.md)
