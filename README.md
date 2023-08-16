<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Prerequisites</h2>

- Azure Virtual Machine
- Internet Information Services
- PHP Manager
- Rewrite Module
- PHP 7.3.8
- VC Redist x86.exe
- MySQL 5.5.62
- OsTicket v1.15.8
- HeidiSQL

<h2>Configuration Steps</h2>

<p>
<


![image](https://github.com/Jess20A/post-install-config/assets/142112890/7fb798dd-156c-4b46-8d56-afacb338c55d)


</p>
<p>
Create a Windows 10 Virtual Machine using Azure and afterwards connect to it by using Remote Desktop. Copy your public IP Address and type your password to connect. 
</p>
<br />


![image](https://github.com/Jess20A/post-install-config/assets/142112890/9c93db9d-b6ea-4956-ae88-a24ddbcc8a22)

</p>
<p>
Install and enable IIS in Windows with CGI. Once in the windows features, start by checking the box for Internet Information Services. Expand World Wide Web Services followed by Application Development Features and checking the CGI and Common HTTP Features boxes. To test IIS go to a web browser and type 127.0.0.1, it should load the IIS webpage if all worked well.
</p>
<br />

![image](https://github.com/Jess20A/post-install-config/assets/142112890/0c8ce590-0225-4e03-807c-a03a4c40dfdf)

![image](https://github.com/Jess20A/post-install-config/assets/142112890/0d0a90b2-3133-4734-8c2b-e6c32ae5663c)


<p>
Download and install PHP Manager for IIS as well as the Rewrite Module.
</p>
<br />
