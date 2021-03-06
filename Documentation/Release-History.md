<div class="wikidoc">
<h3>Release History</h3>
<table>
<tbody>
<tr>
<th style="text-align:center">Version</th>
<th style="text-align:center">Date</th>
<th style="text-align:center">Type</th>
<th style="text-align:left">Notes</th>
<th style="text-align:center">Links</th>
</tr>
<tr>
<td style="text-align:center">1612.1</td>
<td style="text-align:center">12/01/16</td>
<td style="text-align:center">
<p>Build</p>
</td>
<td>
<p><strong>&nbsp;Features</strong><br>
-&nbsp;<a href="https://pfexrmcore.codeplex.com/workitem/1670">#1670</a>:&nbsp;Add extensions methods to FetchExpression to extract paging cookie and current page<br>
-&nbsp;<a href="https://pfexrmcore.codeplex.com/workitem/1669">#1669</a>:&nbsp;Add extension method to get current page number from the EntityCollection paging cookie</p>
<p><strong>Bug Fixes</strong><br>
-&nbsp;<a href="https://pfexrmcore.codeplex.com/workitem/1668">#1668</a>:&nbsp;RetrieveMultiple extension method EntityCollection is not returning last page details (e.g. MoreRecords, PagingCookie, etc.)<br>
-&nbsp;<a href="https://pfexrmcore.codeplex.com/workitem/1667">#1667</a>:&nbsp;Existing PagingCookie is being ignored in RetrieveMultiple extension methods</p>
</td>
<td style="text-align:center"><a href="https://pfexrmcore.codeplex.com/releases/view/629957">download</a></td>
</tr>
<tr>
<td style="text-align:center">1611.1</td>
<td style="text-align:center">11/03/16</td>
<td style="text-align:center">
<p>Build</p>
</td>
<td>
<p><strong>&nbsp;Features</strong><br>
-&nbsp;<a href="https://pfexrmcore.codeplex.com/workitem/1665">#1665</a>: Provide call argument to limit RetrieveMultiple all pages query to max # of records</p>
<p><strong>Bug Fixes</strong><br>
-&nbsp;<a href="https://pfexrmcore.codeplex.com/workitem/1664">#1664</a>: BatchExtensions AsBatches() method prone to OutOfMemoryException as collection sizes increase</p>
<p><strong>Changed</strong><br>
-&nbsp;Release v8 package targeting CRM 2016 Update 1 SDK assemblies (8.1)&nbsp;</p>
</td>
<td style="text-align:center"><a href="https://pfexrmcore.codeplex.com/releases/view/629546">download</a></td>
</tr>
<tr>
<td style="text-align:center">1603.1&nbsp;</td>
<td style="text-align:center">3/25/16&nbsp;</td>
<td style="text-align:center">
<p>&nbsp;Build</p>
</td>
<td>
<p><strong>&nbsp;Features</strong><br>
- #1636: Implement extension methods for converting request collections into ExecuteMultipleRequest batches</p>
<p><strong>Bug Fixes</strong><br>
- #1626: MissingMethodException() prevents upgrade of CrmSdk package to incompatible version (7.1.1 and newer)</p>
<p><strong>Changed</strong><br>
- #1639: Release v8 package targeting CRM 2016 SDK assemblies</p>
</td>
<td style="text-align:center"><a href="https://pfexrmcore.codeplex.com/releases/view/620666">download</a>&nbsp;</td>
</tr>
<tr>
<td style="text-align:center">1506.0</td>
<td style="text-align:center">6/11/15</td>
<td style="text-align:center">
<p>Build&nbsp;</p>
</td>
<td>
<p><strong>Features<br>
</strong>- #1592: Provide property on XrmServiceManager classes to get current endpoint address<br>
- #1590: Provide property on&nbsp;XrmServiceManager classes to determine underlying authentication type of endpoint<br>
- #1579:&nbsp;V5 doesn't have a class XrmServiceUriFactory (merged fixes/features from V6/V7 to V5 for full feature parity)<strong>&nbsp;</strong></p>
<p><strong>Bug Fixes<br>
</strong>- #1591: MessageSecurityException encountered during token refresh for on-premise claims</p>
</td>
<td style="text-align:center"><a href="https://pfexrmcore.codeplex.com/releases/view/615676">download</a></td>
</tr>
<tr>
<td style="text-align:center">1504.0</td>
<td style="text-align:center">4/24/15</td>
<td style="text-align:center">
<p>&nbsp;Build</p>
</td>
<td>
<p><strong>Bug Fixes</strong><br>
- #1583: RetrieveMultiple extension methods do not handle top count scenario properly<strong>&nbsp;</strong></p>
</td>
<td style="text-align:center"><a href="https://pfexrmcore.codeplex.com/releases/view/614645">download</a></td>
</tr>
<tr>
<td style="text-align:center">1503.0</td>
<td style="text-align:center">2/23/15</td>
<td style="text-align:center">
<p>&nbsp;Build</p>
</td>
<td>
<p><strong>&nbsp;Features<br>
</strong>- #1518: Handle exceptions in parallel iteration body so that all iterations can be processed</p>
</td>
<td style="text-align:center"><a href="https://pfexrmcore.codeplex.com/releases/view/611955">download</a></td>
</tr>
<tr>
<td style="text-align:center">1502.0</td>
<td style="text-align:center">1/30/15</td>
<td style="text-align:center">
<p>Major</p>
</td>
<td>
<p><strong>&nbsp;</strong><strong>Features</strong><br>
- #1560: Update library to target CRM 2015 SDK assemblies and .NET 4.5.2<br>
- #1559: Add utility class for create XRM service endpoint Uri's</p>
<p><strong>Bug Fixes</strong><br>
- None.</p>
<p><strong>Changed</strong><br>
- Moved remaining service uri string constants to XrmServiceUriFactory class<br>
- Moved static discovery.svc Uri fields to XrmServiceUriFactory class<br>
- ParallelServiceProxy methods that returned IList&lt;T&gt; now return IEnumerable&lt;T&gt;</p>
<p><strong>Deprecated</strong><br>
- None</p>
<p><strong>Removed</strong><br>
- Unnecessary XrmServiceManager uri format string constants<br>
- IList&lt;QueryBase&gt; RetrieveMultiple methods<br>
- XmlDocument GetXml(this FetchExpression fe) method<br>
- ThreadLocalServiceProxy class<br>
- OrganizationDataServiceManager class</p>
</td>
<td style="text-align:center">&nbsp;<a href="https://pfexrmcore.codeplex.com/releases/view/611188">download</a></td>
</tr>
<tr>
<td style="text-align:center">1409.0</td>
<td style="text-align:center">9/8/2014</td>
<td style="text-align:center">Build</td>
<td>
<p><strong>Features<br>
</strong>- #1475: Replace XmlDocument with XElement implementation for FetchExpression query extension methods<br>
- #1494: Provide parallel methods that accept and return keyed collections (IDictionary&lt;TKey, TValue&gt;) so that requests can be correlated to their results. Create, RetrieveMultiple, and Execute methods. Other requests now accept broader IEnumerable&lt;T&gt;
 rather than IList&lt;T&gt;.<br>
