---
external help file: Builtin-help.xml
Module Name: Builtin
online version: 
schema: 2.0.0
---

# Deny-PendingCommand

## SYNOPSIS
Deny the approval of a pending command.

## SYNTAX

```
Deny-PendingCommand -Bot <Object> [-Id] <String>
```

## DESCRIPTION
{{Fill in the Description}}

## EXAMPLES

### -------------------------- EXAMPLE 1 --------------------------
```
!deny -id f087f1fd
```

Deny the command with ID f087f1fd from being run.

## PARAMETERS

### -Bot
{{Fill Bot Description}}

```yaml
Type: Object
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
The command exeution context ID of a command awaiting approval.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS
