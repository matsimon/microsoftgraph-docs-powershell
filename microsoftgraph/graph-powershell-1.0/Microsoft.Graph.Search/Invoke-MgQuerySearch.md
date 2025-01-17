---
external help file: Microsoft.Graph.Search-help.xml
Module Name: Microsoft.Graph.Search
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.search/invoke-mgquerysearch
schema: 2.0.0
---

# Invoke-MgQuerySearch

## SYNOPSIS
Invoke action query

> [!NOTE]
> To view the beta release of this cmdlet, view [Invoke-MgBetaQuerySearch](/powershell/module/Microsoft.Graph.Beta.Search/Invoke-MgBetaQuerySearch?view=graph-powershell-beta)

## SYNTAX

### QueryExpanded (Default)
```
Invoke-MgQuerySearch [-AdditionalProperties <Hashtable>] [-Requests <IMicrosoftGraphSearchRequest[]>] [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

### Query
```
Invoke-MgQuerySearch -Body <IPaths1Kd2XrlSearchMicrosoftGraphQueryPostRequestbodyContentApplicationJsonSchema>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Invoke action query

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: QueryExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Body
.
To construct, see NOTES section for BODY properties and create a hash table.

```yaml
Type: IPaths1Kd2XrlSearchMicrosoftGraphQueryPostRequestbodyContentApplicationJsonSchema
Parameter Sets: Query
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Requests
.
To construct, see NOTES section for REQUESTS properties and create a hash table.

```yaml
Type: IMicrosoftGraphSearchRequest[]
Parameter Sets: QueryExpanded
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

### Microsoft.Graph.PowerShell.Models.IPaths1Kd2XrlSearchMicrosoftGraphQueryPostRequestbodyContentApplicationJsonSchema
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphSearchResponse
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


