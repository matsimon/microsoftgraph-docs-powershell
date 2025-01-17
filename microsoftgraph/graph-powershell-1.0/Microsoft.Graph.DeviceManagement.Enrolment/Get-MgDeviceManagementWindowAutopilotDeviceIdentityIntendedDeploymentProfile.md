---
external help file: Microsoft.Graph.DeviceManagement.Enrolment-help.xml
Module Name: Microsoft.Graph.DeviceManagement.Enrolment
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.enrolment/get-mgdevicemanagementwindowautopilotdeviceidentityintendeddeploymentprofile
schema: 2.0.0
---

# Get-MgDeviceManagementWindowAutopilotDeviceIdentityIntendedDeploymentProfile

## SYNOPSIS
Deployment profile intended to be assigned to the Windows autopilot device.

> [!NOTE]
> To view the beta release of this cmdlet, view [Get-MgBetaDeviceManagementWindowAutopilotDeviceIdentityIntendedDeploymentProfile](/powershell/module/Microsoft.Graph.Beta.DeviceManagement.Enrolment/Get-MgDeviceManagementWindowAutopilotDeviceIdentityIntendedDeploymentProfile?view=graph-powershell-beta)

## SYNTAX

### Get (Default)
```
Get-MgDeviceManagementWindowAutopilotDeviceIdentityIntendedDeploymentProfile
 -WindowsAutopilotDeviceIdentityId <String> [-ExpandProperty <String[]>] [-Property <String[]>]
 [<CommonParameters>]
```

### GetViaIdentity
```
Get-MgDeviceManagementWindowAutopilotDeviceIdentityIntendedDeploymentProfile
 -InputObject <IDeviceManagementEnrolmentIdentity> [-ExpandProperty <String[]>] [-Property <String[]>]
 [<CommonParameters>]
```

## DESCRIPTION
Deployment profile intended to be assigned to the Windows autopilot device.

## EXAMPLES

### Example 1
```powershell
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -ExpandProperty
Expand related entities

```yaml
Type: String[]
Parameter Sets: (All)
Aliases: Expand

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
Parameter Sets: GetViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Property
Select properties to be returned

```yaml
Type: String[]
Parameter Sets: (All)
Aliases: Select

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WindowsAutopilotDeviceIdentityId
The unique identifier of windowsAutopilotDeviceIdentity

```yaml
Type: String
Parameter Sets: Get
Aliases:

Required: True
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphWindowsAutopilotDeploymentProfile
## NOTES
Please use Get-Help -Online.

## RELATED LINKS
[Get-MgBetaDeviceManagementWindowAutopilotDeviceIdentityIntendedDeploymentProfile](/powershell/module/Microsoft.Graph.Beta.DeviceManagement.Enrolment/Get-MgDeviceManagementWindowAutopilotDeviceIdentityIntendedDeploymentProfile?view=graph-powershell-beta)

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.enrolment/get-mgdevicemanagementwindowautopilotdeviceidentityintendeddeploymentprofile](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.enrolment/get-mgdevicemanagementwindowautopilotdeviceidentityintendeddeploymentprofile)


