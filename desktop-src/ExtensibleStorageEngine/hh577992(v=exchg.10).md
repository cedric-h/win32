---
title: JET_RECSIZE.Equals method (JET_RECSIZE) (Microsoft.Isam.Esent.Interop.Vista)
TOCTitle: Equals method (JET_RECSIZE)
ms:assetid: M:Microsoft.Isam.Esent.Interop.Vista.JET_RECSIZE.Equals(Microsoft.Isam.Esent.Interop.Vista.JET_RECSIZE)
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.isam.esent.interop.vista.jet_recsize.equals(v=EXCHG.10)
ms:contentKeyID: 39511266
ms.date: 07/30/2014
mtps_version: v=EXCHG.10
dev_langs:
- vb
- csharp
api_name: 
- Microsoft.Isam.Esent.Interop.Vista.JET_RECSIZE.Equals
topic_type: 
- kbSyntax
- apiref
api_type: 
- Managed
api_location: 
- Microsoft.Isam.Esent.Interop.dll
ROBOTS: INDEX,FOLLOW

---

# JET\_RECSIZE.Equals method (JET\_RECSIZE)

Returns a value indicating whether this instance is equal to another instance.

**Namespace:**  [Microsoft.Isam.Esent.Interop.Vista](hh558039\(v=exchg.10\).md)  
**Assembly:**  Microsoft.Isam.Esent.Interop (in Microsoft.Isam.Esent.Interop.dll)

## Syntax

``` vb
'Declaration
Public Function Equals ( _
    other As JET_RECSIZE _
) As Boolean
'Usage
Dim instance As JET_RECSIZE
Dim other As JET_RECSIZE
Dim returnValue As Boolean

returnValue = instance.Equals(other)
```

``` csharp
public bool Equals(
    JET_RECSIZE other
)
```

#### Parameters

  - other  
    Type: [Microsoft.Isam.Esent.Interop.Vista.JET\_RECSIZE](hh557010\(v=exchg.10\).md)  
    
    An object to compare with this instance.

#### Return value

Type: [System.Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)  
True if the two instances are equal.  

#### Implements

[IEquatable\<T\>.Equals(T)](http://msdn2.microsoft.com/en-us/library/ms131190)  

## See also

#### Reference

[JET\_RECSIZE structure](hh557010\(v=exchg.10\).md)

[JET\_RECSIZE members](hh557127\(v=exchg.10\).md)

[Equals overload](hh565292\(v=exchg.10\).md)

[Microsoft.Isam.Esent.Interop.Vista namespace](hh558039\(v=exchg.10\).md)
