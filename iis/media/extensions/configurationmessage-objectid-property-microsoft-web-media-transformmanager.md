﻿---
title: ConfigurationMessage.ObjectId Property  (Microsoft.Web.Media.TransformManager)
TOCTitle: ObjectId Property
ms:assetid: P:Microsoft.Web.Media.TransformManager.ConfigurationMessage.ObjectId
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.media.transformmanager.configurationmessage.objectid(v=VS.90)
ms:contentKeyID: 35520624
ms.date: 06/14/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Media.TransformManager.ConfigurationMessage.set_ObjectId
- Microsoft.Web.Media.TransformManager.ConfigurationMessage.get_ObjectId
- Microsoft.Web.Media.TransformManager.ConfigurationMessage.ObjectId
dev_langs:
- CSharp
- JScript
- VB
- FSharp
- c++
api_location:
- Microsoft.Web.Media.TransformManager.Common.dll
api_name:
- Microsoft.Web.Media.TransformManager.ConfigurationMessage.get_ObjectId
- Microsoft.Web.Media.TransformManager.ConfigurationMessage.ObjectId
- Microsoft.Web.Media.TransformManager.ConfigurationMessage.set_ObjectId
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# ObjectId Property

Gets or sets the ID of configuration object.

**Namespace:**  [Microsoft.Web.Media.TransformManager](microsoft-web-media-transformmanager-namespace.md)  
**Assembly:**  Microsoft.Web.Media.TransformManager.Common (in Microsoft.Web.Media.TransformManager.Common.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
PublicPropertyObjectIdAsStringGetSet
'Usage
DiminstanceAsConfigurationMessageDimvalueAsStringvalue = instance.ObjectId

instance.ObjectId = value
```

``` csharp
[DataMemberAttribute]
publicstringObjectId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
propertyString^ ObjectId {
    String^ get ();
    voidset (String^ value);
}
```

``` fsharp
[<DataMemberAttribute>]
memberObjectId : stringwithget, set
```

``` jscript
function getObjectId () : Stringfunction setObjectId (value : String)
```

#### Property Value

Type: [System. . :: . .String](https://msdn.microsoft.com/en-us/library/s1wwdcbf\(v=vs.90\))  
The ID of configuration object.  

## See Also

#### Reference

[ConfigurationMessage Class](configurationmessage-class-microsoft-web-media-transformmanager.md)

[Microsoft.Web.Media.TransformManager Namespace](microsoft-web-media-transformmanager-namespace.md)
