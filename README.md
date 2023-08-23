
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

<h2>Post-Install Configurations</h2>

- Configure Roles
- Configure Department
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics


<h2>Configuration Steps</h2>

<p>
<


![image](https://github.com/Jess20A/post-install-config/assets/142112890/dee3379a-36bb-4106-bac4-18f98c055c6b)



</p>
<p>
Configure a role by going to the Admin Panel > Agents > Roles. You can then choose the permissions you want each role to have. 
</p>
<br />


![image](https://github.com/Jess20A/post-install-config/assets/142112890/9c93db9d-b6ea-4956-ae88-a24ddbcc8a22)

</p>
<p>
Install and enable IIS in Windows with CGI. Once in the windows features, start by checking the box for Internet Information Services. Expand World Wide Web Services followed by Application Development Features and checking the CGI and Common HTTP Features boxes. To test IIS go to a web browser and type 127.0.0.1, it should load the IIS webpage if all worked well.
</p>
<br />


![image](https://github.com/Jess20A/post-install-config/assets/142112890/2a3b83c2-c5d7-4ae2-a04e-1e8461b98529)
<p>
All of these files will have to be dowloaded in order to have OsTicket up and running correctly.

</p>
<br />

![image](https://github.com/Jess20A/post-install-config/assets/142112890/206ed688-f63b-45d2-bd4b-4edf1172e5fd)

When downloading MySQL 5.5.62 you will have to setup some credentials. Begin by choosing to do a typical setup and launch configuration wizard after the installation. Choose standard configuration and create a password for the username root.




