---
title: JET_BKLOGTIME.Equals method (JET_BKLOGTIME) (Microsoft.Isam.Esent.Interop)
TOCTitle: Equals method (JET_BKLOGTIME)
ms:assetid: M:Microsoft.Isam.Esent.Interop.JET_BKLOGTIME.Equals(Microsoft.Isam.Esent.Interop.JET_BKLOGTIME)
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.isam.esent.interop.jet_bklogtime.equals(v=EXCHG.10)
ms:contentKeyID: 39516064
ms.date: 07/30/2014
mtps_version: v=EXCHG.10
dev_langs:
- vb
- csharp
api_name: 
- Microsoft.Isam.Esent.Interop.JET_BKLOGTIME.Equals
topic_type: 
- apiref
- kbSyntax
api_type: 
- Managed
api_location: 
- Microsoft.Isam.Esent.Interop.dll
ROBOTS: INDEX,FOLLOW

---

# JET\_BKLOGTIME.Equals method (JET\_BKLOGTIME)

Returns a value indicating whether this instance is equal to another instance.

**Namespace:**  [Microsoft.Isam.Esent.Interop](hh596136\(v=exchg.10\).md)  
**Assembly:**  Microsoft.Isam.Esent.Interop (in Microsoft.Isam.Esent.Interop.dll)

## Syntax

``` vb
'Declaration
Public Function Equals ( _
    other As JET_BKLOGTIME _
) As Boolean
'Usage
Dim instance As JET_BKLOGTIME
Dim other As JET_BKLOGTIME
Dim returnValue As Boolean

returnValue = instance.Equals(other)
```

``` csharp
public bool Equals(
    JET_BKLOGTIME other
)
```

#### Parameters

  - other  
    Type: [Microsoft.Isam.Esent.Interop.JET\_BKLOGTIME](hh557662\(v=exchg.10\).md)  
    
    An instance to compare with this instance.

#### Return value

Type: [System.Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)  
True if the two instances are equal.  

#### Implements

[IEquatable\<T\>.Equals(T)](http://msdn2.microsoft.com/en-us/library/ms131190)  

## See also

#### Reference

[JET\_BKLOGTIME structure](hh557662\(v=exchg.10\).md)

[JET\_BKLOGTIME members](hh565503\(v=exchg.10\).md)

[Equals overload](hh566806\(v=exchg.10\).md)

[Microsoft.Isam.Esent.Interop namespace](hh596136\(v=exchg.10\).md)
