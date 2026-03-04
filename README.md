<h1>Helpdesk Home Lab – Windows Server 2022 Installation & Virtual Environment Setup</h1>

<h2>Description</h2>
This lab documents the installation of Windows Server 2022 in a virtual environment using Oracle VirtualBox. The goal of this Lab is to create a basic help desk lab environment that will be used for future Active Directory, domain configuration, and Windows 11 client integration labs.

In this setup, the following tasks were completed:
- <b>Downloaded and installed Oracle VirtualBox (v7.1.4)</b>
- <b>Downloaded Windows Server 2022 ISO (64-bit)</b>
- <b>Downloaded Windows 11 installation media (ISO)</b>
- <b>Created a new virtual machine configured for Windows Server 2022</b>
- <b>Allocated 8GB RAM and 2 CPU cores to the virtual machine</b>
- <b>Mounted the Windows Server 2022 ISO to the virtual machine</b>
- <b>Started the virtual machine and launched the Windows Server installation</b>
- <b>Installed Windows Server 2022 (Desktop Experience)</b>
- <b>Configured the local Administrator account and password</b>
- <b>Removed the installation ISO after setup completion</b>
- <b>Adjusted time zone settings</b>
- <b>Tested shutdown and restart commands using GUI and Command Prompt</b>
- <b>Tested shutdown and restart commands using GUI and Command Prompt</b>

This project serves as the foundation for building a full help desk home lab environment.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Oracle VirtualBox (v7.1.4)</b>
- <b>Windows Server 2022 (64-bit)</b>
- <b>Windows 11 Installation Media (ISO)</b>
- <b>Command Prompt (CMD)</b>

<h2>Environments Used </h2>

- <b>Host Operating System: Windows 10 / Windows 11</b>
- <b>Virtualization Platform: Oracle VirtualBox</b>
- <b>Guest Operating System: Windows Server 2022</b>

<h2>Program walk-through:</h2>

<p align="center">
Step 1 – Download and Install Oracle VirtualBox<br/>
Navigate to the Oracle VirtualBox website and download the latest version of VirtualBox (v7.1.4). Run the installer and follow the installation wizard to install VirtualBox on your host machine: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
