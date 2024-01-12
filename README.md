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
- Mac OS (User)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles, Departments, and Teams to organize and streamline ticket management.
- Set up Agents (workers) to handle support requests efficiently.
- Configure Users (customers) for seamless interaction with the help desk system.
- Establish SLA (Service Level Agreements) to define response and resolution times.
- Configure Help Topics to categorize and prioritize support issues effectively.

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>1. Login to osTicket:</b>

- Access osTicket login page: http://localhost/osTicket/scp/login.php
- Use the username and password created during installation.
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b> 2. Access Admin Panel:</b>

- Navigate to the Admin Panel after logging in. This is where the configuration starts.
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>3. Configure Roles:</b>

- Go to Admin Panel -> Agents -> Roles
- Create a role named "SupremeAdmin" with all permissions.
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>4. Configure Departments:</b>

- Go to Admin Panel -> Agents -> Departments
- Create a department named "SystemAdministrators."
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>5. Configure Teams:</b>

- Go to AdminPanel -> Agents -> Teams
- Create a team named "Level II Support."
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>6. Allow Ticket Creation:</b>
  
- Ensure that "Registration Required" is not checked in Admin Panel -> Settings -> User Settings.
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>7. Configure Agents:</b>

- Go to AdminPanel -> Agents -> Add New
- Create agents with usernames and passwords, allowing access.
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>8. Configure Users:</b>

- Switch to the Agent Panel.
- Go to Agent Panel -> Users -> Add New
- Create new users.
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>9. Configure SLA:</b>

- Go to AdminPanel -> Manage -> SLA
- Define SLA levels:
  - Sev-A (1 hour, 24/7)
  - Sev-B (4 hours, 24/7)
  - Sev-C (8 hours, business hours)
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>10. Configure Help Topics:</b>

- Go to AdminPanel -> Manage -> HelpTopics
- Create help topics:
  - Business Critical Outage
  - Personal Computer Issues
  - Equipment Request
  - Password Reset
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>11. Conclusion:</b>

- The above steps conclude the post-install configuration of osTicket.
</p>
<br />
