---
TOCTitle: GetObjectData Method
Title: 'ModularityException.GetObjectData Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModularityException.GetObjectData(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)'
ms:mtpsurl: 'modularityexception-getobjectdata-method-mspp-modularity.md'
---

# ModularityException.GetObjectData Method 

Sets the [SerializationInfo](http://msdn.microsoft.com/en-us/library/a9b6042e) with information about the exception.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public override void GetObjectData(
	SerializationInfo info,
	StreamingContext context
)
```

```VB
'Declaration
Public Overrides Sub GetObjectData ( 
	info As SerializationInfo,
	context As StreamingContext
)
```

### Parameters

*info*  
Type: [System.Runtime.Serialization.SerializationInfo](http://msdn.microsoft.com/en-us/library/a9b6042e)  
The [SerializationInfo](http://msdn.microsoft.com/en-us/library/a9b6042e) that holds the serialized object data about the exception being thrown.

*context*  
Type: [System.Runtime.Serialization.StreamingContext](http://msdn.microsoft.com/en-us/library/t16abws5)  
The [StreamingContext](http://msdn.microsoft.com/en-us/library/t16abws5) that contains contextual information about the source or destination.

### Implements

[ISerializable.GetObjectData(SerializationInfo, StreamingContext)](http://msdn.microsoft.com/en-us/library/27cxsdk6)  
[_Exception.GetObjectData(SerializationInfo, StreamingContext)](http://msdn.microsoft.com/en-us/library/854b9522)

## See Also

[ModularityException Class](/patterns-practices/reference/modularityexception-class-mspp-modularity)  
[ModularityException Members](/patterns-practices/reference/modularityexception-members-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  