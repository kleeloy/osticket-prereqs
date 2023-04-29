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

- Enable Internet Information Services (IIS)
- Web Platform Install
- Install My SQL (Set Up Usernames And Passwords)
- Configure permissions and Install Osticket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/A9x4ozJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
World Wide Web Services -> Application Development Features -> [X] CGI. Checked by checking the local host, 127.0.0.1 to loot back.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Installed web platforms: PHP Manager for ISS, Rewrite module, PHP 7.3.8, VC_redist.x86.exe
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install my SQL, Typical setup, Launch configuration WIzard (after install), Standard Configuration, Setup Root Password. WHat this does is installing a database for this computer. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Back to IIS, sites -> Default -> osTicket, Double-click PHP Manager, Click “Enable or disable an extension”
Enable: php_imap.dll
Enable: php_intl.dll
Enable: php_opcache.dll
Assign Permissions: ost-cofig.php, Downloaded and installed HeidiSQL, continued setting up osticket in the browser
</p>
<br />
