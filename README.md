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

- Get the zip folder for the OsTicket installation
- Install the files downloaded from the zip (IIs with CGI, PHP manager, Rewrite module, Heidisql etc.)
- Install OsTicket v1.15.8 from the root folder
- Enable extensions (php_imap.dll,php_intl.dll,php_opcache.dll)
- Check and make sure there are no errors during your installation

<h2>Installation Steps</h2>
<p>
<img src="https://i.imgur.com/nqudmVZ.png">
</p>
<p>
The first and foremost important step to install osTicket is to download and unzip file that has the installations of osTicket and its supporting files.
</p>
<br />




<p>
<img src="https://i.imgur.com/sS0zU0i.png">
</p>
<p>
The installation files have now been unzipped from the folder so now you can go through and install the files except for the osTicket.
</p>
<br />

<p>
<img src="https://i.imgur.com/VSMK65L.png">
</p>
<p>
The osTicket is now ready to install from the root folder after installing the supporting files.
</p>
<br />


<p>
<img src="https://i.imgur.com/eNrzL05.png">
</p>
<p>
osTicket is now running and functioning but some extensions were not enabled, so going into php extensions to enable php_imap.dll,php_intl.dll,php_opcache.dll. Now osTicket is fully ready.
</p>
<br />