- #1495: Add Execute&lt;TRequest, TResponse&gt; methods to ParallelDiscoveryServiceProxy class<strong><br>
<br>
<strong>Bug Fixes</strong><br>
</strong>- #1491: Removed page size override in RetrieveMultiple extension methods. Defers to page size specified in query argument or establishes a default.<strong><br>
<br>
<strong>Deprecated</strong><br>
</strong>- IList&lt;QueryBase&gt; RetrieveMultiple methods<br>
- XmlDocument GetXml(this FetchExpression fe) method&nbsp;</p>
</td>
<td style="text-align:center"><a href="https://pfexrmcore.codeplex.com/releases/view/125246">download</a></td>
</tr>
<tr>
<td style="text-align:center">1407.0</td>
<td style="text-align:center">7/8/2014</td>
<td style="text-align:center">Build</td>
<td>
<p><strong>Features</strong><br>
- #1474 Implement ThreadLocal&lt;T&gt; in parallelized operations to fine tune thread alignment for CRM service channels</p>
<p><strong>Bug Fixes<br>
</strong>- None</p>
<p><strong>Deprecated</strong><br>
- ThreadLocalServiceProxy.cs classes<br>
- XrmServiceManager.GetThreadLocalProxy&lt;TResult&gt; methods</p>
</td>
<td style="text-align:center"><a href="https://pfexrmcore.codeplex.com/releases/view/121819">download</a>&nbsp;</td>
</tr>
<tr>
<td style="text-align:center">1405.2</td>
<td style="text-align:center">5/6/2014</td>
<td style="text-align:center">Patch</td>
<td>
<p>updated assembly details</p>
</td>
<td style="text-align:center"><a href="https://pfexrmcore.codeplex.com/releases/view/121779">download</a></td>
</tr>
<tr>
<td style="text-align:center">1405.1</td>
<td style="text-align:center">5/5/2014</td>
<td style="text-align:center">Major</td>
<td>
<p>initial release</p>
</td>
<td style="text-align:center">&nbsp;</td>
</tr>
</tbody>
</table>
</div><div class="ClearBoth"></div>
