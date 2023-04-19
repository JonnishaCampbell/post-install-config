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

- Roles
- Departments
- Teams
- Agents
- Users
- SLA
- Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Use the admin information to log into osTicket;if not logged in
Configure Roles
	<p> - Go to the Admin Panel -> Agents -> Roles </p>
	<p> - Create a Role called Supreme Admin </p>
Configure Departments
	<p> - Go to Admin Panel -> Agents -> Departments </p>
	<p> - Create a Department called System Administrators </p>
Configure Teams
	<p> - Go to Admin Panel -> Agents -> Teams </p>
	<p> - Create the following teams </p>
		i. Level I Support
		ii. Level II Support
	- Note: Level I Support is created by default
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Allow anyone to create tickets
<p>	- Go to Admin Panel -> Settings -> User Settings </p>
<p>	- Uncheck the Registration Required so the user doesn't have to require registration to login and create tickets </p>
	-Note: Only for lab purposes. It'll be required to register in the work field

Configure Agents
	- This is for the workers
<p>	- Go to Admin Panel -> Agents -> Add new </p>
<p>	- Create at least 2 agents: e.g. Jane Doe and John Doe </p>
Configure Users
	- This is adding customers
<p>	- Go to Admin Panel -> Users -> Add new </p>
<p>	- Create at least 2 users: e.g. Jenny Jen and Kenny Ken </p>
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure SLA
	- This is to manage tickets on the level of urgency
<p>	- Go to Admin Panel -> Manage -> SLA </p>
<p>	- Sev-A (1 hour, 24/7) </p>
<p>	- Sev-B (4 hours, 24/7) </p>
<p>	- Sev-C (8 hours, 24/7) </p>
Configure Help Topics
<p>	- Go to Admin Panel -> Manage -> Help Topics </p>
<p>	- Select the following topics for users to choose from when deciding what their issue should fall under </p>
		i. Business Critical Outage
		ii. Personal Computer Issues
		iii. Equipment Request
		iv. Password Reset
</p>
<br />
