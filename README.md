Always-On-Top-PS-Script
=======================

A PowerShell script that can be called from a batch script to give a window the always on top attribute. 

### Setup

to enable open admin powershell and run

```powershell
Set-ExecutionPolicy RemoteSigned
```

### Usage from powershell

```powershell
.\Always_On_Top.ps1 -chosenApplication "LG Smart Assistant"
```

`-chosenApplication` should match the Window Title Name

### From batch script

See `launch_colorcpl_ontop.bat` for example
