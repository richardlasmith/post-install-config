<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments 
- Configure Teams 
- Allow users to create Tickets 
- Configure Users 
- Configure SLAs

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/LbkyVXo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To Configure Roles. We will add a "Supreme Admin role" someone who can do everything. Go to Admin Panel/Agents/Roles/Add New Roles. Roles are the permissions granted to Agents per Department that they have access to. 
</p>
<br />

<p>
<img src="https://i.imgur.com/qI5qHDW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configuring Departments, We will use "System Administrators". Go to Admin Panel/Agents/Departments/Add New Department/ Name: "System Administrators". Tickets coming in are routed through departments in the help desk, there are many settings that can be set for departments. 
</p>
<br />

<p>
<img src="https://i.imgur.com/foPdD3L.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Teams allows you to pull agents from different Departments and organize them to handle a specific issue or user via a Help Topic or Ticket Filter. To Configure Team, 
</p>
<br />

<p>
<img src="https://i.imgur.com/Uz29kQo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure to allow anyone to create tickets. Admin Panel/ Settings/ Users Settings/ Makes sure "Require registration and login to create tickets is unchecked".
</p>
<br />

<p>
<img src="https://i.imgur.com/FNZHE1o.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Agents are help desk employees with access to respond to resolve incoming tikcet request. To configure Agent, Go to Admin Panel/Agent/Add New/ Use example Jane Doe. Save Username and set passowrd. 
</p>
<br />

<p>
<img src="https://i.imgur.com/ki1ozFP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Users are the front end customers. They can now create an account and log-in to create a ticket or check a ticket's status. Go to AGENT Panel/ Users / Add New. Use ex. Karen 
</p>
<br />

<p>
<img src="https://i.imgur.com/qknTVZN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
SLA Plans (Service Level Agreements, are to provide a length of time in which a help desk professional expects tickets to be closed. Go to Admin Panel/ Manage / SLA Plans. Click on the top right of the table to "Add New SLA Plan". Create Sev-A (1 Hour,24/7), Sev-B (4-Hour,24/7), Sev-C (8-Hour, Business Hours)
</p>
<br />

<p>
<img src="https://i.imgur.com/zxlqcON.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Help Topics by going to Admin Panel/ Manage / Help Topics/ Add New Help Topic. Create Business Critical Outage, Personal Computer Issues, Equipment Request, Passowrd Reset. 
</p>
<br />
