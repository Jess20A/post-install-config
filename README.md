
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This overview outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

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


<img width="309" alt="image" src="https://github.com/Jess20A/post-install-config/assets/142112890/662e3066-f8b6-4dca-a48a-fc79293c07fb">



</p>
<p>
Configure a role by going to the Admin Panel > Agents > Roles. You can then choose the permissions you want each role to have in regards to tickets and tasks. 
</p>
<br />


<img width="304" alt="image" src="https://github.com/Jess20A/post-install-config/assets/142112890/e4735325-aed2-46fd-9509-3355a5eb2dd1">



</p>
<p>
To configure departments go to the Admin Panel > Agents > Departments. Since tickets are routed through Departments in the help desk, there are many settings that can be set for each Department.
</p>
<br />


<img width="308" alt="image" src="https://github.com/Jess20A/post-install-config/assets/142112890/f0dcf03c-3017-430b-aa01-906b199815ea">


<p>
Configure Teams by going to the Admin Panel > Agents > Teams. Teams allow you to pull Agents from different Departments and organize them to handle a specific issue or user via a Help Topic or Ticket Filter.

</p>
<br />

<img width="328" alt="image" src="https://github.com/Jess20A/post-install-config/assets/142112890/fcafbcce-56b4-4ec1-914b-8ac5c8d20256">



To configure Agents (workers) you will go to the Admin Panel > Agents > Add New. Agents are given access to the help desk with the intent to respond and resolve the tickets. When adding an Agent to the help desk, they will need to be assigned to a Primary Department and given a Primary Role for the Tickets/Tasks routed to that department. 


<img width="329" alt="image" src="https://github.com/Jess20A/post-install-config/assets/142112890/d1d34a02-847f-493b-a65d-d152459df3f9">

When configuring Users (customers) begin by going to the Agent Panel > Users > Add New. Users are the ticket owners of the tickets in the help desk. When a ticket is created in the help desk, the user is associated with their email address in the User Directory of the help desk.  


<img width="293" alt="image" src="https://github.com/Jess20A/post-install-config/assets/142112890/6f45f639-522b-4ecd-95f4-de70714ec028">

To configure SLA (Service Level Agreements) start by going to the Admin Panel > Manage > SLA. For example you can have Sev-A (1hr, 24/7), Sev-B (4hrs, 24/7) and Sev-C (8hrs, business hrs). The purpose of the SLA Plan is to provide a length of time in which the help desk Administrator expects tickets to be closed.

<img width="308" alt="image" src="https://github.com/Jess20A/post-install-config/assets/142112890/43bc7635-c19c-463b-a806-8ff580b20d4e">

To configure Help Topics go to the Admin Panel > Manage > Help Topics. Examples of these can be business critical outage, personal computer issues, equipment request, etc.  Help Topics will help streamline your end-user's help desk experience to ensure proper assignment and prompt response to the ticket. 
