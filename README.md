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
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configure Roles</h2>

 - Admin Panel -> Agents -> Roles
 - Supreme Admin
 - Assign permissions to Role

<p>
<img src="https://i.imgur.com/5ibiCX4.png" height="80%" width="80%"/>
</p>

<br />

<h2>Configure Departments</h2>

 - Admin Panel -> Agents -> Departments
 - System Administrators

<p>
<img src="https://i.imgur.com/6NhFvEn.png" height="80%" width="80%"/>
</p>

<br />

<h2>Configure Teams</h2>

 - Admin Panel -> Agents -> Teams
   - Level I Support
   - Level II Support

<p>
<img src="https://i.imgur.com/5esbZce.png" height="80%" width="80%"/>
</p>

<br />

<h2>Allow anyone to create tickets</h2>

 - Admin Panel -> Settings -> User Settings
 - Registration Required: Require registration and login to create tickets 

<p>
<img src="https://i.imgur.com/w5VRbkp.png" height="80%" width="80%"/>
</p>

<br />

<h2>Configure Agents (workers)</h2>

 - Admin Panel -> Agents -> Add New
   - Jane
     - ***Optional - Assign access, permissions and teams***
   - John
     - ***Optional - Assign access, permissions and teams***

<p>
<img src="https://i.imgur.com/70zxPrE.png" height="80%" width="80%"/>
</p>

<br />

<h2>Configure Users (customers)</h2>

 - Agent Panel -> Users -> Add New
   - Karen
   - Ken
   
<p>
<img src="https://i.imgur.com/wmLmZB5.png" height="80%" width="80%"/>
</p>

<br />

<h2>Configure SLA</h2>

 - Admin Panel -> Manage -> SLA
   - Sev-A (1 hour, 24/7)
   - Sev-B (4 hours, 24/7)
   - Sev-C (8 hours, business hours)

<p>
<img src="https://i.imgur.com/cJkZ0Xz.png" height="80%" width="80%"/>
</p>

<br />
