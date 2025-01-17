---
Module Name: Microsoft.Graph.Security
Module Guid: d936ff93-9373-4f57-a629-c82b84e95a95
Download Help Link: https://learn.microsoft.com/powershell/module/Microsoft.Graph.Security
Help Version: 1.0.0.0
Locale: en-US
---

# Microsoft.Graph.Security Module
## Description
Microsoft Graph PowerShell Cmdlets

## Microsoft.Graph.Security Cmdlets
### [Add-MgSecurityCaseEdiscoveryCaseCustodianHold](Add-MgSecurityCaseEdiscoveryCaseCustodianHold.md)
Start the process of applying hold on eDiscovery custodians.
After the operation is created, you can get the status by retrieving the `Location` parameter from the response headers.
The location provides a URL that will return an eDiscoveryHoldOperation object.

### [Add-MgSecurityCaseEdiscoveryCaseNoncustodialDataSourceHold](Add-MgSecurityCaseEdiscoveryCaseNoncustodialDataSourceHold.md)
Start the process of applying hold on eDiscovery non-custodial data sources.
After the operation is created, you can get the status by retrieving the `Location` parameter from the response headers.
The location provides a URL that will return an eDiscoveryHoldOperation object.

### [Add-MgSecurityCaseEdiscoveryCaseReviewSetQueryTag](Add-MgSecurityCaseEdiscoveryCaseReviewSetQueryTag.md)
Apply tags to files in an eDiscovery review set.
For details, see Tag documents in a review set in eDiscovery.

### [Add-MgSecurityCaseEdiscoveryCaseReviewSetToReviewSet](Add-MgSecurityCaseEdiscoveryCaseReviewSetToReviewSet.md)
Start the process of adding a collection from Microsoft 365 services to a review set.
After the operation is created, you can get the status of the operation by retrieving the `Location` parameter from the response headers.
The location provides a URL that will return a Add to review set operation.

### [Clear-MgSecurityCaseEdiscoveryCaseSearchData](Clear-MgSecurityCaseEdiscoveryCaseSearchData.md)
Invoke action purgeData

### [Close-MgSecurityCaseEdiscoveryCase](Close-MgSecurityCaseEdiscoveryCase.md)
Close an eDiscovery case.
For details, see Close a case.

### [Get-MgSecurityAlert](Get-MgSecurityAlert.md)
Retrieve the properties and relationships of an alert object.

### [Get-MgSecurityAlertCount](Get-MgSecurityAlertCount.md)
Get the number of the resource

### [Get-MgSecurityAlertV2](Get-MgSecurityAlertV2.md)
Get the properties and relationships of an alert in an organization based on the specified alert **id** property.

### [Get-MgSecurityAlertV2Count](Get-MgSecurityAlertV2Count.md)
Get the number of the resource

### [Get-MgSecurityAttackSimulation](Get-MgSecurityAttackSimulation.md)
Get attackSimulation from security

### [Get-MgSecurityAttackSimulationAutomation](Get-MgSecurityAttackSimulationAutomation.md)
Get an attack simulation automation for a tenant.

### [Get-MgSecurityAttackSimulationAutomationCount](Get-MgSecurityAttackSimulationAutomationCount.md)
Get the number of the resource

### [Get-MgSecurityAttackSimulationAutomationRun](Get-MgSecurityAttackSimulationAutomationRun.md)
A collection of simulation automation runs.

### [Get-MgSecurityAttackSimulationAutomationRunCount](Get-MgSecurityAttackSimulationAutomationRunCount.md)
Get the number of the resource

### [Get-MgSecurityAttackSimulationCount](Get-MgSecurityAttackSimulationCount.md)
Get the number of the resource

### [Get-MgSecurityCase](Get-MgSecurityCase.md)
Get cases from security

### [Get-MgSecurityCaseEdiscoveryCase](Get-MgSecurityCaseEdiscoveryCase.md)
Read the properties and relationships of an ediscoveryCase object.

### [Get-MgSecurityCaseEdiscoveryCaseCount](Get-MgSecurityCaseEdiscoveryCaseCount.md)
Get the number of the resource

### [Get-MgSecurityCaseEdiscoveryCaseCustodian](Get-MgSecurityCaseEdiscoveryCaseCustodian.md)
Read the properties and relationships of an ediscoveryCustodian object.

### [Get-MgSecurityCaseEdiscoveryCaseCustodianCount](Get-MgSecurityCaseEdiscoveryCaseCustodianCount.md)
Get the number of the resource

