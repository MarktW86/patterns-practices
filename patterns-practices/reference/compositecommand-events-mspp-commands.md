---
TOCTitle: CompositeCommand Events
Title: 'CompositeCommand Events (Microsoft.Practices.Prism.Commands)'
ms:assetid: 'Events.T:Microsoft.Practices.Prism.Commands.CompositeCommand'
ms:mtpsurl: 'compositecommand-events-mspp-commands.md'
---

# CompositeCommand Events

The [CompositeCommand](/patterns-practices/reference/compositecommand-class-mspp-commands) type exposes the following members.

## Events

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubevent.gif" alt="Public event"/></td>
<td><a href="/patterns-practices/reference/compositecommand-canexecutechanged-event-mspp-commands" data-raw-source="[CanExecuteChanged](/patterns-practices/reference/compositecommand-canexecutechanged-event-mspp-commands)">CanExecuteChanged</a></td>
<td><div class="summary">
Occurs when any of the registered commands raise <a href="http://msdn.microsoft.com/en-us/library/ms523106" data-raw-source="[CanExecuteChanged](http://msdn.microsoft.com/en-us/library/ms523106)">CanExecuteChanged</a>. You must keep a hard reference to the handler to avoid garbage collection and unexpected results. See remarks for more information.
</div></td>
</tr>
</tbody>
</table>

## See Also

[CompositeCommand Class](/patterns-practices/reference/compositecommand-class-mspp-commands)  
[Microsoft.Practices.Prism.Commands Namespace](/patterns-practices/reference/mspp-commands-namespace)  