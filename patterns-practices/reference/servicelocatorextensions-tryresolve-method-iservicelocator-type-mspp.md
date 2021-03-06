---
TOCTitle: 'TryResolve Method (IServiceLocator, Type)'
Title: 'ServiceLocatorExtensions.TryResolve Method (IServiceLocator, Type) (Microsoft.Practices.Prism)'
ms:assetid: 'M:Microsoft.Practices.Prism.ServiceLocatorExtensions.TryResolve(Microsoft.Practices.ServiceLocation.IServiceLocator,System.Type)'
ms:mtpsurl: 'servicelocatorextensions-tryresolve-method-iservicelocator-type-mspp.md'
---

# ServiceLocatorExtensions.TryResolve Method (IServiceLocator, Type)

Attempts to resolve specified type from the underlying IServiceLocator.

**Namespace:** [Microsoft.Practices.Prism](/patterns-practices/reference/mspp-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public static Object TryResolve(
	this IServiceLocator locator,
	Type type
)
```
### Parameters
*locator*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: IServiceLocator  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Locator to use in resolving.

*type*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type to resolve.

### Return Value

Type: [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
T or null

### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type IServiceLocator. When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

## Remarks

 This will return null on any ActivationException.
 
## Exceptions

| Exception                                                                             | Condition                                                                            |
|---------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) | Thrown when *locator* is **null**a null reference (**Nothing** in Visual Basic). |

```VB
'Declaration
<ExtensionAttribute> 
Public Shared Function TryResolve ( 
	locator As IServiceLocator,
	type As Type
) As Object
```

### Parameters
*locator*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: IServiceLocator   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Locator to use in resolving.

*type*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type to resolve.

### Return Value

Type: [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)   
T or null
### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type IServiceLocator. When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

## Remarks

 This will return null on any ActivationException.

## Exceptions


| Exception                                                                             | Condition                                                                            |
|---------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) | Thrown when *locator* is **Nothinga** null reference (**Nothing** in Visual Basic). |

## See Also

[ServiceLocatorExtensions Class](/patterns-practices/reference/servicelocatorextensions-class-mspp)  
[ServiceLocatorExtensions Members](/patterns-practices/reference/servicelocatorextensions-members-mspp)  
[TryResolve Overload](/patterns-practices/reference/servicelocatorextensions-tryresolve-method-mspp)  
[Microsoft.Practices.Prism Namespace](/patterns-practices/reference/mspp-namespace)  