`BODY <IPaths1Kd2XrlSearchMicrosoftGraphQueryPostRequestbodyContentApplicationJsonSchema>`: .
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Requests <IMicrosoftGraphSearchRequest[]>]`: 
    - `[AggregationFilters <String[]>]`: 
    - `[Aggregations <IMicrosoftGraphAggregationOption[]>]`: 
      - `[BucketDefinition <IMicrosoftGraphBucketAggregationDefinition>]`: bucketAggregationDefinition
        - `[(Any) <Object>]`: This indicates any property can be added to this object.
        - `[IsDescending <Boolean?>]`: True to specify the sort order as descending. The default is false, with the sort order as ascending. Optional.
        - `[MinimumCount <Int32?>]`: The minimum number of items that should be present in the aggregation to be returned in a bucket. Optional.
        - `[PrefixFilter <String>]`: A filter to define a matching criteria. The key should start with the specified prefix to be returned in the response. Optional.
        - `[Ranges <IMicrosoftGraphBucketAggregationRange[]>]`: Specifies the manual ranges to compute the aggregations. This is only valid for non-string refiners of date or numeric type. Optional.
          - `[From <String>]`: Defines the lower bound from which to compute the aggregation. This can be a numeric value or a string representation of a date using the YYYY-MM-DDTHH:mm:ss.sssZ format. Required.
          - `[To <String>]`: Defines the upper bound up to which to compute the aggregation. This can be a numeric value or a string representation of a date using the YYYY-MM-DDTHH:mm:ss.sssZ format. Required.
        - `[SortBy <String>]`: bucketAggregationSortProperty
      - `[Field <String>]`: Computes aggregation on the field while the field exists in current entity type. Required.
      - `[Size <Int32?>]`: The number of searchBucket resources to be returned. This is not required when the range is provided manually in the search request. Optional.
    - `[CollapseProperties <IMicrosoftGraphCollapseProperty[]>]`: 
      - `[Fields <String[]>]`: Defines the collapse group to trim results. The properties in this collection must be sortable/refinable properties. Required.
      - `[Limit <Int32?>]`: Defines a maximum limit count for this field. This numeric value must be a positive integer. Required.
    - `[ContentSources <String[]>]`: 
    - `[EnableTopResults <Boolean?>]`: 
    - `[EntityTypes <String[]>]`: 
    - `[Fields <String[]>]`: 
    - `[From <Int32?>]`: 
    - `[Query <IMicrosoftGraphSearchQuery>]`: searchQuery
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[QueryString <String>]`: The search query containing the search terms. Required.
      - `[QueryTemplate <String>]`: Provides a way to decorate the query string. Supports both KQL and query variables. Optional.
    - `[QueryAlterationOptions <IMicrosoftGraphSearchAlterationOptions>]`: searchAlterationOptions
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[EnableModification <Boolean?>]`: Indicates whether spelling modifications are enabled. If enabled, the user will get the search results for the corrected query in case of no results for the original query with typos. The response will also include the spelling modification information in the queryAlterationResponse property. Optional.
      - `[EnableSuggestion <Boolean?>]`: Indicates whether spelling suggestions are enabled. If enabled, the user will get the search results for the original search query and suggestions for spelling correction in the queryAlterationResponse property of the response for the typos in the query. Optional.
    - `[Region <String>]`: 
    - `[ResultTemplateOptions <IMicrosoftGraphResultTemplateOption>]`: resultTemplateOption
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[EnableResultTemplate <Boolean?>]`: Indicates whether search display layouts are enabled. If enabled, the user will get the result template to render the search results content in the resultTemplates property of the response. The result template is based on Adaptive Cards. Optional.
    - `[SharePointOneDriveOptions <IMicrosoftGraphSharePointOneDriveOptions>]`: sharePointOneDriveOptions
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[IncludeContent <String>]`: searchContent
    - `[Size <Int32?>]`: 
    - `[SortProperties <IMicrosoftGraphSortProperty[]>]`: 
      - `[IsDescending <Boolean?>]`: True if the sort order is descending. Default is false, with the sort order as ascending. Optional.
      - `[Name <String>]`: The name of the property to sort on. Required.

`REQUESTS <IMicrosoftGraphSearchRequest[]>`: .
  - `[AggregationFilters <String[]>]`: 
  - `[Aggregations <IMicrosoftGraphAggregationOption[]>]`: 
    - `[BucketDefinition <IMicrosoftGraphBucketAggregationDefinition>]`: bucketAggregationDefinition
      - `[(Any) <Object>]`: This indicates any property can be added to this object.
      - `[IsDescending <Boolean?>]`: True to specify the sort order as descending. The default is false, with the sort order as ascending. Optional.
      - `[MinimumCount <Int32?>]`: The minimum number of items that should be present in the aggregation to be returned in a bucket. Optional.
      - `[PrefixFilter <String>]`: A filter to define a matching criteria. The key should start with the specified prefix to be returned in the response. Optional.
      - `[Ranges <IMicrosoftGraphBucketAggregationRange[]>]`: Specifies the manual ranges to compute the aggregations. This is only valid for non-string refiners of date or numeric type. Optional.
        - `[From <String>]`: Defines the lower bound from which to compute the aggregation. This can be a numeric value or a string representation of a date using the YYYY-MM-DDTHH:mm:ss.sssZ format. Required.
        - `[To <String>]`: Defines the upper bound up to which to compute the aggregation. This can be a numeric value or a string representation of a date using the YYYY-MM-DDTHH:mm:ss.sssZ format. Required.
      - `[SortBy <String>]`: bucketAggregationSortProperty
    - `[Field <String>]`: Computes aggregation on the field while the field exists in current entity type. Required.
    - `[Size <Int32?>]`: The number of searchBucket resources to be returned. This is not required when the range is provided manually in the search request. Optional.
  - `[CollapseProperties <IMicrosoftGraphCollapseProperty[]>]`: 
    - `[Fields <String[]>]`: Defines the collapse group to trim results. The properties in this collection must be sortable/refinable properties. Required.
    - `[Limit <Int32?>]`: Defines a maximum limit count for this field. This numeric value must be a positive integer. Required.
  - `[ContentSources <String[]>]`: 
  - `[EnableTopResults <Boolean?>]`: 
  - `[EntityTypes <String[]>]`: 
  - `[Fields <String[]>]`: 
  - `[From <Int32?>]`: 
  - `[Query <IMicrosoftGraphSearchQuery>]`: searchQuery
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[QueryString <String>]`: The search query containing the search terms. Required.
    - `[QueryTemplate <String>]`: Provides a way to decorate the query string. Supports both KQL and query variables. Optional.
  - `[QueryAlterationOptions <IMicrosoftGraphSearchAlterationOptions>]`: searchAlterationOptions
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[EnableModification <Boolean?>]`: Indicates whether spelling modifications are enabled. If enabled, the user will get the search results for the corrected query in case of no results for the original query with typos. The response will also include the spelling modification information in the queryAlterationResponse property. Optional.
    - `[EnableSuggestion <Boolean?>]`: Indicates whether spelling suggestions are enabled. If enabled, the user will get the search results for the original search query and suggestions for spelling correction in the queryAlterationResponse property of the response for the typos in the query. Optional.
  - `[Region <String>]`: 
  - `[ResultTemplateOptions <IMicrosoftGraphResultTemplateOption>]`: resultTemplateOption
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[EnableResultTemplate <Boolean?>]`: Indicates whether search display layouts are enabled. If enabled, the user will get the result template to render the search results content in the resultTemplates property of the response. The result template is based on Adaptive Cards. Optional.
  - `[SharePointOneDriveOptions <IMicrosoftGraphSharePointOneDriveOptions>]`: sharePointOneDriveOptions
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[IncludeContent <String>]`: searchContent
  - `[Size <Int32?>]`: 
  - `[SortProperties <IMicrosoftGraphSortProperty[]>]`: 
    - `[IsDescending <Boolean?>]`: True if the sort order is descending. Default is false, with the sort order as ascending. Optional.
    - `[Name <String>]`: The name of the property to sort on. Required.

## RELATED LINKS
[Invoke-MgBetaQuerySearch](/powershell/module/Microsoft.Graph.Beta.Search/Invoke-MgBetaQuerySearch?view=graph-powershell-beta)

