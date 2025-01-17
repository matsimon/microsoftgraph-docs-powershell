---
external help file: Microsoft.Graph.DeviceManagement.Enrolment-help.xml
Module Name: Microsoft.Graph.DeviceManagement.Enrolment
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.enrolment/new-mgdevicemanagementimporteddeviceidentity
schema: 2.0.0
---

# New-MgDeviceManagementImportedDeviceIdentity

## SYNOPSIS
Create new navigation property to importedDeviceIdentities for deviceManagement

> [!NOTE]
> To view the beta release of this cmdlet, view [New-MgBetaDeviceManagementImportedDeviceIdentity](/powershell/module/Microsoft.Graph.Beta.DeviceManagement.Enrolment/New-MgDeviceManagementImportedDeviceIdentity?view=graph-powershell-beta)

## SYNTAX

### CreateExpanded (Default)
```
New-MgDeviceManagementImportedDeviceIdentity [-AdditionalProperties <Hashtable>] [-CreatedDateTime <DateTime>]
 [-Description <String>] [-EnrollmentState <EnrollmentState>] [-Id <String>]
 [-ImportedDeviceIdentifier <String>] [-ImportedDeviceIdentityType <ImportedDeviceIdentityType>]
 [-LastContactedDateTime <DateTime>] [-LastModifiedDateTime <DateTime>] [-Platform <Platform>] [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

### Create
```
New-MgDeviceManagementImportedDeviceIdentity -BodyParameter <IMicrosoftGraphImportedDeviceIdentity> [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Create new navigation property to importedDeviceIdentities for deviceManagement

## EXAMPLES

### Example 1
```powershell
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

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

### -BodyParameter
The importedDeviceIdentity resource represents a unique hardware identity of a device that has been pre-staged for pre-enrollment configuration.
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphImportedDeviceIdentity
Parameter Sets: Create
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -CreatedDateTime
Created Date Time of the device

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

### -Description
The description of the device

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

### -EnrollmentState
.

```yaml
Type: EnrollmentState
Parameter Sets: CreateExpanded
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
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ImportedDeviceIdentifier
Imported Device Identifier

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

### -ImportedDeviceIdentityType
importedDeviceIdentityType

```yaml
Type: ImportedDeviceIdentityType
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -LastContactedDateTime
Last Contacted Date Time of the device

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

### -LastModifiedDateTime
Last Modified DateTime of the description

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

### -Platform
platform

```yaml
Type: Platform
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphImportedDeviceIdentity
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphImportedDeviceIdentity
## NOTES
Please use Get-Help -Online.

## RELATED LINKS
[New-MgBetaDeviceManagementImportedDeviceIdentity](/powershell/module/Microsoft.Graph.Beta.DeviceManagement.Enrolment/New-MgDeviceManagementImportedDeviceIdentity?view=graph-powershell-beta)

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.enrolment/new-mgdevicemanagementimporteddeviceidentity](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.enrolment/new-mgdevicemanagementimporteddeviceidentity)


