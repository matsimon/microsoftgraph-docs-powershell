---
external help file: Microsoft.Graph.Beta.Security-help.xml
Module Name: Microsoft.Graph.Beta.Security
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.beta.security/update-mgbetasecuritythreatintelligencehostcomponent
schema: 2.0.0
---

# Update-MgBetaSecurityThreatIntelligenceHostComponent

## SYNOPSIS
Update the navigation property hostComponents in security

> [!NOTE]
> To view the v1.0 release of this cmdlet, view [Update-MgSecurityThreatIntelligenceHostComponent](/powershell/module/Microsoft.Graph.Security/Update-MgSecurityThreatIntelligenceHostComponent?view=graph-powershell-v1.0)

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgBetaSecurityThreatIntelligenceHostComponent -HostComponentId <String>
 [-AdditionalProperties <Hashtable>] [-Category <String>] [-FirstSeenDateTime <DateTime>]
 [-Host1 <IMicrosoftGraphSecurityHost>] [-Id <String>] [-LastSeenDateTime <DateTime>] [-Name <String>]
 [-Version <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Update
```
Update-MgBetaSecurityThreatIntelligenceHostComponent -HostComponentId <String>
 -BodyParameter <IMicrosoftGraphSecurityHostComponent> [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgBetaSecurityThreatIntelligenceHostComponent -InputObject <ISecurityIdentity>
 [-AdditionalProperties <Hashtable>] [-Category <String>] [-FirstSeenDateTime <DateTime>]
 [-Host1 <IMicrosoftGraphSecurityHost>] [-Id <String>] [-LastSeenDateTime <DateTime>] [-Name <String>]
 [-Version <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgBetaSecurityThreatIntelligenceHostComponent -InputObject <ISecurityIdentity>
 -BodyParameter <IMicrosoftGraphSecurityHostComponent> [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Update the navigation property hostComponents in security

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
hostComponent
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphSecurityHostComponent
Parameter Sets: Update, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Category
The type of component that was detected (for example, Operating System, Framework, Remote Access, or Server).

```yaml
Type: String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -FirstSeenDateTime
The first date and time when this web component was observed by Microsoft Defender Threat Intelligence.
The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.

```yaml
Type: DateTime
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Host1
host
To construct, see NOTES section for HOST1 properties and create a hash table.

```yaml
Type: IMicrosoftGraphSecurityHost
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -HostComponentId
The unique identifier of hostComponent

```yaml
Type: String
Parameter Sets: UpdateExpanded, Update
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
The unique identifier for an entity.
Read-only.

```yaml
Type: String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InputObject
Identity Parameter
To construct, see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: ISecurityIdentity
Parameter Sets: UpdateViaIdentityExpanded, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -LastSeenDateTime
The most recent date and time when this web component was observed by Microsoft Defender Threat Intelligence.
The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.

```yaml
Type: DateTime
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Name
A name running on the artifact, for example, Microsoft IIS.

```yaml
Type: String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Version
The component version running on the artifact, for example, v8.5.
This should not be assumed to be strictly numerical.

```yaml
Type: String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.Beta.PowerShell.Models.IMicrosoftGraphSecurityHostComponent
### Microsoft.Graph.Beta.PowerShell.Models.ISecurityIdentity
## OUTPUTS

### Microsoft.Graph.Beta.PowerShell.Models.IMicrosoftGraphSecurityHostComponent
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


`BODYPARAMETER <IMicrosoftGraphSecurityHostComponent>`: hostComponent
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: The unique identifier for an entity. Read-only.
  - `[Category <String>]`: The type of component that was detected (for example, Operating System, Framework, Remote Access, or Server).
  - `[FirstSeenDateTime <DateTime?>]`: The first date and time when this web component was observed by Microsoft Defender Threat Intelligence. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
  - `[Host <IMicrosoftGraphSecurityHost>]`: host
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: The unique identifier for an entity. Read-only.
    - `[Components <IMicrosoftGraphSecurityHostComponent[]>]`: The hostComponents that are associated with this host.
    - `[Cookies <IMicrosoftGraphSecurityHostCookie[]>]`: The hostCookies that are associated with this host.
      - `[Id <String>]`: The unique identifier for an entity. Read-only.
      - `[Domain <String>]`: The URI for which the cookie is valid.
      - `[FirstSeenDateTime <DateTime?>]`: The first date and time when this hostCookie was observed by Microsoft Defender Threat Intelligence. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
      - `[Host <IMicrosoftGraphSecurityHost>]`: host
      - `[LastSeenDateTime <DateTime?>]`: The most recent date and time when this hostCookie was observed by Microsoft Defender Threat Intelligence. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
      - `[Name <String>]`: The name of the cookie, for example, JSESSIONID or SEARCH_NAMESITE.
    - `[FirstSeenDateTime <DateTime?>]`: The first date and time when this host was observed. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
    - `[LastSeenDateTime <DateTime?>]`: The most recent date and time when this host was observed. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
    - `[PassiveDns <IMicrosoftGraphSecurityPassiveDnsRecord[]>]`: Passive DNS retrieval about this host.
      - `[Id <String>]`: The unique identifier for an entity. Read-only.
      - `[Artifact <IMicrosoftGraphSecurityArtifact>]`: artifact
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[Id <String>]`: The unique identifier for an entity. Read-only.
      - `[CollectedDateTime <DateTime?>]`: The date and time that this passiveDnsRecord entry was collected by Microsoft. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
      - `[FirstSeenDateTime <DateTime?>]`: The date and time when this passiveDnsRecord entry was first seen. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
      - `[LastSeenDateTime <DateTime?>]`: The date and time when this passiveDnsRecord entry was most recently seen. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
      - `[ParentHost <IMicrosoftGraphSecurityHost>]`: host
      - `[RecordType <String>]`: The DNS record type for this passiveDnsRecord entry.
    - `[PassiveDnsReverse <IMicrosoftGraphSecurityPassiveDnsRecord[]>]`: Reverse passive DNS retrieval about this host.
    - `[Reputation <IMicrosoftGraphSecurityHostReputation>]`: hostReputation
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Id <String>]`: The unique identifier for an entity. Read-only.
      - `[Classification <String>]`: hostReputationClassification
      - `[Rules <IMicrosoftGraphSecurityHostReputationRule[]>]`: A collection of rules that have been used to calculate the classification and score.
        - `[Description <String>]`: The description of the rule that gives more context.
        - `[Name <String>]`: The name of the rule.
        - `[RelatedDetailsUrl <String>]`: Link to a web page with details related to this rule.
        - `[Severity <String>]`: hostReputationRuleSeverity
      - `[Score <Int32?>]`: The calculated score (0-100) of the requested host. A higher value indicates that this host is more likely to be suspicious or malicious.
    - `[Trackers <IMicrosoftGraphSecurityHostTracker[]>]`: The hostTrackers that are associated with this host.
      - `[Id <String>]`: The unique identifier for an entity. Read-only.
      - `[FirstSeenDateTime <DateTime?>]`: The first date and time when this hostTracker was observed by Microsoft Defender Threat Intelligence. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
      - `[Host <IMicrosoftGraphSecurityHost>]`: host
      - `[Kind <String>]`: The kind of hostTracker that was detected. For example, GoogleAnalyticsID or JarmHash.
      - `[LastSeenDateTime <DateTime?>]`: The most recent date and time when this hostTracker was observed by Microsoft Defender Threat Intelligence. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
      - `[Value <String>]`: The identification value for the hostTracker.
  - `[LastSeenDateTime <DateTime?>]`: The most recent date and time when this web component was observed by Microsoft Defender Threat Intelligence. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
  - `[Name <String>]`: A name running on the artifact, for example, Microsoft IIS.
  - `[Version <String>]`: The component version running on the artifact, for example, v8.5. This should not be assumed to be strictly numerical.

`HOST1 <IMicrosoftGraphSecurityHost>`: host
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: The unique identifier for an entity. Read-only.
  - `[Components <IMicrosoftGraphSecurityHostComponent[]>]`: The hostComponents that are associated with this host.
    - `[Id <String>]`: The unique identifier for an entity. Read-only.
    - `[Category <String>]`: The type of component that was detected (for example, Operating System, Framework, Remote Access, or Server).
    - `[FirstSeenDateTime <DateTime?>]`: The first date and time when this web component was observed by Microsoft Defender Threat Intelligence. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
    - `[Host <IMicrosoftGraphSecurityHost>]`: host
    - `[LastSeenDateTime <DateTime?>]`: The most recent date and time when this web component was observed by Microsoft Defender Threat Intelligence. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
    - `[Name <String>]`: A name running on the artifact, for example, Microsoft IIS.
    - `[Version <String>]`: The component version running on the artifact, for example, v8.5. This should not be assumed to be strictly numerical.
  - `[Cookies <IMicrosoftGraphSecurityHostCookie[]>]`: The hostCookies that are associated with this host.
    - `[Id <String>]`: The unique identifier for an entity. Read-only.
    - `[Domain <String>]`: The URI for which the cookie is valid.
    - `[FirstSeenDateTime <DateTime?>]`: The first date and time when this hostCookie was observed by Microsoft Defender Threat Intelligence. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
    - `[Host <IMicrosoftGraphSecurityHost>]`: host
    - `[LastSeenDateTime <DateTime?>]`: The most recent date and time when this hostCookie was observed by Microsoft Defender Threat Intelligence. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
    - `[Name <String>]`: The name of the cookie, for example, JSESSIONID or SEARCH_NAMESITE.
  - `[FirstSeenDateTime <DateTime?>]`: The first date and time when this host was observed. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
  - `[LastSeenDateTime <DateTime?>]`: The most recent date and time when this host was observed. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
  - `[PassiveDns <IMicrosoftGraphSecurityPassiveDnsRecord[]>]`: Passive DNS retrieval about this host.
    - `[Id <String>]`: The unique identifier for an entity. Read-only.
    - `[Artifact <IMicrosoftGraphSecurityArtifact>]`: artifact
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Id <String>]`: The unique identifier for an entity. Read-only.
    - `[CollectedDateTime <DateTime?>]`: The date and time that this passiveDnsRecord entry was collected by Microsoft. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
    - `[FirstSeenDateTime <DateTime?>]`: The date and time when this passiveDnsRecord entry was first seen. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
    - `[LastSeenDateTime <DateTime?>]`: The date and time when this passiveDnsRecord entry was most recently seen. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
    - `[ParentHost <IMicrosoftGraphSecurityHost>]`: host
    - `[RecordType <String>]`: The DNS record type for this passiveDnsRecord entry.
  - `[PassiveDnsReverse <IMicrosoftGraphSecurityPassiveDnsRecord[]>]`: Reverse passive DNS retrieval about this host.
  - `[Reputation <IMicrosoftGraphSecurityHostReputation>]`: hostReputation
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: The unique identifier for an entity. Read-only.
    - `[Classification <String>]`: hostReputationClassification
    - `[Rules <IMicrosoftGraphSecurityHostReputationRule[]>]`: A collection of rules that have been used to calculate the classification and score.
      - `[Description <String>]`: The description of the rule that gives more context.
      - `[Name <String>]`: The name of the rule.
      - `[RelatedDetailsUrl <String>]`: Link to a web page with details related to this rule.
      - `[Severity <String>]`: hostReputationRuleSeverity
    - `[Score <Int32?>]`: The calculated score (0-100) of the requested host. A higher value indicates that this host is more likely to be suspicious or malicious.
  - `[Trackers <IMicrosoftGraphSecurityHostTracker[]>]`: The hostTrackers that are associated with this host.
    - `[Id <String>]`: The unique identifier for an entity. Read-only.
    - `[FirstSeenDateTime <DateTime?>]`: The first date and time when this hostTracker was observed by Microsoft Defender Threat Intelligence. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
    - `[Host <IMicrosoftGraphSecurityHost>]`: host
    - `[Kind <String>]`: The kind of hostTracker that was detected. For example, GoogleAnalyticsID or JarmHash.
    - `[LastSeenDateTime <DateTime?>]`: The most recent date and time when this hostTracker was observed by Microsoft Defender Threat Intelligence. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is 2014-01-01T00:00:00Z.
    - `[Value <String>]`: The identification value for the hostTracker.

