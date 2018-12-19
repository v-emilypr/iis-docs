﻿---
title: DeploymentAgentWorkerRequest.QueryString Property  (Microsoft.Web.Deployment)
TOCTitle: QueryString Property
ms:assetid: P:Microsoft.Web.Deployment.DeploymentAgentWorkerRequest.QueryString
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.deployment.deploymentagentworkerrequest.querystring(v=VS.90)
ms:contentKeyID: 20208906
ms.date: 05/02/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Deployment.DeploymentAgentWorkerRequest.QueryString
- Microsoft.Web.Deployment.DeploymentAgentWorkerRequest.get_QueryString
dev_langs:
- CSharp
- JScript
- VB
- c++
api_location:
- Microsoft.Web.Deployment.dll
api_name:
- Microsoft.Web.Deployment.DeploymentAgentWorkerRequest.get_QueryString
- Microsoft.Web.Deployment.DeploymentAgentWorkerRequest.QueryString
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# QueryString Property

Get a string that represents the query string for the current [DeploymentAgentWorkerRequest](deploymentagentworkerrequest-class-microsoft-web-deployment.md) object.

**Namespace:**  [Microsoft.Web.Deployment](microsoft-web-deployment-namespace.md)  
**Assembly:**  Microsoft.Web.Deployment (in Microsoft.Web.Deployment.dll)

## Syntax

``` vb
'Declaration
PublicMustOverrideReadOnlyPropertyQueryStringAsString
'Usage
DiminstanceAsDeploymentAgentWorkerRequestDimvalueAsStringvalue = instance.QueryString
```

``` csharp
publicabstractstringQueryString { get; }
```

``` c++
public:
virtualpropertyString^ QueryString {
    String^ get () abstract;
}
```

``` jscript
abstractfunction getQueryString () : String
```

#### Property Value

Type: [System. . :: . .String](https://msdn.microsoft.com/en-us/library/s1wwdcbf\(v=vs.90\))  
A string that represents the query string for the current [DeploymentAgentWorkerRequest](deploymentagentworkerrequest-class-microsoft-web-deployment.md) object.  

## Permissions

  - Full trust for the immediate caller. This member cannot be used by partially trusted code. For more information, see [Using Libraries from Partially Trusted Code](https://msdn.microsoft.com/en-us/library/8skskf63\(v=vs.90\)).

## See Also

#### Reference

[DeploymentAgentWorkerRequest Class](deploymentagentworkerrequest-class-microsoft-web-deployment.md)

[Microsoft.Web.Deployment Namespace](microsoft-web-deployment-namespace.md)
