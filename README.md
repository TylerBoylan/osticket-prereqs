<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- osTicket Installer
- PHP Registration

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/uUjfXbj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This screenshot shows the osticket-vm I set up in Microsoft Azure as part of a lab project. The VM is running in the East US region with 2 virtual CPUs and 8 GB of RAM, It's connected to a custom virtual network with both public and private IP addresses assigned.

The purpose of this VM is to install and configure osTicket, an open-source support ticket system used to simulate real-world IT service desk environments. This step lays the groundwork for hosting the platform, testing connectivity, and applying security configurations like network security groups (NSGs).

This lab helped reinforce core concepts like virtual machine deployment, network configuration, and practical cloud administration in Azure — all key skills for help desk and SOC roles.
</p>
<br />

<p>
<img src="https://i.imgur.com/Mz2RBcJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This image shows the osTicket virtual machine after I extracted the required installation files. I navigated to the osTicket-Installation-Files folder on the desktop and unpacked the PHP installer. From there, I moved the extracted PHP files to the C:\Windows\PHP directory.

This step was essential for setting up the environment osTicket needs to run. By manually installing PHP, I was able to verify the correct version, ensure all the necessary extensions were available, and prepare for integration with IIS in the next steps of the setup.
</p>
<br />

<p>
<img src="https://i.imgur.com/Ym1HiTK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After extracting the PHP files, I opened up IIS (Internet Information Services) Manager to get PHP working with the server. Since PHP wasn’t set up by default, I used the PHP Manager tool to manually register the PHP executable by pointing it to C:\PHP\php-cgi.exe.
</p>
<br />

<p>
<img src="https://i.imgur.com/X1dp2Zm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
osTicket is installed!
</p>
<br />
