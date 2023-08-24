
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

 Part 1 (Create Virtual Machine in Azure)
- Create a Resource Group
- Create a Windows 10 Virtual Machine (VM) with 2-4 Virtual CPUs
- Create a Virtual Network
  
  Part 2 (Installation)
- Create an Azure Virtual Machine Windows 10, 4 vCPUs
- Name: Vm-osticket
- Username: labuser (for example/whatever you chose)
- Password: osTicketPassword1! (for example/whatever you chose)


<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/eT3vecn.png " height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
<p>
 Install / Enable IIS in Windows WITH
CGI and Common HTTP Features
World Wide Web Services -> Application Development Features ->
[X] CGI
[X] Common HTTP Features
AND IIS Management Console
Internet Information Services -> Web Management Tools -> IIS Management Console
	[X] IIS Management Console


</p>
<br />

<p>
<img src="https://i.imgur.com/eT3vecn.png " height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After you install the IIS management console download and install the following
	PHP Manager for IIS which allows you to be able to run the Internet Information Services (IIS) webserver.
	Rewrite Module which is used to redirect URL request
	
<img src="https://imgur.com/a/A13ZDG1  " height="80%" width="80%" alt="Disk Sanitization Steps"/>
  Create the directory C:\PHP


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
