---
Download Help Link: https://aka.ms/powershell72-help
Help Version: 7.2.0.0
Locale: en-US
Module Guid: 5714753b-2afd-4492-a5fd-01d9e2cff8b5
Module Name: PSReadLine
ms.date: 06/27/2022
schema: 2.0.0
title: PSReadLine
---
# PSReadLine Module

## Description

The PSReadLine module contains cmdlets that let you customize the command-line editing environment
in PowerShell.

There have been many updates to PSReadLine since the version that ships in
Windows PowerShell 5.1.

- PowerShell 7.3-preview.5 ships with PSReadLine 2.2.5
- PowerShell 7.2.5 ships with PSReadLine 2.1.0
- PowerShell 7.0.11 ships with PSReadLine 2.0.4
- PowerShell 5.1 ships with PSReadLine 2.0.0

These articles document version 2.1.0 of PSReadLine.

> [!NOTE]
> Beginning with PowerShell 7.0, PowerShell skips auto-loading PSReadLine on
> Windows if a screen reader program is detected. Currently, PSReadLine doesn't
> work well with the screen readers. The default rendering and formatting of
> PowerShell 7.0 on Windows works properly. You can manually load the module if
> necessary.

## PSReadLine Cmdlets

### [PSConsoleHostReadLine](PSConsoleHostReadLine.md)
The main entry point for PSReadLine.