### [Get-MgSecurityCaseEdiscoveryCaseCustodianLastIndexOperation](Get-MgSecurityCaseEdiscoveryCaseCustodianLastIndexOperation.md)
Get a list of the ediscoveryIndexOperations associated with an ediscoveryCustodian.

### [Get-MgSecurityCaseEdiscoveryCaseCustodianSiteSource](Get-MgSecurityCaseEdiscoveryCaseCustodianSiteSource.md)
Data source entity for SharePoint sites associated with the custodian.

### [Get-MgSecurityCaseEdiscoveryCaseCustodianSiteSourceCount](Get-MgSecurityCaseEdiscoveryCaseCustodianSiteSourceCount.md)
Get the number of the resource

### [Get-MgSecurityCaseEdiscoveryCaseCustodianSiteSourceSite](Get-MgSecurityCaseEdiscoveryCaseCustodianSiteSourceSite.md)
The SharePoint site associated with the siteSource.

### [Get-MgSecurityCaseEdiscoveryCaseCustodianUnifiedGroupSource](Get-MgSecurityCaseEdiscoveryCaseCustodianUnifiedGroupSource.md)
Data source entity for groups associated with the custodian.

### [Get-MgSecurityCaseEdiscoveryCaseCustodianUnifiedGroupSourceCount](Get-MgSecurityCaseEdiscoveryCaseCustodianUnifiedGroupSourceCount.md)
Get the number of the resource

### [Get-MgSecurityCaseEdiscoveryCaseCustodianUnifiedGroupSourceGroup](Get-MgSecurityCaseEdiscoveryCaseCustodianUnifiedGroupSourceGroup.md)
Represents a group.

### [Get-MgSecurityCaseEdiscoveryCaseCustodianUserSource](Get-MgSecurityCaseEdiscoveryCaseCustodianUserSource.md)
Data source entity for a the custodian.
This is the container for a custodian's mailbox and OneDrive for Business site.

### [Get-MgSecurityCaseEdiscoveryCaseCustodianUserSourceCount](Get-MgSecurityCaseEdiscoveryCaseCustodianUserSourceCount.md)
Get the number of the resource

### [Get-MgSecurityCaseEdiscoveryCaseNoncustodialDataSource](Get-MgSecurityCaseEdiscoveryCaseNoncustodialDataSource.md)
Returns a list of case ediscoveryNoncustodialDataSource objects for this case.

### [Get-MgSecurityCaseEdiscoveryCaseNoncustodialDataSourceCount](Get-MgSecurityCaseEdiscoveryCaseNoncustodialDataSourceCount.md)
Get the number of the resource

### [Get-MgSecurityCaseEdiscoveryCaseNoncustodialDataSourceLastIndexOperation](Get-MgSecurityCaseEdiscoveryCaseNoncustodialDataSourceLastIndexOperation.md)
Operation entity that represents the latest indexing for the non-custodial data source.

### [Get-MgSecurityCaseEdiscoveryCaseOperation](Get-MgSecurityCaseEdiscoveryCaseOperation.md)
Read the properties and relationships of a caseOperation object.

### [Get-MgSecurityCaseEdiscoveryCaseOperationCount](Get-MgSecurityCaseEdiscoveryCaseOperationCount.md)
Get the number of the resource

### [Get-MgSecurityCaseEdiscoveryCaseReviewSet](Get-MgSecurityCaseEdiscoveryCaseReviewSet.md)
Read the properties and relationships of an ediscoveryReviewSet object.

### [Get-MgSecurityCaseEdiscoveryCaseReviewSetCount](Get-MgSecurityCaseEdiscoveryCaseReviewSetCount.md)
Get the number of the resource

### [Get-MgSecurityCaseEdiscoveryCaseReviewSetQuery](Get-MgSecurityCaseEdiscoveryCaseReviewSetQuery.md)
Read the properties and relationships of an ediscoveryReviewSetQuery object.

### [Get-MgSecurityCaseEdiscoveryCaseReviewSetQueryCount](Get-MgSecurityCaseEdiscoveryCaseReviewSetQueryCount.md)
Get the number of the resource

### [Get-MgSecurityCaseEdiscoveryCaseSearch](Get-MgSecurityCaseEdiscoveryCaseSearch.md)
Read the properties and relationships of an ediscoverySearch object.

