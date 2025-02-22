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
- Admin/Analyst Login Page: http://localhost/osTicket/scp/login.php
- End Users/Customer osTicket URL: http://localhost/osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Allow anyone to create tickets
- Configure Agents
- Configure Users / Customers
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p  align="center">
<img src="https://imgur.com/faZ8b3P.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To add and configure roles for the agents on osTicket, first make sure you are on the 'Admin' panel. To verify this, if the top right has a prompt to select the 'Agent panel,' you are on the correct panel. Under the 'Agents' tab and under 'Roles,' select 'Add New Role.'
</p>
<br />

<p  align="center">
<img src="https://imgur.com/RHl81XW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here, you can name a role. I named this role 'Supreme Admin.'
</p>
<br />

<p  align="center">
<img src="https://imgur.com/Q5aq9Pw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is how you can configure the permissions. For the 'Supreme Admin' role, I like to enable all
</p>
<br />

<p  align="center">
<img src="https://imgur.com/jyHttDB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Navigate to 'Departments' under the same 'Agents' tab, and select 'Add New Department' to add a new department
</p>
<br />

<p  align="center">
<img src="https://imgur.com/nXVMSSW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is how you name and configure a new department. I named this one 'SysAdmins' for the system administrators
</p>
<br />

<p  align="center">
<img src="https://imgur.com/41yyJeP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
If you tab over to the 'Access' screen, you can select which agents/employees are within this department.
</p>
<br />

<p align="center">
<img src="https://imgur.com/kV8X1bt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Return to the 'Agents' tab, and select 'Teams.' From here, you can add and configure 'Teams.' Teams are basically how you can connect agents/employees to other departments. For example, you may have cashiers and custodians in their own respective departments but under Teams, this is how you can delegate the responsibilities to not overwhelm every agent/employee and as well, who to escalate to, who's responsible, and this keeps things organized. There may be multiple System administrators and sometimes a company might change the responsibilites for each agent so Teams is a pretty handy tool.
</p>
<br />

<p align="center">
<img src="https://imgur.com/Qc9jzb4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here, you can see I am creating a team for Online Banking. 
</p>
<br />

<p align="center">
<img src="https://imgur.com/nozRM7Y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
On this window, you can select the agents who belong in this Team
</p>
<br />

<p align="center">
<img src="https://imgur.com/wbzdJyb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Navigate to the 'Settings' tab, then 'Users.' On this screen, 'Registration Required' decides whether people have to register in order to create a ticket. This is more so based on a company's desire for convenience for a client and completely optional.
</p>
<br />

<p align="center">
<img src="https://imgur.com/emnyOQx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
You can navigate to the 'Agents' tab and on the 'Agents' tab within the other, you can create a new agent and configure pre-existing ones.
</p>
<br />

<p align="center">
<img src="https://imgur.com/wdleYl5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is the first menu in the agent configuration. This sets up the basic information for an agent/employee within the company's osTicket database. 
</p>
<br />

<p align="center">
<img src="https://imgur.com/AkVVjUB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The next page allows you to choose the agent's department and role.
</p>
<br />

<p align="center">
<img src="https://imgur.com/91oEi4I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, is where you set up the permissions
</p>
<br />

<p align="center">
<img src="https://imgur.com/xrAH1Kq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Finally, this is where you set the Team
</p>
<br />

<p align="center">
<img src="https://imgur.com/ZA85vuj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to the 'Manage' tab, 'SLA,' then 'Add New SLA Plan.' 
</p>
<br />

<p align="center">
<img src="https://imgur.com/LzHmBqv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
SLA (Service Level Agreement) is a pretty linear term. This defines the service, level of this service that is defined by the priority or urgency, and agreement is where both the client/customer and agent/employee agree on these terms. Companies typically get the same issues, so creating SLAs save time for the agent/employee in configuring this agreement.  You can set the 'Grace Period' which on this page, is defined as the duration until this particular service agreement is marked overdue once it is initiated.
</p>
<br />

<p align="center">
<img src="https://imgur.com/CbUoHOi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Setting the Schedule sets the time window for when the hours within a Grace Period are counted
</p>
<br />

<p align="center">
<img src="https://imgur.com/029X8jw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
These are how SLAs are generally configured. Sev-A is the highest priority, while Sev-C has the least priority, The Grace Period reflects the level of urgency
</p>
<br />

<p align="center">
<img src="https://imgur.com/xFHRjYg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
You can navigate to the 'Help Topics' tab under 'Manage' to add a new help topic. This is what that window looks like. If you select a parent topic, this will be shown as a sub-topic on the Help Topics menu. Otherwise, this will be created as a main topic for when tickets are created.
</p>
<br />

<p align="center">
<img src="https://imgur.com/X9kOwCG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
These are the basic, general help topics. You can see how each priority ranges and specifies the urgency and as well how these topics are delegated to specified departments
</p>
<br />

<p align="center">
<img src="https://imgur.com/ixjcyWA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When users create tickets (navigate to http://localhost/osTicket), they enter their contact information for notification, specify the Help Topic configured previously, and elaborate on their issue in the field prompted below.
</p>
<br />

<p align="center">
<img src="https://imgur.com/Yk0Fajf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Returning to osTicket, click 'Agent Panel' in the top right to handle tickets that are created. Under the 'Tickets' tab, you can set the priority, specify the department, choose who this will be assigned to, and select the SLA plan to define the ticket's urgency.
</p>
<br />

<p align="center">
This covers all the important intracacies on configuring osTicket post-installation. I hope you enjoyed and found this educational!
</p>
