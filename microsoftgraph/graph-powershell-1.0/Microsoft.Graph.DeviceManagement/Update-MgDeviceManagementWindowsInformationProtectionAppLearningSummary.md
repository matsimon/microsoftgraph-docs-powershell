---
external help file: Microsoft.Graph.DeviceManagement-help.xml
Module Name: Microsoft.Graph.DeviceManagement
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.devicemanagement/update-mgdevicemanagementwindowsinformationprotectionapplearningsummary
schema: 2.0.0
---

# Update-MgDeviceManagementWindowsInformationProtectionAppLearningSummary

## SYNOPSIS
Update the navigation property windowsInformationProtectionAppLearningSummaries in deviceManagement

> [!NOTE]
> To view the beta release of this cmdlet, view [Update-MgBetaDeviceManagementWindowsInformationProtectionAppLearningSummary](/powershell/module/Microsoft.Graph.Beta.DeviceManagement/Update-MgBetaDeviceManagementWindowsInformationProtectionAppLearningSummary?view=graph-powershell-beta)

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgDeviceManagementWindowsInformationProtectionAppLearningSummary
 -WindowsInformationProtectionAppLearningSummaryId <String> [-AdditionalProperties <Hashtable>]
 [-ApplicationName <String>] [-ApplicationType <ApplicationType>] [-DeviceCount <Int32>] [-Id <String>]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Update
```
Update-MgDeviceManagementWindowsInformationProtectionAppLearningSummary
 -WindowsInformationProtectionAppLearningSummaryId <String>
 -BodyParameter <IMicrosoftGraphWindowsInformationProtectionAppLearningSummary> [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgDeviceManagementWindowsInformationProtectionAppLearningSummary
 -InputObject <IDeviceManagementIdentity> [-AdditionalProperties <Hashtable>] [-ApplicationName <String>]
 [-ApplicationType <ApplicationType>] [-DeviceCount <Int32>] [-Id <String>] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgDeviceManagementWindowsInformationProtectionAppLearningSummary
 -InputObject <IDeviceManagementIdentity>
 -BodyParameter <IMicrosoftGraphWindowsInformationProtectionAppLearningSummary> [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

## DESCRIPTION
Update the navigation property windowsInformationProtectionAppLearningSummaries in deviceManagement

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

### -ApplicationName
Application Name

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

### -ApplicationType
Possible types of Application

```yaml
Type: ApplicationType
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
Windows Information Protection AppLearning Summary entity.
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphWindowsInformationProtectionAppLearningSummary
Parameter Sets: Update, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -DeviceCount
Device Count

```yaml
Type: Int32
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
The unique idenfier for an entity.
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
Type: IDeviceManagementIdentity
Parameter Sets: UpdateViaIdentityExpanded, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -WindowsInformationProtectionAppLearningSummaryId
The unique identifier of windowsInformationProtectionAppLearningSummary

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

### Microsoft.Graph.PowerShell.Models.IDeviceManagementIdentity
### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphWindowsInformationProtectionAppLearningSummary
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphWindowsInformationProtectionAppLearningSummary
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


`BODYPARAMETER <IMicrosoftGraphWindowsInformationProtectionAppLearningSummary>`: Windows Information Protection AppLearning Summary entity.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: The unique idenfier for an entity. Read-only.
  - `[ApplicationName <String>]`: Application Name
  - `[ApplicationType <ApplicationType?>]`: Possible types of Application
  - `[DeviceCount <Int32?>]`: Device Count

`INPUTOBJECT <IDeviceManagementIdentity>`: Identity Parameter
  - `[DetectedAppId <String>]`: The unique identifier of detectedApp
  - `[DeviceCategoryId <String>]`: The unique identifier of deviceCategory
  - `[DeviceComplianceActionItemId <String>]`: The unique identifier of deviceComplianceActionItem
  - `[DeviceComplianceDeviceStatusId <String>]`: The unique identifier of deviceComplianceDeviceStatus
  - `[DeviceCompliancePolicyAssignmentId <String>]`: The unique identifier of deviceCompliancePolicyAssignment
  - `[DeviceCompliancePolicyId <String>]`: The unique identifier of deviceCompliancePolicy
  - `[DeviceCompliancePolicySettingStateSummaryId <String>]`: The unique identifier of deviceCompliancePolicySettingStateSummary
  - `[DeviceCompliancePolicyStateId <String>]`: The unique identifier of deviceCompliancePolicyState
  - `[DeviceComplianceScheduledActionForRuleId <String>]`: The unique identifier of deviceComplianceScheduledActionForRule
  - `[DeviceComplianceSettingStateId <String>]`: The unique identifier of deviceComplianceSettingState
  - `[DeviceComplianceUserStatusId <String>]`: The unique identifier of deviceComplianceUserStatus
  - `[DeviceConfigurationAssignmentId <String>]`: The unique identifier of deviceConfigurationAssignment
  - `[DeviceConfigurationDeviceStatusId <String>]`: The unique identifier of deviceConfigurationDeviceStatus
  - `[DeviceConfigurationId <String>]`: The unique identifier of deviceConfiguration
  - `[DeviceConfigurationStateId <String>]`: The unique identifier of deviceConfigurationState
  - `[DeviceConfigurationUserStatusId <String>]`: The unique identifier of deviceConfigurationUserStatus
  - `[DeviceManagementTroubleshootingEventId <String>]`: The unique identifier of deviceManagementTroubleshootingEvent
  - `[LocalizedNotificationMessageId <String>]`: The unique identifier of localizedNotificationMessage
  - `[ManagedDeviceId <String>]`: The unique identifier of managedDevice
  - `[NotificationMessageTemplateId <String>]`: The unique identifier of notificationMessageTemplate
  - `[SettingStateDeviceSummaryId <String>]`: The unique identifier of settingStateDeviceSummary
  - `[WindowsInformationProtectionAppLearningSummaryId <String>]`: The unique identifier of windowsInformationProtectionAppLearningSummary
  - `[WindowsInformationProtectionNetworkLearningSummaryId <String>]`: The unique identifier of windowsInformationProtectionNetworkLearningSummary

## RELATED LINKS
[Update-MgBetaDeviceManagementWindowsInformationProtectionAppLearningSummary](/powershell/module/Microsoft.Graph.Beta.DeviceManagement/Update-MgBetaDeviceManagementWindowsInformationProtectionAppLearningSummary?view=graph-powershell-beta)

