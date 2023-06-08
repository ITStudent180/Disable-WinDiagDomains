# Disable-WinDiagDomains
Description:
Powershell script to disable windows diagnostic domains. Contributions are welcomed. 

Hello Guys,
After the lack of trustworthy tools concerning Windows tracking I decided to make my own script.
The build method used was ChatGPT.
This script is meant to be simple and easy to vet. 
This script is based on microsoft documentation on domains used for 4 different types of diagnostic data.
Big and small contributions are welcomed.

Note it may trigger antimalware and will require Powershell execution permission. 
You may enable script execution using:
"Set-ExecutionPolicy -ExecutionPolicy Unrestricted"
Then disable using
"Set-ExecutionPolicy -ExecutionPolicy default"

Reference Script Execution:
https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-7.3

Reference Windows Telemetry Domains:
https://learn.microsoft.com/en-us/windows/privacy/configure-windows-diagnostic-data-in-your-organization
