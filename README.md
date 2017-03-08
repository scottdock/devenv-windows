# devenv-windows
This is my notes and scripts used to setup my development VMs for .net Core development.  Created this because I was tired of looking for text files on my other VMs. :)

# Reliminary Steps #
## Step 1 Create Virtual Machine ##
Use your VM Host of choice - Parallels, VMWare Fusion, HyperV (with Windows Pro and Enterprise)
* Install Base OS
* Run Windows Update
* Disable UAC For this, I use the following article as guidance:
https://evotec.xyz/how-to-permanently-disable-uac-in-windows-server/
* Reboot and test
* Create your user account and add it to the appropriate group
* Now, logout of administrator and use your new user account

## Step 2 Install Chocolatey ##
Ref: [example](https://chocolatey.org/install "Title")

1. Set Powershell Get-ExecutionPolicy to something other than Restricted

