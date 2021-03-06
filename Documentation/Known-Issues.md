<div class="wikidoc">
<h6>V7 (CRM 2015) Known Issues</h6>
<table>
<tbody>
<tr>
<th>Issue</th>
<th>Exception</th>
<th>Workaround</th>
<th>Fix Status</th>
</tr>
<tr>
<td>7.1.1&#43; SDK Core Assemblies not compatible &nbsp;</td>
<td>
<p><em><strong>System.MissingMethodException</strong> SecurityTokenResponse.get_Response.&nbsp;
</em></p>
<p><em>The issue occurs when using a version of our library build targeting SDK core&nbsp;assemblies package v7.1.0 or earlier in combination with SDK core assemblies v7.1.1 or newer.</em></p>
</td>
<td>Downgrade your Microsoft.CrmSdk.CoreAssemblies package to v7.1.0 or earlier</td>
<td>Upgrade to our Microsoft.Pfe.Xrm.CoreV8 package</td>
</tr>
</tbody>
</table>
<h6>V6 (CRM 2013) Known Issues</h6>
<table>
<tbody>
<tr>
<th>Issue</th>
<th>Exception</th>
<th>Workaround</th>
<th>Fix Status</th>
</tr>
<tr>
<td>Thread-safety issue in Microsoft.Xrm.Sdk.dll IServiceConfiguration CreateLocalChannelFactory() method encountered when ProxyTypesBehavior is enabled</td>
<td><em><strong>System.InvalidOperationException</strong> Collection was modified; enumeration operation may not execute.</em></td>
<td>None</td>
<td>UR2 / SDK v6.0</td>
</tr>
<tr>
<td>SQL Deadlock caused by ActivityFeeds plug-in</td>
<td><em><strong>FaultException&lt;OrganizationServiceFault&gt;</strong> There is no active transaction. This error is usually caused by custom plug-ins that ignore errors from service calls and continue processing</em></td>
<td>Disable post-configuration plug-in step</td>
<td>Fix for Leo postponed</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<h6>V5 (CRM 2011) Known Issues</h6>
<table>
<tbody>
<tr>
<th>Issue</th>
<th>Exception</th>
<th>Workaround</th>
<th>Fix Status</th>
</tr>
<tr>
<td>Thread-safety issue in Microsoft.Xrm.Sdk.dll IServiceConfiguration CreateLocalChannelFactory() method encountered when ProxyTypesBehavior is enabled</td>
<td><em><strong>System.InvalidOperationException</strong> Collection was modified; enumeration operation may not execute.</em></td>
<td>None</td>
<td>UR16 (Current SDK v5.0.18 has <u>NOT</u> been updated!!)</td>
</tr>
<tr>
<td>SQL Deadlock for parallelized deletes when entity participates as an ActivityParty</td>
<td><em><strong>SqlException</strong> Deadlock victim statement: UPDATE [ActivityPartyBase] SET [IsPartyDeleted] = 1 WHERE ([PartyId] = '[GUID]' AND [PartyObjectTypeCode] = 3)</em></td>
<td>None</td>
<td>Investigating</td>
</tr>
</tbody>
</table>
<p><br>
<br>
<br>
<br>
</p>
</div><div class="ClearBoth"></div>
