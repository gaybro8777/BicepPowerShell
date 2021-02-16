---
external help file: Bicep-help.xml
Module Name: Bicep
online version:
schema: 2.0.0
---

# Install-BicepCLI

## SYNOPSIS
Install Bicep CLI

## SYNTAX

```powershell
Install-BicepCLI [-Force] [<CommonParameters>]
```

## DESCRIPTION
Install-BicepCLI is a command to to install the latest Bicep CLI realease available from the Azure/Bicep repo.

## EXAMPLES

### Example 1: Install the latest Bicep CLI Version
```powershell
Install-BicepCLI
```

### Example 2: Install the latest Bicep CLI Version using the force switch
```powershell
Install-BicepCLI -Force
```

## PARAMETERS

### -Force
This switch will force Bicep to be installed, even if another installation is already in place.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES
Go to module repository https://github.com/StefanIvemo/BicepPowerShell for detailed info, reporting issues and to submit contributions.

## RELATED LINKS