---
external help file: Microsoft.Graph.DeviceManagement.Enrolment-help.xml
Module Name: Microsoft.Graph.DeviceManagement.Enrolment
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.enrolment/remove-mgrolemanagementdirectoryroleassignmentapproval
schema: 2.0.0
---

# Remove-MgRoleManagementDirectoryRoleAssignmentApproval

## SYNOPSIS
Delete navigation property roleAssignmentApprovals for roleManagement

> [!NOTE]
> To view the beta release of this cmdlet, view [Remove-MgBetaRoleManagementDirectoryRoleAssignmentApproval](/powershell/module/Microsoft.Graph.Beta.DeviceManagement.Enrolment/Remove-MgRoleManagementDirectoryRoleAssignmentApproval?view=graph-powershell-beta)

## SYNTAX

### Delete (Default)
```
Remove-MgRoleManagementDirectoryRoleAssignmentApproval -ApprovalId <String> [-IfMatch <String>] [-PassThru]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### DeleteViaIdentity
```
Remove-MgRoleManagementDirectoryRoleAssignmentApproval -InputObject <IDeviceManagementEnrolmentIdentity>
 [-IfMatch <String>] [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Delete navigation property roleAssignmentApprovals for roleManagement

## EXAMPLES

### Example 1
```powershell
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -ApprovalId
The unique identifier of approval

```yaml
Type: String
Parameter Sets: Delete
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IfMatch
ETag

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InputObject
Identity Parameter
To construct, please use Get-Help -Online and see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: IDeviceManagementEnrolmentIdentity
Parameter Sets: DeleteViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
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

### Microsoft.Graph.PowerShell.Models.IDeviceManagementEnrolmentIdentity
## OUTPUTS

### System.Boolean
## NOTES
Please use Get-Help -Online.

## RELATED LINKS
[Remove-MgBetaRoleManagementDirectoryRoleAssignmentApproval](/powershell/module/Microsoft.Graph.Beta.DeviceManagement.Enrolment/Remove-MgRoleManagementDirectoryRoleAssignmentApproval?view=graph-powershell-beta)

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.enrolment/remove-mgrolemanagementdirectoryroleassignmentapproval](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.enrolment/remove-mgrolemanagementdirectoryroleassignmentapproval)


