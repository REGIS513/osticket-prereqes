<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create an Azure Virtual Machine using Windows 10 with at least 4 vCPU's
- Log into the VM with Remote Desktop
- Within the VM, download the osTicket-Installation-Files.zip
- Unzip the file onto your desktop
- Install/Enable IIS in Windows with CGI
- From the osTicket-Installation-Files folder, install PHP Manager for IIS
- Install the Rewrite Module from the osTicket-Istallation-Files folder
- Create the directory C:\PHP
- From the osTicket-Installation-Files folder, unzip PHP 7.3.8 into the C:\PHP folder
- Install VC_redist.x86.exe from the osTicket-Installation-Files folder
- Install MySQL 5.5.62 from the osTicket-Installation-Files folder
- Open IIS as an Admin
- Register PHP from within IIS
- Reload IIS (stop and start)
- Install osTicket v1.15.8
- Reload IIS (stop and start)
- Go to sites -> Default -> osTicket
- On the right, click Browse *:80
- Within IIS -> Enable php_imap.dll -> php_intl.dll -> php_opcache.dll
- Refresh the osTicket site in your browser and observe the changes

<h2>Installation Steps</h2>

<p>
<img src="https://imgur.com/a/ziM4qvn" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
