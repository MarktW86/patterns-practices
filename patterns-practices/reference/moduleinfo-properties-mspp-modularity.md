---
TOCTitle: ModuleInfo Properties
Title: 'ModuleInfo Properties (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'Properties.T:Microsoft.Practices.Prism.Modularity.ModuleInfo'
ms:mtpsurl: 'moduleinfo-properties-mspp-modularity.md'
---

# ModuleInfo Properties

The [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) type exposes the following members.

## Properties

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/moduleinfo-dependson-property-mspp-modularity" data-raw-source="[DependsOn](/patterns-practices/reference/moduleinfo-dependson-property-mspp-modularity)">DependsOn</a></td>
<td><div class="summary">
Gets or sets the list of modules that this module depends upon.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/moduleinfo-initializationmode-property-mspp-modularity" data-raw-source="[InitializationMode](/patterns-practices/reference/moduleinfo-initializationmode-property-mspp-modularity)">InitializationMode</a></td>
<td><div class="summary">
Specifies on which stage the Module will be initialized.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/moduleinfo-modulename-property-mspp-modularity" data-raw-source="[ModuleName](/patterns-practices/reference/moduleinfo-modulename-property-mspp-modularity)">ModuleName</a></td>
<td><div class="summary">
Gets or sets the name of the module.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/moduleinfo-moduletype-property-mspp-modularity" data-raw-source="[ModuleType](/patterns-practices/reference/moduleinfo-moduletype-property-mspp-modularity)">ModuleType</a></td>
<td><div class="summary">
Gets or sets the module <a href="http://msdn.microsoft.com/en-us/library/42892f65" data-raw-source="[Type](http://msdn.microsoft.com/en-us/library/42892f65)">Type</a>&#39;s AssemblyQualifiedName.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity" data-raw-source="[Ref](/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity)">Ref</a></td>
<td><div class="summary">
Reference to the location of the module assembly.
<div>
<h3 id="examples">Examples</h3>
The following are examples of valid <a href="/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity" data-raw-source="[Ref](/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity)">Ref</a> values: file://c:/MyProject/Modules/MyModule.dll for a loose DLL in WPF.
</div>
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/moduleinfo-state-property-mspp-modularity" data-raw-source="[State](/patterns-practices/reference/moduleinfo-state-property-mspp-modularity)">State</a></td>
<td><div class="summary">
Gets or sets the state of the <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity" data-raw-source="[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)">ModuleInfo</a> with regards to the module loading and initialization process.
</div></td>
</tr>
</tbody>
</table>

## See Also

[ModuleInfo Class](/patterns-practices/reference/moduleinfo-class-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  