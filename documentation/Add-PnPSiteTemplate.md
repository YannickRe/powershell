---
applicable: SharePoint Online
external help file: PnP.PowerShell.dll-Help.xml
Module Name: PnP.PowerShell
online version: https://pnp.github.io/powershell/cmdlets/add-pnpsitetemplate
schema: 2.0.0
title: Add-PnPSiteTemplate
---

# Add-PnPSiteTemplate

## SYNOPSIS
Adds a PnP Site Template object to a tenant template

## SYNTAX

```powershell
Add-PnPSiteTemplate -SiteTemplate <SiteTemplate> -TenantTemplate <ProvisioningHierarchy> [<CommonParameters>]
```

## DESCRIPTION

## EXAMPLES

### EXAMPLE 1
```powershell
Add-PnpSiteTemplate -TenantTemplate $tenanttemplate -SiteTemplate $sitetemplate
```

Adds an existing site template to an existing tenant template object

## PARAMETERS

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

### -SiteTemplate
The template to add to the tenant template

```yaml
Type: SiteTemplate
Parameter Sets: (All)

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -TenantTemplate
The tenant template to add the template to

```yaml
Type: ProvisioningHierarchy
Parameter Sets: (All)

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs. The cmdlet is not run.

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

## RELATED LINKS

[Microsoft 365 Patterns and Practices](https://aka.ms/m365pnp)