`INPUTOBJECT <ISecurityIdentity>`: Identity Parameter
  - `[AlertId <String>]`: The unique identifier of alert
  - `[ArticleId <String>]`: The unique identifier of article
  - `[ArticleIndicatorId <String>]`: The unique identifier of articleIndicator
  - `[AttackSimulationOperationId <String>]`: The unique identifier of attackSimulationOperation
  - `[AuthoredNoteId <String>]`: The unique identifier of authoredNote
  - `[CaseOperationId <String>]`: The unique identifier of caseOperation
  - `[CloudAppSecurityProfileId <String>]`: The unique identifier of cloudAppSecurityProfile
  - `[DataSourceId <String>]`: The unique identifier of dataSource
  - `[DispositionReviewStageId <String>]`: The unique identifier of dispositionReviewStage
  - `[DomainSecurityProfileId <String>]`: The unique identifier of domainSecurityProfile
  - `[EdiscoveryCaseId <String>]`: The unique identifier of ediscoveryCase
  - `[EdiscoveryCustodianId <String>]`: The unique identifier of ediscoveryCustodian
  - `[EdiscoveryFileId <String>]`: The unique identifier of ediscoveryFile
  - `[EdiscoveryHoldPolicyId <String>]`: The unique identifier of ediscoveryHoldPolicy
  - `[EdiscoveryNoncustodialDataSourceId <String>]`: The unique identifier of ediscoveryNoncustodialDataSource
  - `[EdiscoveryReviewSetId <String>]`: The unique identifier of ediscoveryReviewSet
  - `[EdiscoveryReviewSetQueryId <String>]`: The unique identifier of ediscoveryReviewSetQuery
  - `[EdiscoveryReviewTagId <String>]`: The unique identifier of ediscoveryReviewTag
  - `[EdiscoveryReviewTagId1 <String>]`: The unique identifier of ediscoveryReviewTag
  - `[EdiscoverySearchId <String>]`: The unique identifier of ediscoverySearch
  - `[EmailThreatSubmissionId <String>]`: The unique identifier of emailThreatSubmission
  - `[EmailThreatSubmissionPolicyId <String>]`: The unique identifier of emailThreatSubmissionPolicy
  - `[FileSecurityProfileId <String>]`: The unique identifier of fileSecurityProfile
  - `[FileThreatSubmissionId <String>]`: The unique identifier of fileThreatSubmission
  - `[HostComponentId <String>]`: The unique identifier of hostComponent
  - `[HostCookieId <String>]`: The unique identifier of hostCookie
  - `[HostId <String>]`: The unique identifier of host
  - `[HostSecurityProfileId <String>]`: The unique identifier of hostSecurityProfile
  - `[HostTrackerId <String>]`: The unique identifier of hostTracker
  - `[IPSecurityProfileId <String>]`: The unique identifier of ipSecurityProfile
  - `[IncidentId <String>]`: The unique identifier of incident
  - `[IntelligenceProfileId <String>]`: The unique identifier of intelligenceProfile
  - `[IntelligenceProfileIndicatorId <String>]`: The unique identifier of intelligenceProfileIndicator
  - `[PassiveDnsRecordId <String>]`: The unique identifier of passiveDnsRecord
  - `[PayloadId <String>]`: The unique identifier of payload
  - `[ProviderTenantSettingId <String>]`: The unique identifier of providerTenantSetting
  - `[RetentionEventId <String>]`: The unique identifier of retentionEvent
  - `[RetentionEventTypeId <String>]`: The unique identifier of retentionEventType
  - `[RetentionLabelId <String>]`: The unique identifier of retentionLabel
  - `[SecureScoreControlProfileId <String>]`: The unique identifier of secureScoreControlProfile
  - `[SecureScoreId <String>]`: The unique identifier of secureScore
  - `[SecurityActionId <String>]`: The unique identifier of securityAction
  - `[SensitivityLabelId <String>]`: The unique identifier of sensitivityLabel
  - `[SimulationAutomationId <String>]`: The unique identifier of simulationAutomation
  - `[SimulationAutomationRunId <String>]`: The unique identifier of simulationAutomationRun
  - `[SimulationId <String>]`: The unique identifier of simulation
  - `[SiteSourceId <String>]`: The unique identifier of siteSource
  - `[SubjectRightsRequestId <String>]`: The unique identifier of subjectRightsRequest
  - `[TiIndicatorId <String>]`: The unique identifier of tiIndicator
  - `[UnifiedGroupSourceId <String>]`: The unique identifier of unifiedGroupSource
  - `[UrlThreatSubmissionId <String>]`: The unique identifier of urlThreatSubmission
  - `[UserId <String>]`: The unique identifier of user
  - `[UserSecurityProfileId <String>]`: The unique identifier of userSecurityProfile
  - `[UserSourceId <String>]`: The unique identifier of userSource
  - `[VulnerabilityComponentId <String>]`: The unique identifier of vulnerabilityComponent
  - `[VulnerabilityId <String>]`: The unique identifier of vulnerability

## RELATED LINKS
[Update-MgSecurityThreatIntelligenceHostComponent](/powershell/module/Microsoft.Graph.Security/Update-MgSecurityThreatIntelligenceHostComponent?view=graph-powershell-v1.0)

## RELATED LINKS
[Update-MgSecurityThreatIntelligenceHostComponent](/powershell/module/Microsoft.Graph.Security/Update-MgSecurityThreatIntelligenceHostComponent?view=graph-powershell-v1.0)

