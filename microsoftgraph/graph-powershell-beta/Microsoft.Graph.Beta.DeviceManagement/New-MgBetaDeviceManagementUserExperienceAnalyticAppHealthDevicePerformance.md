---
external help file: Microsoft.Graph.Beta.DeviceManagement-help.xml
Module Name: Microsoft.Graph.Beta.DeviceManagement
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.beta.devicemanagement/new-mgbetadevicemanagementuserexperienceanalyticapphealthdeviceperformance
schema: 2.0.0
---

# New-MgBetaDeviceManagementUserExperienceAnalyticAppHealthDevicePerformance

## SYNOPSIS
Create new navigation property to userExperienceAnalyticsAppHealthDevicePerformance for deviceManagement

> [!NOTE]
> To view the v1.0 release of this cmdlet, view [New-MgDeviceManagementUserExperienceAnalyticAppHealthDevicePerformance](/powershell/module/Microsoft.Graph.DeviceManagement/New-MgDeviceManagementUserExperienceAnalyticAppHealthDevicePerformance?view=graph-powershell-v1.0)

## SYNTAX

### CreateExpanded (Default)
```
New-MgBetaDeviceManagementUserExperienceAnalyticAppHealthDevicePerformance [-AdditionalProperties <Hashtable>]
 [-AppCrashCount <Int32>] [-AppHangCount <Int32>] [-CrashedAppCount <Int32>] [-DeviceAppHealthScore <Double>]
 [-DeviceAppHealthStatus <String>] [-DeviceDisplayName <String>] [-DeviceId <String>]
 [-DeviceManufacturer <String>] [-DeviceModel <String>] [-HealthStatus <UserExperienceAnalyticsHealthState>]
 [-Id <String>] [-MeanTimeToFailureInMinutes <Int32>] [-ProcessedDateTime <DateTime>] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### Create
```
New-MgBetaDeviceManagementUserExperienceAnalyticAppHealthDevicePerformance
 -BodyParameter <IMicrosoftGraphUserExperienceAnalyticsAppHealthDevicePerformance> [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

## DESCRIPTION
Create new navigation property to userExperienceAnalyticsAppHealthDevicePerformance for deviceManagement

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AppCrashCount
The number of app crashes for the device.
Valid values -2147483648 to 2147483647

```yaml
Type: Int32
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AppHangCount
The number of app hangs for the device.
Valid values -2147483648 to 2147483647

```yaml
Type: Int32
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
The user experience analytics device performance entity contains device performance details.
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphUserExperienceAnalyticsAppHealthDevicePerformance
Parameter Sets: Create
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -CrashedAppCount
The number of distinct app crashes for the device.
Valid values -2147483648 to 2147483647

```yaml
Type: Int32
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeviceAppHealthScore
The app health score of the device.
Valid values -1.79769313486232E+308 to 1.79769313486232E+308

```yaml
Type: Double
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeviceAppHealthStatus
The overall app health status of the device.

```yaml
Type: String
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeviceDisplayName
The name of the device.

```yaml
Type: String
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeviceId
The id of the device.

```yaml
Type: String
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeviceManufacturer
The manufacturer name of the device.

```yaml
Type: String
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeviceModel
The model name of the device.

```yaml
Type: String
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -HealthStatus
userExperienceAnalyticsHealthState

```yaml
Type: UserExperienceAnalyticsHealthState
Parameter Sets: CreateExpanded
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
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MeanTimeToFailureInMinutes
The mean time to failure for the device in minutes.
Valid values -2147483648 to 2147483647

```yaml
Type: Int32
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ProcessedDateTime
The date and time when the statistics were last computed.

```yaml
Type: DateTime
Parameter Sets: CreateExpanded
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

### Microsoft.Graph.Beta.PowerShell.Models.IMicrosoftGraphUserExperienceAnalyticsAppHealthDevicePerformance
## OUTPUTS

### Microsoft.Graph.Beta.PowerShell.Models.IMicrosoftGraphUserExperienceAnalyticsAppHealthDevicePerformance
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


`BODYPARAMETER <IMicrosoftGraphUserExperienceAnalyticsAppHealthDevicePerformance>`: The user experience analytics device performance entity contains device performance details.
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: The unique identifier for an entity. Read-only.
  - `[AppCrashCount <Int32?>]`: The number of app crashes for the device. Valid values -2147483648 to 2147483647
  - `[AppHangCount <Int32?>]`: The number of app hangs for the device. Valid values -2147483648 to 2147483647
  - `[CrashedAppCount <Int32?>]`: The number of distinct app crashes for the device. Valid values -2147483648 to 2147483647
  - `[DeviceAppHealthScore <Double?>]`: The app health score of the device. Valid values -1.79769313486232E+308 to 1.79769313486232E+308
  - `[DeviceDisplayName <String>]`: The name of the device.
  - `[DeviceId <String>]`: The id of the device.
  - `[DeviceManufacturer <String>]`: The manufacturer name of the device.
  - `[DeviceModel <String>]`: The model name of the device.
  - `[HealthStatus <UserExperienceAnalyticsHealthState?>]`: userExperienceAnalyticsHealthState
  - `[MeanTimeToFailureInMinutes <Int32?>]`: The mean time to failure for the device in minutes. Valid values -2147483648 to 2147483647
  - `[ProcessedDateTime <DateTime?>]`: The date and time when the statistics were last computed.

## RELATED LINKS
[New-MgDeviceManagementUserExperienceAnalyticAppHealthDevicePerformance](/powershell/module/Microsoft.Graph.DeviceManagement/New-MgDeviceManagementUserExperienceAnalyticAppHealthDevicePerformance?view=graph-powershell-v1.0)

