---
TOCTitle: 'AddModule Method (Type, String[])'
Title: 'ModuleCatalog.AddModule Method (Type, String[]) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.AddModule(System.Type,System.String[])'
ms:mtpsurl: 'addmodule-mthd-str-str-initializationmode-str.md'
---

# ModuleCatalog.AddModule Method (Type, String[])

Adds a groupless [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) to the catalog.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public ModuleCatalog AddModule(
	Type moduleType,
	params string[] dependsOn
)
```

### Parameters

*moduleType*  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)  
[Type](http://msdn.microsoft.com/en-us/library/42892f65) of the module to be added.

*dependsOn*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)[]  
Collection of module names ([ModuleName](/patterns-practices/reference/moduleinfo-modulename-property-mspp-modularity)) of the modules on which the module to be added logically depends on.


# ModuleCatalog.AddModule Method (Type, String())

Adds a groupless [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) to the catalog.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Public Function AddModule ( 
	moduleType As Type,
	ParamArray dependsOn As String()
) As ModuleCatalog
```

### Parameters

*moduleType*  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)  
[Type](http://msdn.microsoft.com/en-us/library/42892f65) of the module to be added.

*dependsOn*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)()  
Collection of module names ([ModuleName](/patterns-practices/reference/moduleinfo-modulename-property-mspp-modularity)) of the modules on which the module to be added logically depends on.

### Return Value

Type: [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity)  
The same [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity) instance with the added module.

## See Also

[ModuleCatalog Class](/patterns-practices/reference/modulecatalog-class-mspp-modularity)  
[ModuleCatalog Members](/patterns-practices/reference/modulecatalog-members-mspp-modularity)  
[AddModule Overload](/patterns-practices/reference/modulecatalog-addmodule-method-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  

