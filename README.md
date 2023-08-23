
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


![image](https://github.com/Jess20A/post-install-config/assets/142112890/6596a293-e2e1-482b-876e-988701765433)

<p>
Configure Teams by going to the Admin Panel > Agents > Teams. Teams allow you to pull Agents from different Departments and organize them to handle a specific issue or user via a Help Topic or Ticket Filter.

</p>
<br />

![image](https://github.com/Jess20A/post-install-config/assets/142112890/8a7913fe-fa1e-4dfe-a1bd-677a5ef5964e)


To configure Agents you will go to the Admin Panel > Agents > Add New. Agents are given access to the help desk with the intent to respond and resolve the tickets. When adding an Agent to the help desk, they will need to be assigned to a Primary Department and given a Primary Role for the Tickets/Tasks routed to that department. 




