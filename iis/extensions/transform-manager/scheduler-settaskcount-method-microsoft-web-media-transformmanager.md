---
title: Scheduler.SetTaskCount Method  (Microsoft.Web.Media.TransformManager)
TOCTitle: SetTaskCount Method
ms:assetid: M:Microsoft.Web.Media.TransformManager.Scheduler.SetTaskCount(System.String,System.Int32)
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.media.transformmanager.scheduler.settaskcount(v=VS.90)
ms:contentKeyID: 35520714
ms.date: 06/14/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Media.TransformManager.Scheduler.SetTaskCount
dev_langs:
- CSharp
- JScript
- VB
- FSharp
- c++
api_location:
- Microsoft.Web.Media.TransformManager.Common.dll
api_name:
- Microsoft.Web.Media.TransformManager.Scheduler.SetTaskCount
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# SetTaskCount Method

Sets the task count for the specified job.

**Namespace:**  [Microsoft.Web.Media.TransformManager](microsoft-web-media-transformmanager-namespace.md)  
**Assembly:**  Microsoft.Web.Media.TransformManager.Common (in Microsoft.Web.Media.TransformManager.Common.dll)

## Syntax

``` vb
'Declaration

  Public MustOverride Sub SetTaskCount ( _
    jobInstanceId As String, _
    taskCount As Integer _
)
'Usage

  Dim instance As Scheduler
Dim jobInstanceId As String
Dim taskCount As Integer

instance.SetTaskCount(jobInstanceId, _
    taskCount)
```

``` csharp
  public abstract void SetTaskCount(
    string jobInstanceId,
    int taskCount
)
```

``` c++
  public:
virtual void SetTaskCount(
    String^ jobInstanceId, 
    int taskCount
) abstract
```

``` fsharp
  abstract SetTaskCount : 
        jobInstanceId:string * 
        taskCount:int -> unit 
```

``` jscript
  public abstract function SetTaskCount(
    jobInstanceId : String, 
    taskCount : int
)
```

#### Parameters

  - jobInstanceId  
    Type: [System. . :: . .String](https://msdn.microsoft.com/en-us/library/s1wwdcbf\(v=vs.90\))  
    The ID of the job.  

<!-- end list -->

  - taskCount  
    Type: [System. . :: . .Int32](https://msdn.microsoft.com/en-us/library/td2s409d\(v=vs.90\))  
    The number of tasks.  

## See Also

#### Reference

[Scheduler Class](scheduler-class-microsoft-web-media-transformmanager.md)

[Microsoft.Web.Media.TransformManager Namespace](microsoft-web-media-transformmanager-namespace.md)
