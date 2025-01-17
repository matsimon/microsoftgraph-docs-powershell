---
external help file: Microsoft.Graph.Mail-help.xml
Module Name: Microsoft.Graph.Mail
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.mail/new-mguserinferenceclassificationoverride
schema: 2.0.0
---

# New-MgUserInferenceClassificationOverride

## SYNOPSIS
Create an override for a sender identified by an SMTP address.
Future messages from that SMTP address will be consistently classified\nas specified in the override.
**Note**

> [!NOTE]
> To view the beta release of this cmdlet, view [New-MgBetaUserInferenceClassificationOverride](/powershell/module/Microsoft.Graph.Beta.Mail/New-MgBetaUserInferenceClassificationOverride?view=graph-powershell-beta)

## SYNTAX

### CreateExpanded (Default)
```
New-MgUserInferenceClassificationOverride -UserId <String> [-AdditionalProperties <Hashtable>]
 [-ClassifyAs <String>] [-Id <String>] [-SenderEmailAddress <IMicrosoftGraphEmailAddress>] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### Create
```
New-MgUserInferenceClassificationOverride -UserId <String>
 -BodyParameter <IMicrosoftGraphInferenceClassificationOverride> [-WhatIf] [-Confirm] [<CommonParameters>]
```

### CreateViaIdentityExpanded
```
New-MgUserInferenceClassificationOverride -InputObject <IMailIdentity> [-AdditionalProperties <Hashtable>]
 [-ClassifyAs <String>] [-Id <String>] [-SenderEmailAddress <IMicrosoftGraphEmailAddress>] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### CreateViaIdentity
```
New-MgUserInferenceClassificationOverride -InputObject <IMailIdentity>
 -BodyParameter <IMicrosoftGraphInferenceClassificationOverride> [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Create an override for a sender identified by an SMTP address.
Future messages from that SMTP address will be consistently classified\nas specified in the override.
**Note**

## EXAMPLES

### Example 1
```
Import-Module Microsoft.Graph.Mail

$params = @{
	classifyAs = "focused"
	senderEmailAddress = @{
		name = "Samantha Booth"
		address = "samanthab@adatum.onmicrosoft.com"
	}
}

# A UPN can also be used as -UserId.
New-MgUserInferenceClassificationOverride -UserId $userId -BodyParameter $params

```
## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
inferenceClassificationOverride
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphInferenceClassificationOverride
Parameter Sets: Create, CreateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ClassifyAs
inferenceClassificationType

```yaml
Type: String
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
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
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
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
Type: IMailIdentity
Parameter Sets: CreateViaIdentityExpanded, CreateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -SenderEmailAddress
emailAddress
To construct, see NOTES section for SENDEREMAILADDRESS properties and create a hash table.

```yaml
Type: IMicrosoftGraphEmailAddress
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UserId
The unique identifier of user

```yaml
Type: String
Parameter Sets: CreateExpanded, Create
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

### Microsoft.Graph.PowerShell.Models.IMailIdentity
### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphInferenceClassificationOverride
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphInferenceClassificationOverride
## NOTES
COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties.
For information on hash tables, run Get-Help about_Hash_Tables.

BODYPARAMETER \<IMicrosoftGraphInferenceClassificationOverride\>: inferenceClassificationOverride
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[Id \<String\>\]: The unique idenfier for an entity.
Read-only.
  \[ClassifyAs \<String\>\]: inferenceClassificationType
  \[SenderEmailAddress \<IMicrosoftGraphEmailAddress\>\]: emailAddress
    \[(Any) \<Object\>\]: This indicates any property can be added to this object.
    \[Address \<String\>\]: The email address of the person or entity.
    \[Name \<String\>\]: The display name of the person or entity.

INPUTOBJECT \<IMailIdentity\>: Identity Parameter
  \[AttachmentId \<String\>\]: The unique identifier of attachment
  \[ExtensionId \<String\>\]: The unique identifier of extension
  \[InferenceClassificationOverrideId \<String\>\]: The unique identifier of inferenceClassificationOverride
  \[MailFolderId \<String\>\]: The unique identifier of mailFolder
  \[MailFolderId1 \<String\>\]: The unique identifier of mailFolder
  \[MessageId \<String\>\]: The unique identifier of message
  \[MessageRuleId \<String\>\]: The unique identifier of messageRule
  \[UserId \<String\>\]: The unique identifier of user

SENDEREMAILADDRESS \<IMicrosoftGraphEmailAddress\>: emailAddress
  \[(Any) \<Object\>\]: This indicates any property can be added to this object.
  \[Address \<String\>\]: The email address of the person or entity.
  \[Name \<String\>\]: The display name of the person or entity.

## RELATED LINKS
[New-MgBetaUserInferenceClassificationOverride](/powershell/module/Microsoft.Graph.Beta.Mail/New-MgBetaUserInferenceClassificationOverride?view=graph-powershell-beta)

[https://learn.microsoft.com/powershell/module/microsoft.graph.mail/new-mguserinferenceclassificationoverride](https://learn.microsoft.com/powershell/module/microsoft.graph.mail/new-mguserinferenceclassificationoverride)



