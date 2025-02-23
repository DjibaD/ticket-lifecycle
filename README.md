<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img src="https://i.imgur.com/x4eOo8a.jpeg" height="80%" width="80%" />
</p>
<p>
Admin/Analyst Login Page:
http://localhost/osTicket/scp/login.php 

End Users osTicket URL:
http://localhost/osTicket 

In this lab, we will be creating tickets as end users
Observing all the ticket properties and responding to them as help desk professionals

Change the SysAdmins Department to a Top Level Department
DELETE the Maintenance Department (not archive)

</p>
<br />

<p>
<img src="https://i.imgur.com/xywFjPZ.jpeg" height="80%" width="80%"/>
</p>
<p>
As an end-user, create the following ticket
entire mobile/online banking system is down

</p>
<br />

<p>
<img src="https://i.imgur.com/UQ9MqHb.jpeg" height="80%" width="80%" />
</p>
<p>
As a Help Desk Agent (john), observe the ticket’s properties
	Priority
	Department
	SLA
	Assigned To

Set Properties to the ticket
Sev-A (1 hour, 24/7)
Online Banking Department

Attempt to observe the ticket again as “john”. Can you view or change?

Work the ticket to completion as jane

</p>
<br />

<p>
<img src="https://i.imgur.com/xTrO79n.jpeg" height="80%" width="80%"/>
</p>
<p>
As an end-user, create the following ticket
accounting department needs adobe upgrade, broken

</p>
<br />

<p>
<img src="https://i.imgur.com/UQ9MqHb.jpeg" height="80%" width="80%" />
</p>
<p>
As a Help Desk Agent (john), observe the ticket’s properties
	Priority
	Department
	SLA
	Assigned To

Set Properties to the ticket
Sev-B (4 hours, 24/7)
Support

Work the ticket to completion as john


</p>
<br />
