---
external help file: Microsoft.Graph.Beta.Devices.CorporateManagement-help.xml
Module Name: Microsoft.Graph.Beta.Devices.CorporateManagement
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.beta.devices.corporatemanagement/update-mgbetadeviceappmanagementwdacsupplementalpolicy
schema: 2.0.0
---

# Update-MgBetaDeviceAppManagementWdacSupplementalPolicy

## SYNOPSIS
Update the navigation property wdacSupplementalPolicies in deviceAppManagement

> [!NOTE]
> To view the v1.0 release of this cmdlet, view [Update-MgDeviceAppManagementWdacSupplementalPolicy](/powershell/module/Microsoft.Graph.Devices.CorporateManagement/Update-MgDeviceAppManagementWdacSupplementalPolicy?view=graph-powershell-v1.0)

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgBetaDeviceAppManagementWdacSupplementalPolicy
 -WindowsDefenderApplicationControlSupplementalPolicyId <String> [-AdditionalProperties <Hashtable>]
 [-Assignments <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyAssignment[]>]
 [-ContentFileName <String>] [-ContentInputFile <String>] [-CreationDateTime <DateTime>]
 [-DeploySummary <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyDeploymentSummary>]
 [-Description <String>]
 [-DeviceStatuses <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyDeploymentStatus[]>]
 [-DisplayName <String>] [-Id <String>] [-LastModifiedDateTime <DateTime>] [-RoleScopeTagIds <String[]>]
 [-Version <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Update
```
Update-MgBetaDeviceAppManagementWdacSupplementalPolicy
 -WindowsDefenderApplicationControlSupplementalPolicyId <String>
 -BodyParameter <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicy> [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgBetaDeviceAppManagementWdacSupplementalPolicy -InputObject <IDevicesCorporateManagementIdentity>
 [-AdditionalProperties <Hashtable>]
 [-Assignments <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyAssignment[]>]
 [-ContentFileName <String>] [-ContentInputFile <String>] [-CreationDateTime <DateTime>]
 [-DeploySummary <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyDeploymentSummary>]
 [-Description <String>]
 [-DeviceStatuses <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyDeploymentStatus[]>]
 [-DisplayName <String>] [-Id <String>] [-LastModifiedDateTime <DateTime>] [-RoleScopeTagIds <String[]>]
 [-Version <String>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgBetaDeviceAppManagementWdacSupplementalPolicy -InputObject <IDevicesCorporateManagementIdentity>
 -BodyParameter <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicy> [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

## DESCRIPTION
Update the navigation property wdacSupplementalPolicies in deviceAppManagement

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

### -Assignments
The associated group assignments for this WindowsDefenderApplicationControl supplemental policy.
To construct, see NOTES section for ASSIGNMENTS properties and create a hash table.

```yaml
Type: IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyAssignment[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
windowsDefenderApplicationControlSupplementalPolicy
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicy
Parameter Sets: Update, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ContentFileName
The WindowsDefenderApplicationControl supplemental policy content's file name.

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

### -ContentInputFile
Input File for Content (The WindowsDefenderApplicationControl supplemental policy content in byte array format.)

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

### -CreationDateTime
The date and time when the WindowsDefenderApplicationControl supplemental policy was uploaded.

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

### -DeploySummary
Contains properties for the deployment summary of a WindowsDefenderApplicationControl supplemental policy.
To construct, see NOTES section for DEPLOYSUMMARY properties and create a hash table.

```yaml
Type: IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyDeploymentSummary
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Description
The description of WindowsDefenderApplicationControl supplemental policy.

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

### -DeviceStatuses
The list of device deployment states for this WindowsDefenderApplicationControl supplemental policy.
To construct, see NOTES section for DEVICESTATUSES properties and create a hash table.

```yaml
Type: IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyDeploymentStatus[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisplayName
The display name of WindowsDefenderApplicationControl supplemental policy.

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
Type: IDevicesCorporateManagementIdentity
Parameter Sets: UpdateViaIdentityExpanded, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -LastModifiedDateTime
The date and time when the WindowsDefenderApplicationControl supplemental policy was last modified.

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

### -RoleScopeTagIds
List of Scope Tags for this WindowsDefenderApplicationControl supplemental policy entity.

```yaml
Type: String[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Version
The WindowsDefenderApplicationControl supplemental policy's version.

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

### -WindowsDefenderApplicationControlSupplementalPolicyId
The unique identifier of windowsDefenderApplicationControlSupplementalPolicy

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

### Microsoft.Graph.Beta.PowerShell.Models.IDevicesCorporateManagementIdentity
### Microsoft.Graph.Beta.PowerShell.Models.IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicy
## OUTPUTS

### Microsoft.Graph.Beta.PowerShell.Models.IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicy
## NOTES

ALIASES

Update-MgDeviceAppMgtWdacSupplementalPolicy

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


`ASSIGNMENTS <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyAssignment[]>`: The associated group assignments for this WindowsDefenderApplicationControl supplemental policy.
  - `[Id <String>]`: The unique identifier for an entity. Read-only.
  - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: Base type for assignment targets.
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[DeviceAndAppManagementAssignmentFilterId <String>]`: The Id of the filter for the target assignment.
    - `[DeviceAndAppManagementAssignmentFilterType <DeviceAndAppManagementAssignmentFilterType?>]`: Represents type of the assignment filter.

`BODYPARAMETER <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicy>`: windowsDefenderApplicationControlSupplementalPolicy
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: The unique identifier for an entity. Read-only.
  - `[Assignments <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyAssignment[]>]`: The associated group assignments for this WindowsDefenderApplicationControl supplemental policy.
    - `[Id <String>]`: The unique identifier for an entity. Read-only.
    - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: Base type for assignment targets.
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[DeviceAndAppManagementAssignmentFilterId <String>]`: The Id of the filter for the target assignment.
      - `[DeviceAndAppManagementAssignmentFilterType <DeviceAndAppManagementAssignmentFilterType?>]`: Represents type of the assignment filter.
  - `[Content <Byte[]>]`: The WindowsDefenderApplicationControl supplemental policy content in byte array format.
  - `[ContentFileName <String>]`: The WindowsDefenderApplicationControl supplemental policy content's file name.
  - `[CreationDateTime <DateTime?>]`: The date and time when the WindowsDefenderApplicationControl supplemental policy was uploaded.
  - `[DeploySummary <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyDeploymentSummary>]`: Contains properties for the deployment summary of a WindowsDefenderApplicationControl supplemental policy.
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: The unique identifier for an entity. Read-only.
    - `[DeployedDeviceCount <Int32?>]`: Number of Devices that have successfully deployed this WindowsDefenderApplicationControl supplemental policy.
    - `[FailedDeviceCount <Int32?>]`: Number of Devices that have failed to deploy this WindowsDefenderApplicationControl supplemental policy.
  - `[Description <String>]`: The description of WindowsDefenderApplicationControl supplemental policy.
  - `[DeviceStatuses <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyDeploymentStatus[]>]`: The list of device deployment states for this WindowsDefenderApplicationControl supplemental policy.
    - `[Id <String>]`: The unique identifier for an entity. Read-only.
    - `[DeploymentStatus <WindowsDefenderApplicationControlSupplementalPolicyStatuses?>]`: Enum values for the various WindowsDefenderApplicationControl supplemental policy deployment statuses.
    - `[DeviceId <String>]`: Device ID.
    - `[DeviceName <String>]`: Device name.
    - `[LastSyncDateTime <DateTime?>]`: Last sync date time.
    - `[OSDescription <String>]`: Windows OS Version Description.
    - `[OSVersion <String>]`: Windows OS Version.
    - `[Policy <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicy>]`: windowsDefenderApplicationControlSupplementalPolicy
    - `[PolicyVersion <String>]`: Human readable version of the WindowsDefenderApplicationControl supplemental policy.
    - `[UserName <String>]`: The name of the user of this device.
    - `[UserPrincipalName <String>]`: User Principal Name.
  - `[DisplayName <String>]`: The display name of WindowsDefenderApplicationControl supplemental policy.
  - `[LastModifiedDateTime <DateTime?>]`: The date and time when the WindowsDefenderApplicationControl supplemental policy was last modified.
  - `[RoleScopeTagIds <String[]>]`: List of Scope Tags for this WindowsDefenderApplicationControl supplemental policy entity.
  - `[Version <String>]`: The WindowsDefenderApplicationControl supplemental policy's version.

`DEPLOYSUMMARY <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyDeploymentSummary>`: Contains properties for the deployment summary of a WindowsDefenderApplicationControl supplemental policy.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: The unique identifier for an entity. Read-only.
  - `[DeployedDeviceCount <Int32?>]`: Number of Devices that have successfully deployed this WindowsDefenderApplicationControl supplemental policy.
  - `[FailedDeviceCount <Int32?>]`: Number of Devices that have failed to deploy this WindowsDefenderApplicationControl supplemental policy.

`DEVICESTATUSES <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyDeploymentStatus[]>`: The list of device deployment states for this WindowsDefenderApplicationControl supplemental policy.
  - `[Id <String>]`: The unique identifier for an entity. Read-only.
  - `[DeploymentStatus <WindowsDefenderApplicationControlSupplementalPolicyStatuses?>]`: Enum values for the various WindowsDefenderApplicationControl supplemental policy deployment statuses.
  - `[DeviceId <String>]`: Device ID.
  - `[DeviceName <String>]`: Device name.
  - `[LastSyncDateTime <DateTime?>]`: Last sync date time.
  - `[OSDescription <String>]`: Windows OS Version Description.
  - `[OSVersion <String>]`: Windows OS Version.
  - `[Policy <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicy>]`: windowsDefenderApplicationControlSupplementalPolicy
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: The unique identifier for an entity. Read-only.
    - `[Assignments <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyAssignment[]>]`: The associated group assignments for this WindowsDefenderApplicationControl supplemental policy.
      - `[Id <String>]`: The unique identifier for an entity. Read-only.
      - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: Base type for assignment targets.
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[DeviceAndAppManagementAssignmentFilterId <String>]`: The Id of the filter for the target assignment.
        - `[DeviceAndAppManagementAssignmentFilterType <DeviceAndAppManagementAssignmentFilterType?>]`: Represents type of the assignment filter.
    - `[Content <Byte[]>]`: The WindowsDefenderApplicationControl supplemental policy content in byte array format.
    - `[ContentFileName <String>]`: The WindowsDefenderApplicationControl supplemental policy content's file name.
    - `[CreationDateTime <DateTime?>]`: The date and time when the WindowsDefenderApplicationControl supplemental policy was uploaded.
    - `[DeploySummary <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyDeploymentSummary>]`: Contains properties for the deployment summary of a WindowsDefenderApplicationControl supplemental policy.
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[Id <String>]`: The unique identifier for an entity. Read-only.
      - `[DeployedDeviceCount <Int32?>]`: Number of Devices that have successfully deployed this WindowsDefenderApplicationControl supplemental policy.
      - `[FailedDeviceCount <Int32?>]`: Number of Devices that have failed to deploy this WindowsDefenderApplicationControl supplemental policy.
    - `[Description <String>]`: The description of WindowsDefenderApplicationControl supplemental policy.
    - `[DeviceStatuses <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyDeploymentStatus[]>]`: The list of device deployment states for this WindowsDefenderApplicationControl supplemental policy.
    - `[DisplayName <String>]`: The display name of WindowsDefenderApplicationControl supplemental policy.
    - `[LastModifiedDateTime <DateTime?>]`: The date and time when the WindowsDefenderApplicationControl supplemental policy was last modified.
    - `[RoleScopeTagIds <String[]>]`: List of Scope Tags for this WindowsDefenderApplicationControl supplemental policy entity.
    - `[Version <String>]`: The WindowsDefenderApplicationControl supplemental policy's version.
  - `[PolicyVersion <String>]`: Human readable version of the WindowsDefenderApplicationControl supplemental policy.
  - `[UserName <String>]`: The name of the user of this device.
  - `[UserPrincipalName <String>]`: User Principal Name.

`INPUTOBJECT <IDevicesCorporateManagementIdentity>`: Identity Parameter
  - `[AndroidManagedAppProtectionId <String>]`: The unique identifier of androidManagedAppProtection
  - `[AppLogCollectionRequestId <String>]`: The unique identifier of appLogCollectionRequest
  - `[AssignmentFilterEvaluationStatusDetailsId <String>]`: The unique identifier of assignmentFilterEvaluationStatusDetails
  - `[BundleId <String>]`: Usage: bundleId='{bundleId}'
  - `[DefaultManagedAppProtectionId <String>]`: The unique identifier of defaultManagedAppProtection
  - `[DetectedAppId <String>]`: The unique identifier of detectedApp
  - `[DeviceAppManagementTaskId <String>]`: The unique identifier of deviceAppManagementTask
  - `[DeviceCompliancePolicyStateId <String>]`: The unique identifier of deviceCompliancePolicyState
  - `[DeviceConfigurationStateId <String>]`: The unique identifier of deviceConfigurationState
  - `[DeviceEnrollmentConfigurationId <String>]`: The unique identifier of deviceEnrollmentConfiguration
  - `[DeviceId <String>]`: Property in multi-part unique identifier of deviceHealthScriptPolicyState
  - `[DeviceInstallStateId <String>]`: The unique identifier of deviceInstallState
  - `[DeviceLogCollectionResponseId <String>]`: The unique identifier of deviceLogCollectionResponse
  - `[DeviceManagementConfigurationSettingDefinitionId <String>]`: The unique identifier of deviceManagementConfigurationSettingDefinition
  - `[DeviceManagementConfigurationSettingId <String>]`: The unique identifier of deviceManagementConfigurationSetting
  - `[DeviceManagementTroubleshootingEventId <String>]`: The unique identifier of deviceManagementTroubleshootingEvent
  - `[EnrollmentConfigurationAssignmentId <String>]`: The unique identifier of enrollmentConfigurationAssignment
  - `[EnterpriseCodeSigningCertificateId <String>]`: The unique identifier of enterpriseCodeSigningCertificate
  - `[Id <String>]`: Property in multi-part unique identifier of deviceHealthScriptPolicyState
  - `[IosLobAppProvisioningConfigurationAssignmentId <String>]`: The unique identifier of iosLobAppProvisioningConfigurationAssignment
  - `[IosLobAppProvisioningConfigurationId <String>]`: The unique identifier of iosLobAppProvisioningConfiguration
  - `[IosManagedAppProtectionId <String>]`: The unique identifier of iosManagedAppProtection
  - `[ManagedAppOperationId <String>]`: The unique identifier of managedAppOperation
  - `[ManagedAppPolicyId <String>]`: The unique identifier of managedAppPolicy
  - `[ManagedAppRegistrationId <String>]`: The unique identifier of managedAppRegistration
  - `[ManagedAppStatusId <String>]`: The unique identifier of managedAppStatus
  - `[ManagedDeviceId <String>]`: The unique identifier of managedDevice
  - `[ManagedDeviceMobileAppConfigurationAssignmentId <String>]`: The unique identifier of managedDeviceMobileAppConfigurationAssignment
  - `[ManagedDeviceMobileAppConfigurationDeviceStatusId <String>]`: The unique identifier of managedDeviceMobileAppConfigurationDeviceStatus
  - `[ManagedDeviceMobileAppConfigurationId <String>]`: The unique identifier of managedDeviceMobileAppConfiguration
  - `[ManagedDeviceMobileAppConfigurationStateId <String>]`: The unique identifier of managedDeviceMobileAppConfigurationState
  - `[ManagedDeviceMobileAppConfigurationUserStatusId <String>]`: The unique identifier of managedDeviceMobileAppConfigurationUserStatus
  - `[ManagedEBookAssignmentId <String>]`: The unique identifier of managedEBookAssignment
  - `[ManagedEBookCategoryId <String>]`: The unique identifier of managedEBookCategory
  - `[ManagedEBookId <String>]`: The unique identifier of managedEBook
  - `[ManagedMobileAppId <String>]`: The unique identifier of managedMobileApp
  - `[MdmWindowsInformationProtectionPolicyId <String>]`: The unique identifier of mdmWindowsInformationProtectionPolicy
  - `[MobileAppAssignmentId <String>]`: The unique identifier of mobileAppAssignment
  - `[MobileAppCategoryId <String>]`: The unique identifier of mobileAppCategory
  - `[MobileAppId <String>]`: The unique identifier of mobileApp
  - `[MobileAppIntentAndStateId <String>]`: The unique identifier of mobileAppIntentAndState
  - `[MobileAppProvisioningConfigGroupAssignmentId <String>]`: The unique identifier of mobileAppProvisioningConfigGroupAssignment
  - `[MobileAppRelationshipId <String>]`: The unique identifier of mobileAppRelationship
  - `[MobileAppTroubleshootingEventId <String>]`: The unique identifier of mobileAppTroubleshootingEvent
  - `[PolicyId <String>]`: Property in multi-part unique identifier of deviceHealthScriptPolicyState
  - `[PolicySetAssignmentId <String>]`: The unique identifier of policySetAssignment
  - `[PolicySetId <String>]`: The unique identifier of policySet
  - `[PolicySetItemId <String>]`: The unique identifier of policySetItem
  - `[SecurityBaselineSettingStateId <String>]`: The unique identifier of securityBaselineSettingState
  - `[SecurityBaselineStateId <String>]`: The unique identifier of securityBaselineState
  - `[TargetedManagedAppConfigurationId <String>]`: The unique identifier of targetedManagedAppConfiguration
  - `[TargetedManagedAppPolicyAssignmentId <String>]`: The unique identifier of targetedManagedAppPolicyAssignment
  - `[UserId <String>]`: The unique identifier of user
  - `[UserInstallStateSummaryId <String>]`: The unique identifier of userInstallStateSummary
  - `[VppTokenId <String>]`: The unique identifier of vppToken
  - `[WindowsDefenderApplicationControlSupplementalPolicyAssignmentId <String>]`: The unique identifier of windowsDefenderApplicationControlSupplementalPolicyAssignment
  - `[WindowsDefenderApplicationControlSupplementalPolicyDeploymentStatusId <String>]`: The unique identifier of windowsDefenderApplicationControlSupplementalPolicyDeploymentStatus
  - `[WindowsDefenderApplicationControlSupplementalPolicyId <String>]`: The unique identifier of windowsDefenderApplicationControlSupplementalPolicy
  - `[WindowsDeviceMalwareStateId <String>]`: The unique identifier of windowsDeviceMalwareState
  - `[WindowsInformationProtectionAppLockerFileId <String>]`: The unique identifier of windowsInformationProtectionAppLockerFile
  - `[WindowsInformationProtectionDeviceRegistrationId <String>]`: The unique identifier of windowsInformationProtectionDeviceRegistration
  - `[WindowsInformationProtectionPolicyId <String>]`: The unique identifier of windowsInformationProtectionPolicy
  - `[WindowsInformationProtectionWipeActionId <String>]`: The unique identifier of windowsInformationProtectionWipeAction
  - `[WindowsManagedAppProtectionId <String>]`: The unique identifier of windowsManagedAppProtection

## RELATED LINKS
[Update-MgDeviceAppManagementWdacSupplementalPolicy](/powershell/module/Microsoft.Graph.Devices.CorporateManagement/Update-MgDeviceAppManagementWdacSupplementalPolicy?view=graph-powershell-v1.0)

## RELATED LINKS
[Update-MgDeviceAppManagementWdacSupplementalPolicy](/powershell/module/Microsoft.Graph.Devices.CorporateManagement/Update-MgDeviceAppManagementWdacSupplementalPolicy?view=graph-powershell-v1.0)

