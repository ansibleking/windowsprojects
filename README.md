# windowsprojects
windowsprojects


 For Basic

 ansible_host: xx.xx.xx.xx
 Set-Item -Path WSMan:\localhost\Service\Auth\Basic -Value $true
 winrm set winrm/config/service '@{AllowUnencrypted="true"}'
