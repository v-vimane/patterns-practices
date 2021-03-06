---
TOCTitle: 'AddModule Method (String, String, String, InitializationMode, String[])'
Title: 'ModuleCatalog.AddModule Method (String, String, String, InitializationMode, String[]) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.AddModule(System.String,System.String,System.String,Microsoft.Practices.Prism.Modularity.InitializationMode,System.String[])'
ms:mtpsurl: 'addmodule-mthd-str-str-initializationmode-str.md'
---

# ModuleCatalog.AddModule Method (String, String, String, InitializationMode, String[])

Adds a groupless [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) to the catalog.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public ModuleCatalog AddModule(
	string moduleName,
	string moduleType,
	string refValue,
	InitializationMode initializationMode,
	params string[] dependsOn
)
```

### Parameters

*moduleName*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)   
Name of the module to be added.

*moduleType*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)   
[Type](http://msdn.microsoft.com/en-us/library/42892f65) of the module to be added.

*refValue*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)   
Reference to the location of the module to be added assembly.

*initializationMode*  
Type: [Microsoft.Practices.Prism.Modularity.InitializationMode](/patterns-practices/reference/initializationmode-enumeration-mspp-modularity)   
Stage on which the module to be added will be initialized.

*dependsOn*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)[]   
Collection of module names ([ModuleName](/patterns-practices/reference/moduleinfo-modulename-property-mspp-modularity)) of the modules on which the module to be added logically depends on.


# ModuleCatalog.AddModule Method (String, String, String, InitializationMode, String())

Adds a groupless [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) to the catalog.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Public Function AddModule ( 
	moduleName As String,
	moduleType As String,
	refValue As String,
	initializationMode As InitializationMode,
	ParamArray dependsOn As String()
) As ModuleCatalog
```

### Parameters

*moduleName*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)   
Name of the module to be added.

*moduleType*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)   
[Type](http://msdn.microsoft.com/en-us/library/42892f65) of the module to be added.

*refValue*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)   
Reference to the location of the module to be added assembly.

*initializationMode*  
Type: [Microsoft.Practices.Prism.Modularity.InitializationMode](/patterns-practices/reference/initializationmode-enumeration-mspp-modularity)   
Stage on which the module to be added will be initialized.

*dependsOn*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)()   
Collection of module names ([ModuleName](/patterns-practices/reference/moduleinfo-modulename-property-mspp-modularity)) of the modules on which the module to be added logically depends on.

### Return Value

Type: [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity)   
The same [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity) instance with the added module.

## See Also

[ModuleCatalog Class](/patterns-practices/reference/modulecatalog-class-mspp-modularity)  
[ModuleCatalog Members](/patterns-practices/reference/modulecatalog-members-mspp-modularity)  
[AddModule Overload](/patterns-practices/reference/addmodule-mthd-str-str-initializationmode-str)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  