# devenv-windows
This is my notes and scripts used to setup my development VMs for .net Core development.  Created this because I was tired of looking for text files on my other VMs. :)

# Preliminary Steps #
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
Chocolatey is a free command-line package manager for Windows.  [Reference](https://chocolatey.org/install "Title")

1. Set Powershell Get-ExecutionPolicy to something other than Restricted
2. Use this web page to obtain the necessary installation steps - https://chocolatey.org/install

## Step 3 Install Utilities & Apps via Chocolatey.org ##
* Use  [this page](https://chocolatey.org/packages "Title") to find your utilities of choice
* Then create your own version of the DevEnv.bat file located in this repo to install your preferred apps

## Step 4 Install Microsoft Software ## 
My general rule of thumb has always been to install the Microsoft Servers/Tools from oldest to newest. 
For example - If you want SQL Server Developer Edition - I would install it first before VS 2017.
