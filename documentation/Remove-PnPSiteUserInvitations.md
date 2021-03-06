---
applicable: SharePoint Online
external help file: PnP.PowerShell.dll-Help.xml
Module Name: PnP.PowerShell
online version: https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpsiteuserinvitations
schema: 2.0.0
title: Remove-PnPSiteUserInvitations
---

# Remove-PnPSiteUserInvitations

## SYNOPSIS

**Required Permissions**

* SharePoint: Access to the SharePoint Tenant Administration site

Searches against all stored sharing links and removes an email invite.

## SYNTAX

```powershell
Remove-PnPSiteUserInvitations [[-Site] <SitePipeBind>] [-EmailAddress] <string>
   [<CommonParameters>]
```

## DESCRIPTION
Searches against all stored sharing links on a Site and removes an email invits. If the site parameter is omitted the current site will be searched.

## EXAMPLES

### EXAMPLE 1
```powershell
Remove-PnPiteUserInvitations -Site "https://contoso.sharepoint.com/sites/ContosoWeb1/" -EmailAddress someone@example.com
```

This example removes the email invite stored in the ContosoWeb1 site for the user with email address someone@example.com.

## PARAMETERS

### -Site
Specifies the URL of the site collection.

```yaml
Type: SitePipeBind
Parameter Sets: (All)

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EmailAddress
Email Address of the user.

```yaml
Type: String
Parameter Sets: (All)

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

## RELATED LINKS

[Microsoft 365 Patterns and Practices](https://aka.ms/m365pnp)