<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install & Enable IIS In Windows With CGI and Common HTTP Features  
- Install PHP Manager for IIS 
- Install Rewrite Module
- Change permissions in Security
- Create "osTicket" database

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/4aWDK68.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Setting up and configuring IIS allowing osTicket to run over server. Accessing programs and features, selected "turn on windows features". Located IIS folder checked box. Expand IIS folder then expand "world wide services" open " Application Developement" to locate and enable "CGI". Check box. Once thnese action have been successfully executed, close folders and proceed to next steps. 
</p>
<br />

<p>
<img src="https://i.imgur.com/qICXeeP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Installation of PHP Manager and Rewrite module on main driver succcessful. Installation of MySQL Server  with standard config. Created root password and user then execute action. Refresh server. 
</p>
<br />

<p>
<img src="https://i.imgur.com/bTcSENG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Registered new PHP and located PHP.CGI file. Downloaded osTicket then located "upload foldeer. Opened main drive drag and drop upload fold into wwwroot folder. Rename "upload" folder to osTicket, then go back to IIS to restart server. Enable osTicket extensions PHP IMAP,  PHP INTL, and PHP Opache then refresh server again. Install Heidi SQL, Create osTicket database. Install complete.
</p>
<br />
