<h1> Custom PowerShell Script for Wiping USB Drives</h1>

This is a step by step tutorial for wipping your USB drivers using a PowerShell Script.

<h1>Applacations and Operating System Used</h1>

- PowerShell
- Windows 11

<h1>Steps</h1>

To create a custom PowerShell script for wiping USB drives, you can follow these steps:

1.   Open Windows PowerShell ISE or any text editor of your choice.

2.  Create a new PowerShell script file and save it with a .ps1 extension.

3.  Use the following code to create a function that will wipe the USB drive:

  <p align="center">
  <img src="https://i.imgur.com/yS99fca.png" alt="CopyCode"/>
  
4.  The above code contains a function called "Wipe-USBDrive" that takes a "DrivePath" parameter, which specifies the path of the USB drive to wipe. The function uses WMI (Windows Management Instrumentation) to get the USB drive and then formats it with the NTFS file system, which will overwrite all the data on the drive.

5.  Save the PowerShell script file.

6.  Open PowerShell as an administrator, navigate to the directory where you saved the PowerShell script file and run the following command:

 <img src="https://i.imgur.com/aBNBuQg.png" alt="CopyCode"/>
The command allows your computer the execute scripts


7.To wipe a USB drive using the custom PowerShell script, run the following command:

 <img src="https://i.imgur.com/ofpz1FS.png" alt="CopyCode"/>
  
Replace "E:" with the actual drive letter of your USB drive.

Note: Be very careful when wiping USB drives, as this action cannot be undone. Make sure you have backed up any important data before running the script.

<h1> Custom PowerShell Script for Wiping USB Drives END</h1>
