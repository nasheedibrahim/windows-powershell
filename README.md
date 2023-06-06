# config for windows-powershell
### Windows Powershell
- Open Powershell as Adminstrator

- Set ExeutionPolicy to Unrestricted
```powershell
Set-ExecutionPolicy -ExecutionPolicy Unrestricted
```

- Create symlink to Documents/WindowsPowerShell folder from windows-powershell
```powershell
mklink /D WindowsPowerShell "C:\SLinks\windows-powershell"
```