### [Get-MgSecurityCaseEdiscoveryCaseSearchAdditionalSource](Get-MgSecurityCaseEdiscoveryCaseSearchAdditionalSource.md)
Adds an additional source to the eDiscovery search.

### [Get-MgSecurityCaseEdiscoveryCaseSearchAdditionalSourceCount](Get-MgSecurityCaseEdiscoveryCaseSearchAdditionalSourceCount.md)
Get the number of the resource

### [Get-MgSecurityCaseEdiscoveryCaseSearchAddToReviewSetOperation](Get-MgSecurityCaseEdiscoveryCaseSearchAddToReviewSetOperation.md)
Adds the results of the eDiscovery search to the specified reviewSet.

### [Get-MgSecurityCaseEdiscoveryCaseSearchCount](Get-MgSecurityCaseEdiscoveryCaseSearchCount.md)
Get the number of the resource

### [Get-MgSecurityCaseEdiscoveryCaseSearchCustodianSource](Get-MgSecurityCaseEdiscoveryCaseSearchCustodianSource.md)
Custodian sources that are included in the eDiscovery search.

### [Get-MgSecurityCaseEdiscoveryCaseSearchCustodianSourceCount](Get-MgSecurityCaseEdiscoveryCaseSearchCustodianSourceCount.md)
Get the number of the resource

### [Get-MgSecurityCaseEdiscoveryCaseSearchLastEstimateStatisticsOperation](Get-MgSecurityCaseEdiscoveryCaseSearchLastEstimateStatisticsOperation.md)
Get the last  ediscoveryEstimateOperation objects and their properties.

### [Get-MgSecurityCaseEdiscoveryCaseSearchNoncustodialSource](Get-MgSecurityCaseEdiscoveryCaseSearchNoncustodialSource.md)
noncustodialDataSource sources that are included in the eDiscovery search

### [Get-MgSecurityCaseEdiscoveryCaseSearchNoncustodialSourceCount](Get-MgSecurityCaseEdiscoveryCaseSearchNoncustodialSourceCount.md)
Get the number of the resource

### [Get-MgSecurityCaseEdiscoveryCaseSetting](Get-MgSecurityCaseEdiscoveryCaseSetting.md)
Read the properties and relationships of an ediscoveryCaseSettings object.

### [Get-MgSecurityCaseEdiscoveryCaseTag](Get-MgSecurityCaseEdiscoveryCaseTag.md)
Read the properties and relationships of an ediscoveryReviewTag object.

### [Get-MgSecurityCaseEdiscoveryCaseTagChildTag](Get-MgSecurityCaseEdiscoveryCaseTagChildTag.md)
Returns the tags that are a child of a tag.

### [Get-MgSecurityCaseEdiscoveryCaseTagChildTagCount](Get-MgSecurityCaseEdiscoveryCaseTagChildTagCount.md)
Get the number of the resource

### [Get-MgSecurityCaseEdiscoveryCaseTagCount](Get-MgSecurityCaseEdiscoveryCaseTagCount.md)
Get the number of the resource

### [Get-MgSecurityCaseEdiscoveryCaseTagParent](Get-MgSecurityCaseEdiscoveryCaseTagParent.md)
Returns the parent tag of the specified tag.

### [Get-MgSecurityIncident](Get-MgSecurityIncident.md)
Retrieve the properties and relationships of an incident object.
Attacks are typically inflicted on different types of entities, such as devices, users, and mailboxes, resulting in multiple alert objects.
Microsoft 365 Defender correlates alerts with the same attack techniques or the same attacker into an **incident**.

### [Get-MgSecurityIncidentAlert](Get-MgSecurityIncidentAlert.md)
The list of related alerts.
Supports $expand.

### [Get-MgSecurityIncidentAlertCount](Get-MgSecurityIncidentAlertCount.md)
Get the number of the resource

### [Get-MgSecurityIncidentCount](Get-MgSecurityIncidentCount.md)
Get the number of the resource

### [Get-MgSecuritySecureScore](Get-MgSecuritySecureScore.md)
Retrieve the properties and relationships of a secureScore object.

### [Get-MgSecuritySecureScoreControlProfile](Get-MgSecuritySecureScoreControlProfile.md)
Retrieve the properties and relationships of an securescorecontrolprofile object.

### [Get-MgSecuritySecureScoreControlProfileCount](Get-MgSecuritySecureScoreControlProfileCount.md)
Get the number of the resource

