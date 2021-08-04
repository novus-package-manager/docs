---
sidebar_position: 1
---

# Installation

Novus is extremely easy to install.

This can be done using the official installer or via powershell.

## Powershell Installation

You can install Novus using the powershell command.

First, you must set the PowerShell Execution Policy from Restricted to RemoteSigned or Unrestricted to allow local PowerShell scripts to run.

```powershell
Set-ExecutionPolicy RemoteSigned
```

You can then run this command on your powershell window to install Novus

```powershell
iwr -useb https://storage.googleapis.com/novus_bucket/api/powershell_install.ps1 | iex
```

## Official Installer

Download the official installer for novus [here](https://github.com/novus-package-manager/novus/releases/download/v1.0.0/Novus.v1.0.0.Setup.exe).

Check out the [Github Page](https://github.com/novus-package-manager/novus/releases) for more releases.

After downloading the installer, follow the simple installation prompts to setup Novus.

Open a terminal and type `novus` to ensure that it has installed.

Take a look at the list of commands by running `novus list`.