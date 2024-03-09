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
- Configure Departments
- Configure Teams
- Allow Anyone to Create Tickets
- Configure Agents (Workers)
- Configure Users (Customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/75OyWnD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Configure Roles and Departments:
  In the Admin Panel, navigate to the Agents section and create roles like "Supreme Admin" to define specific access levels. Additionally, set up departments such as "System Administrators" to organize tasks and responsibilities within the system.
</p>
<br />

<p>
<img src="https://i.imgur.com/vYtv4an.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 2. Configure Teams: 
  Within the Agents section, establish teams like "Level I Support" and "Level II Support" to streamline collaboration and task allocation among agents with different skill levels or areas of expertise.
</p>
<br />

<p>
<img src="https://i.imgur.com/4M7dIMe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 3. Allow Ticket Creation:
  Under the User Settings in the Admin Panel, enable the option for ticket creation without requiring registration. This allows users to submit tickets conveniently without the need to create an account.
</p>
<img src="https://i.imgur.com/LozBsgh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  4. Configure Agents and Users:
  Add agents such as "Onika" and "Steve" to handle support tickets effectively. Also, include users like "Karen" and "Ken" who will be submitting tickets and interacting with the support system.
</p>
<br />

<p>
<img src="https://i.imgur.com/OzIhw5y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  5. Set SLA:
   Define Service Level Agreements (SLA) in the Manage section to establish response time targets for different ticket priorities. For example, set response times for Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7), and Sev-C (8 hours, business hours).
</p>
<br />

<p>
<img src="https://i.imgur.com/RRznh0V_d.webp?maxwidth=760&fidelity=grand="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  6. Set Help Topics:
  Create help topics in the Manage section to categorize support tickets based on common issues or requests. Examples include "Business Critical Outage," "Password Reset," and "Software Installation."
</p>
<br />

<p>
<img src="https://i.imgur.com/JtfbCIp_d.webp?maxwidth=760&fidelity=grand" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  7. Configure Email Templates: 
  Customize email templates for notifications and responses to ensure clear communication with users and agents. Include relevant information such as ticket details, updates, and resolution instructions.
</p>
<br />

<p>
<img src="https://i.imgur.com/SSO6snX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 8. Configure Automation Rules:
  Implement automation rules in the Manage section to automate ticket routing, assignment, and escalation processes based on predefined criteria. This helps streamline workflow and ensure timely resolution of support issues.</p>
