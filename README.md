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

- Install IIS in windows <Config IIS>
- Install PHP manager for IIS
- Install mySQL
- Open IIS as an Admin
- Setup OsTicket in the browser

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/rumjMZo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After I set up the Virtual Machine VM for osTicket withnin a Resource Group in Azure, then login to remote desktop with the IP address of the VM created. The installation of IIS (Internet Information services) in windows is to configure IIS through the control panel, enable IIS CGI and common HTTP features 
for IIS to be effective. I checked to confirmed the update with 127.0.0.1
</p>
<br />

<p>
<img src="https://i.imgur.com/EACcvUc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here, I proceed with the installation of PHP manager for IIS, installed Rewrite module, installed VC_redist for a proper functioning of IIS. 
The PHP manager helps to manage one or many PHP installation. After the installation, I checked and confirmed it is well configured and IIS works perfectly..
</p>
<br />

<p>
<img src="https://i.imgur.com/jgtbNhR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I downloaded MySQL and did a typical setup, launched configuration wizzard after the installation. Then click on standard confirguration and setup a random username and
password to setup. Installation of MySQL is important beacause it is a reliable, fast and easy for database management. It is easy to modify, secure and organise the database. 
</p>
<br />

<p>
<img src="https://i.imgur.com/YuDPMni.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/3TS724J.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To open IIS as an admin, I downloaded and installed osTicket and also registered PHP from within IIS. Osticket installer provides access to 
route inquires created via email, web-forms and clients/cutomers support. Afeterwards, I enabled some section to enable effective work, refreshed osTicket to update changes.
</p>
<br />

<p>
<img src="https://i.imgur.com/MLtkxnN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I created a new database, osTicket Vicky Help desk, set a random username and password. 
Browse through the vicky help desk and I created the osTicket. After the setup was successful, I end users osTicket URL, clean up by deleting the osTicket, set the permission to "Read only" and refresh</p>
<br />

