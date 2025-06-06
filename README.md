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

The notice at the top indicates the VM agent isn’t fully initialized, which I noted for troubleshooting later, but it didn’t impact my ability to connect and continue setup through RDP.

This lab helped reinforce core concepts like virtual machine deployment, network configuration, and practical cloud administration in Azure — all key skills for help desk and SOC roles.
</p>
<br />

<p>
<img src="https://i.imgur.com/Mz2RBcJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This image shows where I went into the osTicket virtual machine, into the osTicket desktop folder and extracted the PHP folder from the files list so I was able to go into the PHP folder and get information that I needed.
</p>
<br />

<p>
<img src="https://i.imgur.com/Ym1HiTK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After extracting the PHP folder, I then had to go into the Internet Information Services (ISS) to register the PHP manager so I could run PHP commands.
</p>
<br />

<p>
<img src="https://i.imgur.com/X1dp2Zm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
osTicket is installed!
</p>
<br />