### [Get-MgSecuritySecureScoreCount](Get-MgSecuritySecureScoreCount.md)
Get the number of the resource

### [Get-MgSecurityTrigger](Get-MgSecurityTrigger.md)
Get triggers from security

### [Get-MgSecurityTriggerRetentionEvent](Get-MgSecurityTriggerRetentionEvent.md)
Read the properties and relationships of a retentionEvent object.

### [Get-MgSecurityTriggerRetentionEventCount](Get-MgSecurityTriggerRetentionEventCount.md)
Get the number of the resource

### [Get-MgSecurityTriggerRetentionEventType](Get-MgSecurityTriggerRetentionEventType.md)
Specifies the event that will start the retention period for labels that use this event type when an event is created.

### [Get-MgSecurityTriggerType](Get-MgSecurityTriggerType.md)
Get triggerTypes from security

### [Get-MgSecurityTriggerTypeRetentionEventType](Get-MgSecurityTriggerTypeRetentionEventType.md)
Read the properties and relationships of a retentionEventType object.

### [Get-MgSecurityTriggerTypeRetentionEventTypeCount](Get-MgSecurityTriggerTypeRetentionEventTypeCount.md)
Get the number of the resource

### [Initialize-MgSecurityCaseEdiscoveryCaseCustodian](Initialize-MgSecurityCaseEdiscoveryCaseCustodian.md)
Activate a custodian that has been released from a case to make them part of the case again.
For details, see Manage custodians in an eDiscovery (Premium) case.

### [Invoke-MgAsSecurityCaseEdiscoveryCaseTagHierarchy](Invoke-MgAsSecurityCaseEdiscoveryCaseTagHierarchy.md)
Invoke function asHierarchy

### [Invoke-MgEstimateSecurityCaseEdiscoveryCaseSearchStatistics](Invoke-MgEstimateSecurityCaseEdiscoveryCaseSearchStatistics.md)
Run an estimate of the number of emails and documents in the eDiscovery search.
To learn more about searches in eDiscovery, see Collect data for a case in eDiscovery (Premium).

### [Invoke-MgReopenSecurityCaseEdiscoveryCase](Invoke-MgReopenSecurityCaseEdiscoveryCase.md)
Reopen an eDiscovery case that was closed.
For details, see Reopen a closed case.

### [New-MgSecurityAlert](New-MgSecurityAlert.md)
Create new navigation property to alerts for security

### [New-MgSecurityAlertV2](New-MgSecurityAlertV2.md)
Create new navigation property to alerts_v2 for security

### [New-MgSecurityAttackSimulation](New-MgSecurityAttackSimulation.md)
Create new navigation property to simulations for security

### [New-MgSecurityAttackSimulationAutomation](New-MgSecurityAttackSimulationAutomation.md)
Create new navigation property to simulationAutomations for security

### [New-MgSecurityAttackSimulationAutomationRun](New-MgSecurityAttackSimulationAutomationRun.md)
Create new navigation property to runs for security

### [New-MgSecurityCaseEdiscoveryCase](New-MgSecurityCaseEdiscoveryCase.md)
Create a new ediscoveryCase object.

### [New-MgSecurityCaseEdiscoveryCaseCustodian](New-MgSecurityCaseEdiscoveryCaseCustodian.md)
Create a new ediscoveryCustodian object.\nAfter the custodian object is created, you will need to create the custodian's userSource to reference their mailbox and OneDrive for Business site.

### [New-MgSecurityCaseEdiscoveryCaseCustodianSiteSource](New-MgSecurityCaseEdiscoveryCaseCustodianSiteSource.md)
Create a new siteSource object associated with an eDiscovery custodian.

### [New-MgSecurityCaseEdiscoveryCaseCustodianUnifiedGroupSource](New-MgSecurityCaseEdiscoveryCaseCustodianUnifiedGroupSource.md)
Create a new unifiedGroupSource object associated with an eDiscovery custodian.

### [New-MgSecurityCaseEdiscoveryCaseCustodianUserSource](New-MgSecurityCaseEdiscoveryCaseCustodianUserSource.md)
Create a new userSource object associated with an eDiscovery custodian.

### [New-MgSecurityCaseEdiscoveryCaseNoncustodialDataSource](New-MgSecurityCaseEdiscoveryCaseNoncustodialDataSource.md)
Create a new ediscoveryNoncustodialDataSource object.

