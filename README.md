# config for windows-powershell
### Windows Powershell
- Open Powershell as Adminstrator

- Set ExeutionPolicy to Unrestricted
`Set-ExecutionPolicy -ExecutionPolicy Unrestricted`

- Create symlink to Documents/WindowsPowerShell folder from windows-powershell
`mklink /D WindowsPowerShell "C:\SLinks\windows-powershell"`