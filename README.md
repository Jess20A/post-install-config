
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


![image](https://github.com/Jess20A/post-install-config/assets/142112890/c8567f7c-69ec-4c22-8e8c-67ecff639be5)



</p>
<p>
Configure a role by going to the Admin Panel > Agents > Roles. You can then choose the permissions you want each role to have in regards to tickets and tasks. 
</p>
<br />


![image](https://github.com/Jess20A/post-install-config/assets/142112890/7ca84656-ec36-4658-9c73-8bad58a87457)



</p>
<p>
To configure departments go to the Admin Panel > Agents > Departments. Since tickets are routed through Departments in the help desk, there are many settings that can be set for each Department.
</p>
<br />


![image](https://github.com/Jess20A/post-install-config/assets/142112890/2a3b83c2-c5d7-4ae2-a04e-1e8461b98529)
<p>
All of these files will have to be dowloaded in order to have OsTicket up and running correctly.

</p>
<br />

![image](https://github.com/Jess20A/post-install-config/assets/142112890/206ed688-f63b-45d2-bd4b-4edf1172e5fd)

When downloading MySQL 5.5.62 you will have to setup some credentials. Begin by choosing to do a typical setup and launch configuration wizard after the installation. Choose standard configuration and create a password for the username root.