### [New-MgSecurityCaseEdiscoveryCaseOperation](New-MgSecurityCaseEdiscoveryCaseOperation.md)
Create new navigation property to operations for security

### [New-MgSecurityCaseEdiscoveryCaseReviewSet](New-MgSecurityCaseEdiscoveryCaseReviewSet.md)
Create a new ediscoveryReviewSet object.

### [New-MgSecurityCaseEdiscoveryCaseReviewSetQuery](New-MgSecurityCaseEdiscoveryCaseReviewSetQuery.md)
Create a new ediscoveryReviewSetQuery object.

### [New-MgSecurityCaseEdiscoveryCaseSearch](New-MgSecurityCaseEdiscoveryCaseSearch.md)
Create a new ediscoverySearch object.

### [New-MgSecurityCaseEdiscoveryCaseSearchAdditionalSource](New-MgSecurityCaseEdiscoveryCaseSearchAdditionalSource.md)
Create a new additional source associated with an eDiscovery search.

### [New-MgSecurityCaseEdiscoveryCaseTag](New-MgSecurityCaseEdiscoveryCaseTag.md)
Create a new ediscoveryReviewTag object.

### [New-MgSecurityIncident](New-MgSecurityIncident.md)
Create new navigation property to incidents for security

### [New-MgSecuritySecureScore](New-MgSecuritySecureScore.md)
Create new navigation property to secureScores for security

### [New-MgSecuritySecureScoreControlProfile](New-MgSecuritySecureScoreControlProfile.md)
Create new navigation property to secureScoreControlProfiles for security

### [New-MgSecurityTriggerRetentionEvent](New-MgSecurityTriggerRetentionEvent.md)
Create a new retentionEvent object.

### [New-MgSecurityTriggerTypeRetentionEventType](New-MgSecurityTriggerTypeRetentionEventType.md)
Create a new retentionEventType object.

### [Publish-MgSecurityCaseEdiscoveryCaseCustodian](Publish-MgSecurityCaseEdiscoveryCaseCustodian.md)
Release a custodian from a case.
For details, see Release a custodian from a case.

### [Publish-MgSecurityCaseEdiscoveryCaseNoncustodialDataSource](Publish-MgSecurityCaseEdiscoveryCaseNoncustodialDataSource.md)
Release the non-custodial data source from the case.

### [Remove-MgSecurityAlertV2](Remove-MgSecurityAlertV2.md)
Delete navigation property alerts_v2 for security

### [Remove-MgSecurityAttackSimulation](Remove-MgSecurityAttackSimulation.md)
Delete navigation property attackSimulation for security

### [Remove-MgSecurityAttackSimulationAutomation](Remove-MgSecurityAttackSimulationAutomation.md)
Delete navigation property simulationAutomations for security

### [Remove-MgSecurityAttackSimulationAutomationRun](Remove-MgSecurityAttackSimulationAutomationRun.md)
Delete navigation property runs for security

### [Remove-MgSecurityCase](Remove-MgSecurityCase.md)
Delete navigation property cases for security

### [Remove-MgSecurityCaseEdiscoveryCase](Remove-MgSecurityCaseEdiscoveryCase.md)
Delete an ediscoveryCase object.

### [Remove-MgSecurityCaseEdiscoveryCaseCustodian](Remove-MgSecurityCaseEdiscoveryCaseCustodian.md)
Delete navigation property custodians for security

### [Remove-MgSecurityCaseEdiscoveryCaseCustodianHold](Remove-MgSecurityCaseEdiscoveryCaseCustodianHold.md)
Start the process of removing hold from eDiscovery custodians.
After the operation is created, you can get the status by retrieving the `Location` parameter from the response headers.
The location provides a URL that will return an eDiscoveryHoldOperation object.

### [Remove-MgSecurityCaseEdiscoveryCaseCustodianSiteSource](Remove-MgSecurityCaseEdiscoveryCaseCustodianSiteSource.md)
Delete navigation property siteSources for security

### [Remove-MgSecurityCaseEdiscoveryCaseCustodianUnifiedGroupSource](Remove-MgSecurityCaseEdiscoveryCaseCustodianUnifiedGroupSource.md)
Delete navigation property unifiedGroupSources for security

### [Remove-MgSecurityCaseEdiscoveryCaseCustodianUserSource](Remove-MgSecurityCaseEdiscoveryCaseCustodianUserSource.md)
Delete navigation property userSources for security

