# Windows 11 Install 

## Pre-installation Steps
* Download one of the VMs from the links provided above
* Import the .ovf if necessary
* Disable Windows Defender 
    - Open **Windows Security App**
    - Click on **Virus and Threat Protection**
    - Click on **Virus and Threat Protection Settings** 
        - Disable real-time protection
        - Disable cloud-delivered protection
        - Disable automatic sample submission
    - Click on **Controlled Folder Access** 
        - Add the directory C:\ to the exclusion list

### Take a snapshot of your machine!

## Installations Steps

* Download and copy install.ps1 onto your new VM
* Open PowerShell as an Administrator
    - Unblock the install file by running:
    -   **Unblock-File .\install.ps1** 
    - Enable script execution by running:
        - Set-ExecutionPolicy Unrestricted
    - Finally, execute the installer script as follow:
        - **.\install.ps1**
    - Default Windows password: Passw0rd! 
