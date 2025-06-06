---
description: Use this topic to help manage Windows and Windows Server technologies with Windows PowerShell.
external help file: RemoteDesktop.psm1-help.xml
Module Name: RemoteDesktop
ms.date: 12/20/2016
online version: https://learn.microsoft.com/powershell/moduleremotedesktop/export-rdpersonalsessiondesktopassignment?view=windowsserver2016-ps&wt.mc_id=ps-gethelp
schema: 2.0.0
title: Export-RDPersonalSessionDesktopAssignment
---

# Export-RDPersonalSessionDesktopAssignment

## SYNOPSIS
Exports the current map of personal session desktops to users.

## SYNTAX

```
Export-RDPersonalSessionDesktopAssignment [-CollectionName] <String> -path <String>
 [-ConnectionBroker <String>] [<CommonParameters>]
```

## DESCRIPTION
The **Export-RDPersonalSessionDesktopAssignment** cmdlet exports the current map of personal session desktops to users.

## EXAMPLES

### 1:
```

```

## PARAMETERS

### -CollectionName
Specifies the name of a personal session desktop collection.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ConnectionBroker
Specifies the Remote Desktop Connection Broker (RD Connection Broker) server for a remote desktop deployment.
If you do not specify a value, the cmdlet uses the fully qualified domain name (FQDN) of the local computer.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -path


```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](https://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-RDPersonalSessionDesktopAssignment](./Get-RDPersonalSessionDesktopAssignment.md)

[Import-RDPersonalSessionDesktopAssignment](./Import-RDPersonalSessionDesktopAssignment.md)

[Remove-RDPersonalSessionDesktopAssignment](./Remove-RDPersonalSessionDesktopAssignment.md)

[Set-RDPersonalSessionDesktopAssignment](./Set-RDPersonalSessionDesktopAssignment.md)

