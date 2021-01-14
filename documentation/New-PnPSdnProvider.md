---
applicable: SharePoint Online
external help file: PnP.PowerShell.dll-Help.xml
Module Name: PnP.PowerShell
online version: https://pnp.github.io/powershell/cmdlets/new-pnpsdnprovider
schema: 2.0.0
title: New-PnPSdnProvider
---

# New-PnPSdnProvider

## SYNOPSIS
Adds a new Software-Defined Networking (SDN) provider

## SYNTAX

```powershell
New-PnPSdnProvider -Identity <String> -License <String> [-Confirm] [-WhatIf]
```

## DESCRIPTION
This Cmdlet creates a new Software-Defined Networking, and it receives two parameters, the Identity (ID) of the Hive and the License key of the Hive.

## EXAMPLES

### EXAMPLE 1
```powershell
New-PnPSdnProvider -ID "Hive" -License ""
```

This example creates the Hive for a SDN Provider.

## PARAMETERS

### -Identity

```yaml
Type: String
Parameter Sets: (All)

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -License

```yaml
Type: String
Parameter Sets: (All)

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs. The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)

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

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

## RELATED LINKS

[Microsoft 365 Patterns and Practices](https://aka.ms/m365pnp)