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
<b>- Login to osTicket using the username and password you previously created.</b>

- Visit the login page at http://localhost/osTicket/scp/login.php to access osTicket.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>- The Admin Panel is where we initiate the configuration of osTicket.</b>
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>Configure roles within the Admin Panel to define user responsibilities and permissions.</b>

- In the Admin Panel, go to Agents, then Roles.
- Create a role named "SupremeAdmin," allow all permissions, and click "Add Role."
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>- Configure departments in the Admin Panel to organize and categorize support requests effectively.</b>

- Access Admin Panel, navigate to Agents, and select Departments.
- Create a department named "SystemAdministrators."
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>- Configure teams within the Admin Panel to enhance collaboration and assignment of tasks.</b>

- Access the Admin Panel, navigate to Agents, and select Teams.
Create a team named "Level II Support."
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>- Enable the option to allow anyone to create tickets in the osTicket configuration settings.</b>

- Ensure that the "Registration Required" option is unchecked in the osTicket configuration settings.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>- Configure agents in the Admin Panel to assign roles, responsibilities, and permissions to individuals handling support requests.</b>

- In the Admin Panel, navigate to Agents and click "Add New" to configure and add new agents.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>- Configure agents in the Admin Panel to assign roles, responsibilities, and permissions to individuals handling support requests.</b>

- Grant access to the newly created agent account.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>- Configure agents in the Admin Panel to assign roles, responsibilities, and permissions to individuals handling support requests.</b>

- Grant access to the newly created agent account.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>- Configure users in the Admin Panel to set up and manage customer accounts for interacting with the help desk system.</b>

- In the Agent Panel, go to Users and click "Add New."
- Switch to the Agent Panel at the top.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>- During the configuration, create a new user in the Agent Panel.</b>
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>- Define and configure SLA (Service Level Agreements) in the Admin Panel to establish response and resolution time standards for support requests.</b>

- In the Admin Panel, navigate to Manage and select SLA.
- Create the following SLA entries:
  - Sev-A: 1 hour, 24/7
  - Sev-B: 4 hours, 24/7
  - Sev-C: 8 hours, business hours.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>- Congratulations! The post-install configuration for osTicket is now complete.</b>
</p>
<br />
