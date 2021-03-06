---
applicable: SharePoint Online
external help file: PnP.PowerShell.dll-Help.xml
Module Name: PnP.PowerShell
online version: https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpplannertask
schema: 2.0.0
title: remove-pnpplannertask
---

# Remove-PnPPlannerTask

## SYNOPSIS
Removes a Planner task

## SYNTAX

```powershell
Remove-PnPPlannerTask -Task <PlannerTaskPipeBind>  [<CommonParameters>]
```

## DESCRIPTION
This cmdlet removes a specific Planner task.

## EXAMPLES

### Example 1
```powershell
Remove-PnPPlannerTask -Task _LIqnL4lZUqurT71i2-iY5YALFLk
```

Removes the task with the specified id.

## PARAMETERS

### -Task
Specify the id or Task object to delete.

```yaml
Type: PlannerTaskPipeBind
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## RELATED LINKS

[Microsoft 365 Patterns and Practices](https://aka.ms/m365pnp)