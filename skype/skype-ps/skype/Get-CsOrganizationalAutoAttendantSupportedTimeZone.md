---
external help file: Microsoft.Rtc.Management.Hosted.dll-help.xml
online version: https://docs.microsoft.com/powershell/module/skype/get-csorganizationalautoattendantsupportedtimezone
applicable: Skype for Business Online
title: Get-CsOrganizationalAutoAttendantSupportedTimeZone
schema: 2.0.0
manager: bulenteg
author: tomkau
ms.author: tomkau
ms.reviewer:
---

# Get-CsOrganizationalAutoAttendantSupportedTimeZone

## SYNOPSIS
> [!CAUTION]
> This cmdlet has been deprecated and is no longer supported.  This cmdlet will be removed in the near future.
> 
> Please use [Get-CsAutoAttendantSupportedTimeZone](Get-CsAutoAttendantSupportedTimeZone.md) cmdlet instead.

The Get-CsOrganizationalAutoAttendantSupportedTimeZone cmdlet gets supported time zones for the Auto Attendant (AA) service.

## SYNTAX

```
Get-CsOrganizationalAutoAttendantSupportedTimeZone [-Identity] <String> [-Tenant <Guid>] [<CommonParameters>]
```

## DESCRIPTION
The Get-CsOrganizationalAutoAttendantSupportedTimeZone cmdlet gets all the time zones that the OAA service supports, or a specific time zone if its Identity is provided.

## EXAMPLES

### -------------------------- Example 1 --------------------------
```
Get-CsOrganizationalAutoAttendantSupportedTimeZone
```

This example gets all supported time zones.

### -------------------------- Example 2 --------------------------
```
Get-CsOrganizationalAutoAttendantSupportedTimeZone -Identity "Pacific Standard Time"
```

This example gets the timezone that the Identity parameter specifies (Pacific Standard Time).


## PARAMETERS

### -Identity
The Identity parameter specifies a time zone to be retrieved. If this parameter is not used, then all supported time zones are returned.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases: 
Applicable: Skype for Business Online

Required: False
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Tenant

```yaml
Type: System.Guid
Parameter Sets: (All)
Aliases: 
Applicable: Skype for Business Online

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (https://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### None


## OUTPUTS

### Microsoft.Rtc.Management.Hosted.OAA.Models.TimeZone


## NOTES


## RELATED LINKS

