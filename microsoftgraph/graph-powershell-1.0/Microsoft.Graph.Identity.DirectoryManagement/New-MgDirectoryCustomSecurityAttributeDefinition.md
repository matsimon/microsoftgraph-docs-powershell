---
external help file: Microsoft.Graph.Identity.DirectoryManagement-help.xml
Module Name: Microsoft.Graph.Identity.DirectoryManagement
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.identity.directorymanagement/new-mgdirectorycustomsecurityattributedefinition
schema: 2.0.0
---

# New-MgDirectoryCustomSecurityAttributeDefinition

## SYNOPSIS
Create new navigation property to customSecurityAttributeDefinitions for directory

> [!NOTE]
> To view the beta release of this cmdlet, view [New-MgBetaDirectoryCustomSecurityAttributeDefinition](/powershell/module/Microsoft.Graph.Beta.Identity.DirectoryManagement/New-MgBetaDirectoryCustomSecurityAttributeDefinition?view=graph-powershell-beta)

## SYNTAX

### CreateExpanded (Default)
```
New-MgDirectoryCustomSecurityAttributeDefinition [-AdditionalProperties <Hashtable>]
 [-AllowedValues <IMicrosoftGraphAllowedValue[]>] [-AttributeSet <String>] [-Description <String>]
 [-Id <String>] [-IsCollection] [-IsSearchable] [-Name <String>] [-Status <String>] [-Type <String>]
 [-UsePreDefinedValuesOnly] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Create
```
New-MgDirectoryCustomSecurityAttributeDefinition
 -BodyParameter <IMicrosoftGraphCustomSecurityAttributeDefinition> [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Create new navigation property to customSecurityAttributeDefinitions for directory

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

### -AllowedValues
.
To construct, see NOTES section for ALLOWEDVALUES properties and create a hash table.

```yaml
Type: IMicrosoftGraphAllowedValue[]
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AttributeSet
.

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

### -BodyParameter
customSecurityAttributeDefinition
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphCustomSecurityAttributeDefinition
Parameter Sets: Create
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Description
.

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

### -IsCollection
.

```yaml
Type: SwitchParameter
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsSearchable
.

```yaml
Type: SwitchParameter
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Name
.

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

### -Status
.

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

### -Type
.

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

### -UsePreDefinedValuesOnly
.

```yaml
Type: SwitchParameter
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphCustomSecurityAttributeDefinition
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphCustomSecurityAttributeDefinition
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


`ALLOWEDVALUES <IMicrosoftGraphAllowedValue[]>`: .
  - `[Id <String>]`: The unique idenfier for an entity. Read-only.
  - `[IsActive <Boolean?>]`: 

`BODYPARAMETER <IMicrosoftGraphCustomSecurityAttributeDefinition>`: customSecurityAttributeDefinition
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: The unique idenfier for an entity. Read-only.
  - `[AllowedValues <IMicrosoftGraphAllowedValue[]>]`: 
    - `[Id <String>]`: The unique idenfier for an entity. Read-only.
    - `[IsActive <Boolean?>]`: 
  - `[AttributeSet <String>]`: 
  - `[Description <String>]`: 
  - `[IsCollection <Boolean?>]`: 
  - `[IsSearchable <Boolean?>]`: 
  - `[Name <String>]`: 
  - `[Status <String>]`: 
  - `[Type <String>]`: 
  - `[UsePreDefinedValuesOnly <Boolean?>]`: 

## RELATED LINKS
[New-MgBetaDirectoryCustomSecurityAttributeDefinition](/powershell/module/Microsoft.Graph.Beta.Identity.DirectoryManagement/New-MgBetaDirectoryCustomSecurityAttributeDefinition?view=graph-powershell-beta)

