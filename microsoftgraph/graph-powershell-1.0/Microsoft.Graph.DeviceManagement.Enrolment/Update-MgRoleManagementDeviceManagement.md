---
external help file: Microsoft.Graph.DeviceManagement.Enrolment-help.xml
Module Name: Microsoft.Graph.DeviceManagement.Enrolment
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.enrolment/update-mgrolemanagementdevicemanagement
schema: 2.0.0
---

# Update-MgRoleManagementDeviceManagement

## SYNOPSIS
Update the navigation property deviceManagement in roleManagement

> [!NOTE]
> To view the beta release of this cmdlet, view [Update-MgBetaRoleManagementDeviceManagement](/powershell/module/Microsoft.Graph.Beta.DeviceManagement.Enrolment/Update-MgRoleManagementDeviceManagement?view=graph-powershell-beta)

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgRoleManagementDeviceManagement [-AdditionalProperties <Hashtable>] [-Id <String>]
 [-ResourceNamespaces <IMicrosoftGraphUnifiedRbacResourceNamespace1[]>]
 [-RoleAssignments <IMicrosoftGraphUnifiedRoleAssignmentMultiple[]>]
 [-RoleDefinitions <IMicrosoftGraphUnifiedRoleDefinition[]>] [-PassThru] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### Update
```
Update-MgRoleManagementDeviceManagement -BodyParameter <IMicrosoftGraphRbacApplicationMultiple> [-PassThru]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Update the navigation property deviceManagement in roleManagement

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
Parameter Sets: UpdateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
rbacApplicationMultiple
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphRbacApplicationMultiple
Parameter Sets: Update
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Id
The unique idenfier for an entity.
Read-only.

```yaml
Type: String
Parameter Sets: UpdateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PassThru
Returns true when the command succeeds

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -ResourceNamespaces
.
To construct, please use Get-Help -Online and see NOTES section for RESOURCENAMESPACES properties and create a hash table.

```yaml
Type: IMicrosoftGraphUnifiedRbacResourceNamespace1[]
Parameter Sets: UpdateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RoleAssignments
.
To construct, please use Get-Help -Online and see NOTES section for ROLEASSIGNMENTS properties and create a hash table.

```yaml
Type: IMicrosoftGraphUnifiedRoleAssignmentMultiple[]
Parameter Sets: UpdateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RoleDefinitions
.
To construct, please use Get-Help -Online and see NOTES section for ROLEDEFINITIONS properties and create a hash table.

```yaml
Type: IMicrosoftGraphUnifiedRoleDefinition[]
Parameter Sets: UpdateExpanded
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphRbacApplicationMultiple
## OUTPUTS

### System.Boolean
## NOTES
Please use Get-Help -Online.

## RELATED LINKS
[Update-MgBetaRoleManagementDeviceManagement](/powershell/module/Microsoft.Graph.Beta.DeviceManagement.Enrolment/Update-MgRoleManagementDeviceManagement?view=graph-powershell-beta)

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.enrolment/update-mgrolemanagementdevicemanagement](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.enrolment/update-mgrolemanagementdevicemanagement)