### [Remove-MgSecurityCaseEdiscoveryCaseNoncustodialDataSource](Remove-MgSecurityCaseEdiscoveryCaseNoncustodialDataSource.md)
Delete navigation property noncustodialDataSources for security

### [Remove-MgSecurityCaseEdiscoveryCaseNoncustodialDataSourceHold](Remove-MgSecurityCaseEdiscoveryCaseNoncustodialDataSourceHold.md)
Start the process of removing hold from eDiscovery non-custodial data sources.
After the operation is created, you can get the status by retrieving the `Location` parameter from the response headers.
The location provides a URL that will return an eDiscoveryHoldOperation object.

### [Remove-MgSecurityCaseEdiscoveryCaseOperation](Remove-MgSecurityCaseEdiscoveryCaseOperation.md)
Delete navigation property operations for security

### [Remove-MgSecurityCaseEdiscoveryCaseReviewSet](Remove-MgSecurityCaseEdiscoveryCaseReviewSet.md)
Delete navigation property reviewSets for security

### [Remove-MgSecurityCaseEdiscoveryCaseReviewSetQuery](Remove-MgSecurityCaseEdiscoveryCaseReviewSetQuery.md)
Delete an ediscoveryReviewSetQuery object.

### [Remove-MgSecurityCaseEdiscoveryCaseSearch](Remove-MgSecurityCaseEdiscoveryCaseSearch.md)
Delete an ediscoverySearch object.

### [Remove-MgSecurityCaseEdiscoveryCaseSearchAdditionalSource](Remove-MgSecurityCaseEdiscoveryCaseSearchAdditionalSource.md)
Delete navigation property additionalSources for security

### [Remove-MgSecurityCaseEdiscoveryCaseSearchCustodianSource](Remove-MgSecurityCaseEdiscoveryCaseSearchCustodianSource.md)
Remove a dataSource object.

### [Remove-MgSecurityCaseEdiscoveryCaseSearchNoncustodialSource](Remove-MgSecurityCaseEdiscoveryCaseSearchNoncustodialSource.md)
Remove an ediscoveryNoncustodialDataSource object.

### [Remove-MgSecurityCaseEdiscoveryCaseSetting](Remove-MgSecurityCaseEdiscoveryCaseSetting.md)
Delete navigation property settings for security

### [Remove-MgSecurityCaseEdiscoveryCaseTag](Remove-MgSecurityCaseEdiscoveryCaseTag.md)
Remove an ediscoveryReviewTag object.

### [Remove-MgSecurityIncident](Remove-MgSecurityIncident.md)
Delete navigation property incidents for security

### [Remove-MgSecuritySecureScore](Remove-MgSecuritySecureScore.md)
Delete navigation property secureScores for security

### [Remove-MgSecuritySecureScoreControlProfile](Remove-MgSecuritySecureScoreControlProfile.md)
Delete navigation property secureScoreControlProfiles for security

### [Remove-MgSecurityTrigger](Remove-MgSecurityTrigger.md)
Delete navigation property triggers for security

### [Remove-MgSecurityTriggerRetentionEvent](Remove-MgSecurityTriggerRetentionEvent.md)
Delete a retentionEvent object.

### [Remove-MgSecurityTriggerType](Remove-MgSecurityTriggerType.md)
Delete navigation property triggerTypes for security

### [Remove-MgSecurityTriggerTypeRetentionEventType](Remove-MgSecurityTriggerTypeRetentionEventType.md)
Delete a retentionEventType object.

### [Reset-MgSecurityCaseEdiscoveryCaseSettingToDefault](Reset-MgSecurityCaseEdiscoveryCaseSettingToDefault.md)
Reset a caseSettings object to the default values.

### [Start-MgSecurityHuntingQuery](Start-MgSecurityHuntingQuery.md)
Invoke action runHuntingQuery

### [Update-MgSecurityAlert](Update-MgSecurityAlert.md)
Update an editable **alert** property within any integrated solution to keep alert status and assignments in sync across solutions.
This method updates any solution that has a record of the referenced alert ID.

### [Update-MgSecurityAlertV2](Update-MgSecurityAlertV2.md)
Update the properties of an alert object in an organization based on the specified alert **id** property.

### [Update-MgSecurityAttackSimulationAutomation](Update-MgSecurityAttackSimulationAutomation.md)
Update the navigation property simulationAutomations in security

