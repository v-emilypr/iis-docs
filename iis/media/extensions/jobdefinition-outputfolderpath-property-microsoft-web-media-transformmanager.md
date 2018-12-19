﻿---
title: JobDefinition.OutputFolderPath Property  (Microsoft.Web.Media.TransformManager)
TOCTitle: OutputFolderPath Property
ms:assetid: P:Microsoft.Web.Media.TransformManager.JobDefinition.OutputFolderPath
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.media.transformmanager.jobdefinition.outputfolderpath(v=VS.90)
ms:contentKeyID: 35521147
ms.date: 06/14/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Media.TransformManager.JobDefinition.get_OutputFolderPath
- Microsoft.Web.Media.TransformManager.JobDefinition.OutputFolderPath
- Microsoft.Web.Media.TransformManager.JobDefinition.set_OutputFolderPath
dev_langs:
- CSharp
- JScript
- VB
- FSharp
- c++
api_location:
- Microsoft.Web.Media.TransformManager.Common.dll
api_name:
- Microsoft.Web.Media.TransformManager.JobDefinition.get_OutputFolderPath
- Microsoft.Web.Media.TransformManager.JobDefinition.OutputFolderPath
- Microsoft.Web.Media.TransformManager.JobDefinition.set_OutputFolderPath
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# OutputFolderPath Property

Gets or sets the output folder path for a job. This type/member supports the IIS Transform Manager infrastructure and is not intended to be used directly from your code.

**Namespace:**  [Microsoft.Web.Media.TransformManager](microsoft-web-media-transformmanager-namespace.md)  
**Assembly:**  Microsoft.Web.Media.TransformManager.Common (in Microsoft.Web.Media.TransformManager.Common.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
PublicPropertyOutputFolderPathAsStringGetSet
'Usage
DiminstanceAsJobDefinitionDimvalueAsStringvalue = instance.OutputFolderPath

instance.OutputFolderPath = value
```

``` csharp
[DataMemberAttribute]
publicstringOutputFolderPath { get; set; }
```

``` c++
[DataMemberAttribute]
public:
propertyString^ OutputFolderPath {
    String^ get ();
    voidset (String^ value);
}
```

``` fsharp
[<DataMemberAttribute>]
memberOutputFolderPath : stringwithget, set
```

``` jscript
function getOutputFolderPath () : Stringfunction setOutputFolderPath (value : String)
```

#### Property Value

Type: [System. . :: . .String](https://msdn.microsoft.com/en-us/library/s1wwdcbf\(v=vs.90\))  
The output folder path for a job.  

## See Also

#### Reference

[JobDefinition Class](jobdefinition-class-microsoft-web-media-transformmanager.md)

[Microsoft.Web.Media.TransformManager Namespace](microsoft-web-media-transformmanager-namespace.md)
