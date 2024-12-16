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

1. Create an Azure Virtual Machine using Windows 10 with at least 4 vCPU's
2. Log into the VM with Remote Desktop
3. Within the VM, download the osTicket-Installation-Files.zip
4. Unzip the file onto your desktop
5. Install/Enable IIS in Windows with CGI
6. From the osTicket-Installation-Files folder, install PHP Manager for IIS
7. Install the Rewrite Module from the osTicket-Istallation-Files folder
8. Create the directory C:\PHP
9. From the osTicket-Installation-Files folder, unzip PHP 7.3.8 into the C:\PHP folder
10. Install VC_redist.x86.exe from the osTicket-Installation-Files folder
11. Install MySQL 5.5.62 from the osTicket-Installation-Files folder
12. Open IIS as an Admin
13. Register PHP from within IIS
14. Reload IIS (stop and start)
15. Install osTicket v1.15.8
16. Reload IIS (stop and start)
17. Go to sites -> Default -> osTicket
18. On the right, click Browse *:80
19. Within IIS -> Enable php_imap.dll -> php_intl.dll -> php_opcache.dll
20. Refresh the osTicket site in your browser and observe the changes

<h2>Installation Steps</h2>

<p>
 <img src="https://i.imgur.com/GeuAhdx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In order to install osTicket, first we need to make a VM (Virtual Machine) using Microsoft Azure. Go to https://portal.azure.com/#home then select Virtual Machines and create a new Azure Virtual Machine named osTicket-vm.
</p>
<br />

<p>
<img src="https://i.imgur.com/nIovfk5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once your VM is created, you will be able to see the public IP adress. Go ahead and copy that IP adress, once copied, open Remote Desktop Connection and paste the IP adress that you just copied. Once connected to the Virtual Machine you will be prompt with a user login. This was created when you made the VM, plug in your username and password and click connect. Now you will be installing osTicket on the Virtual Machine.
</p>
<br />

<p>
<img src="https://i.imgur.com/dI2nzb0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Within the VM (osticket-vm), download the osTicket-Installation-Files.zip and unzip it onto your desktop. The folder should be called “osTicket-Installation-Files” We will use the files in this folder to install osTicket and some of the dependencies. From here we will be doing steps 4-20 as you can see above.

</p>
<br />