### [Update-MgSecurityAttackSimulationAutomationRun](Update-MgSecurityAttackSimulationAutomationRun.md)
Update the navigation property runs in security

### [Update-MgSecurityCase](Update-MgSecurityCase.md)
Update the navigation property cases in security

### [Update-MgSecurityCaseEdiscoveryCase](Update-MgSecurityCaseEdiscoveryCase.md)
Update the properties of an ediscoveryCase object.

### [Update-MgSecurityCaseEdiscoveryCaseCustodian](Update-MgSecurityCaseEdiscoveryCaseCustodian.md)
Update the navigation property custodians in security

### [Update-MgSecurityCaseEdiscoveryCaseCustodianIndex](Update-MgSecurityCaseEdiscoveryCaseCustodianIndex.md)
Trigger an indexOperation to make a custodian and associated sources searchable.

### [Update-MgSecurityCaseEdiscoveryCaseCustodianSiteSource](Update-MgSecurityCaseEdiscoveryCaseCustodianSiteSource.md)
Update the navigation property siteSources in security

### [Update-MgSecurityCaseEdiscoveryCaseCustodianUnifiedGroupSource](Update-MgSecurityCaseEdiscoveryCaseCustodianUnifiedGroupSource.md)
Update the navigation property unifiedGroupSources in security

### [Update-MgSecurityCaseEdiscoveryCaseCustodianUserSource](Update-MgSecurityCaseEdiscoveryCaseCustodianUserSource.md)
Update the navigation property userSources in security

### [Update-MgSecurityCaseEdiscoveryCaseNoncustodialDataSource](Update-MgSecurityCaseEdiscoveryCaseNoncustodialDataSource.md)
Update the navigation property noncustodialDataSources in security

### [Update-MgSecurityCaseEdiscoveryCaseNoncustodialDataSourceIndex](Update-MgSecurityCaseEdiscoveryCaseNoncustodialDataSourceIndex.md)
Trigger an indexOperation to make a non-custodial data source and its associated data source searchable.

### [Update-MgSecurityCaseEdiscoveryCaseOperation](Update-MgSecurityCaseEdiscoveryCaseOperation.md)
Update the navigation property operations in security

### [Update-MgSecurityCaseEdiscoveryCaseReviewSet](Update-MgSecurityCaseEdiscoveryCaseReviewSet.md)
Update the navigation property reviewSets in security

### [Update-MgSecurityCaseEdiscoveryCaseReviewSetQuery](Update-MgSecurityCaseEdiscoveryCaseReviewSetQuery.md)
Update the properties of an ediscoveryReviewSetQuery object.

### [Update-MgSecurityCaseEdiscoveryCaseSearch](Update-MgSecurityCaseEdiscoveryCaseSearch.md)
Update the properties of an ediscoverySearch object.

### [Update-MgSecurityCaseEdiscoveryCaseSearchAdditionalSource](Update-MgSecurityCaseEdiscoveryCaseSearchAdditionalSource.md)
Update the navigation property additionalSources in security

### [Update-MgSecurityCaseEdiscoveryCaseSetting](Update-MgSecurityCaseEdiscoveryCaseSetting.md)
Update the properties of an ediscoveryCaseSettings object.

### [Update-MgSecurityCaseEdiscoveryCaseTag](Update-MgSecurityCaseEdiscoveryCaseTag.md)
Update the properties of an ediscoveryReviewTag object.

### [Update-MgSecurityIncident](Update-MgSecurityIncident.md)
Update the properties of an incident object.

### [Update-MgSecuritySecureScore](Update-MgSecuritySecureScore.md)
Update the navigation property secureScores in security

### [Update-MgSecuritySecureScoreControlProfile](Update-MgSecuritySecureScoreControlProfile.md)
Update an editable **secureScoreControlProfile** object within any integrated solution to change various properties, such as **assignedTo** or **tenantNote**.

### [Update-MgSecurityTrigger](Update-MgSecurityTrigger.md)
Update the navigation property triggers in security

### [Update-MgSecurityTriggerRetentionEvent](Update-MgSecurityTriggerRetentionEvent.md)
Update the navigation property retentionEvents in security

### [Update-MgSecurityTriggerType](Update-MgSecurityTriggerType.md)
Update the navigation property triggerTypes in security

### [Update-MgSecurityTriggerTypeRetentionEventType](Update-MgSecurityTriggerTypeRetentionEventType.md)
Update the navigation property retentionEventTypes in security

