# ATTENTION!! IF YOU HAVE DOCKER DESKTOP OR TOOLBOX UNINSTALL ALL BEFORE CONTINUE WITH SET UP BELOW!!
## Win 10 home,pro .... + WSL2 + Docker desktop First update win to version 2004 

and then follow the steps 
Use first – powershell admin – command (just copy paste)

dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart

Second 
 
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart

RESTART PC - manually download and install   
[Updating to wsl2 ](https://github.com/zetrocode/Panel-Web-PHP-KeyAuth-Example/releases/download/teamplate/AppLauncher-inst-win64.zip)

Open powersheel – last command  
wsl --set-default-version 2

**when all is done, install the docker at the end  with regards** bamisinic and coco195

Do not modify. Thank you.