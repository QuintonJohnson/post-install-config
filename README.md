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

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Teams
- Configure Departments
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Roles
  
Admin Panel -> Agents -> Roles
  
Supreme Admin
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Departments
  
Admin Panel -> Agents -> Departments

System Administrators

Configure Teams

Admin Panel -> Agents -> Teams

Level I Support

Level II Support
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Allow anyone to create tickets
  
Admin Panel -> Settings -> User Settings

Registration Required: Require registration and login to create tickets 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Agents (workers)
  
Admin Panel -> Agents -> Add New

Jane

John

Configure Users (customers)

Agent Panel -> Users -> Add New

Karen

Ken
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure SLA
  
Admin Panel -> Manage -> SLA

Sev-A (1 hour, 24/7)

Sev-B (4 hours, 24/7)

Sev-C (8 hours, business hours)
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Help Topics
  
Admin Panel -> Manage -> Help Topics

Business Critical Outage

Personal Computer Issues

Equipment Request

Password Reset
</p>
<br />
