---
applicable: SharePoint Online
external help file: PnP.PowerShell.dll-Help.xml
Module Name: PnP.PowerShell
online version: https://pnp.github.io/powershell/cmdlets/get-pnpgraphaccesstoken
schema: 2.0.0
title: Get-PnPGraphAccessToken
---

# Get-PnPGraphAccessToken

## SYNOPSIS
Returns the current OAuth Access token for the Microsoft Graph API

## SYNTAX

```powershell
Get-PnPGraphAccessToken [-Decoded] [<CommonParameters>]
```

## DESCRIPTION
Gets the OAuth 2.0 Access Token to consume the Microsoft Graph API

## EXAMPLES

### EXAMPLE 1
```powershell
Get-PnPGraphAccessToken
```

Gets the OAuth 2.0 Access Token to consume the Microsoft Graph API

### EXAMPLE 2
```powershell
Get-PnPGraphAccessToken -Decoded
```

Gets the full OAuth 2.0 Token to consume the Microsoft Graph API

## PARAMETERS

### -Decoded
Returns the access token in a decoded manner

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
