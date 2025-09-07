# EdgeKiller

Fun little WIP program I whipped up to remove Microsoft Edge and keep it gone.  
Also includes a watchdog to make sure Edge doesn’t sneak back in when you’re not looking

## Features
- Removes Microsoft Edge from Windows 11
- Watchdog keeps Edge from respawning

## Requirements
- Windows 11
- PowerShell 5.1 or later

## Usage
```powershell
# Run the script
powershell.exe -ExecutionPolicy Bypass -File .\edgekiller.ps1
```
# Disclaimer

Only tested on Windows 11. I am not responsible for any damage this may cause to your system. 

This script is provided as is. Use at your own risk. It will not be updated unless Microsoft does something stupid that breaks it.
