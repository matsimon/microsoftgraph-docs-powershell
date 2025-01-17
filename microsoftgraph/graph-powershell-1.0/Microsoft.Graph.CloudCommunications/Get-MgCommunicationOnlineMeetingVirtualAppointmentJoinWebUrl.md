---
external help file: Microsoft.Graph.CloudCommunications-help.xml
Module Name: Microsoft.Graph.CloudCommunications
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.cloudcommunications/get-mgcommunicationonlinemeetingvirtualappointmentjoinweburl
schema: 2.0.0
---

# Get-MgCommunicationOnlineMeetingVirtualAppointmentJoinWebUrl

## SYNOPSIS
Invoke function getVirtualAppointmentJoinWebUrl

> [!NOTE]
> To view the beta release of this cmdlet, view [Get-MgBetaCommunicationOnlineMeetingVirtualAppointmentJoinWebUrl](/powershell/module/Microsoft.Graph.Beta.CloudCommunications/Get-MgBetaCommunicationOnlineMeetingVirtualAppointmentJoinWebUrl?view=graph-powershell-beta)

## SYNTAX

### Get (Default)
```
Get-MgCommunicationOnlineMeetingVirtualAppointmentJoinWebUrl -OnlineMeetingId <String> [<CommonParameters>]
```

### GetViaIdentity
```
Get-MgCommunicationOnlineMeetingVirtualAppointmentJoinWebUrl -InputObject <ICloudCommunicationsIdentity>
 [<CommonParameters>]
```

## DESCRIPTION
Invoke function getVirtualAppointmentJoinWebUrl

## PARAMETERS

### -InputObject
Identity Parameter
To construct, see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: ICloudCommunicationsIdentity
Parameter Sets: GetViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -OnlineMeetingId
The unique identifier of onlineMeeting

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

### Microsoft.Graph.PowerShell.Models.ICloudCommunicationsIdentity
## OUTPUTS

### System.String
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


`INPUTOBJECT <ICloudCommunicationsIdentity>`: Identity Parameter
  - `[AttendanceRecordId <String>]`: The unique identifier of attendanceRecord
  - `[AudioRoutingGroupId <String>]`: The unique identifier of audioRoutingGroup
  - `[CallId <String>]`: The unique identifier of call
  - `[CallRecordId <String>]`: The unique identifier of callRecord
  - `[CommsOperationId <String>]`: The unique identifier of commsOperation
  - `[ContentSharingSessionId <String>]`: The unique identifier of contentSharingSession
  - `[MeetingAttendanceReportId <String>]`: The unique identifier of meetingAttendanceReport
  - `[OnlineMeetingId <String>]`: The unique identifier of onlineMeeting
  - `[ParticipantId <String>]`: The unique identifier of participant
  - `[PresenceId <String>]`: The unique identifier of presence
  - `[SessionId <String>]`: The unique identifier of session
  - `[UserId <String>]`: The unique identifier of user

## RELATED LINKS
[Get-MgBetaCommunicationOnlineMeetingVirtualAppointmentJoinWebUrl](/powershell/module/Microsoft.Graph.Beta.CloudCommunications/Get-MgBetaCommunicationOnlineMeetingVirtualAppointmentJoinWebUrl?view=graph-powershell-beta)

