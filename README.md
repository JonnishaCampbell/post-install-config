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
Log into the account you just made
Configure Roles
<ul>
	<p> - Go to the Admin Panel -> Agents -> Roles </p>
	<p> - Create a Role called Supreme Admin </p>
	</ul>
Configure Departments
<ul>
	<p> - Go to Admin Panel -> Agents -> Departments </p>
	<p> - Create a Department called System Administrators </p>
	</ul>
Configure Teams
<ul>
	<p> - Go to Admin Panel -> Agents -> Teams </p>
	<p> - Create the following teams </p></ul>
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
<ul>	
<p>	- Go to Admin Panel -> Settings -> User Settings </p>
<p>	- Uncheck the Registration Required so the user doesn't have to require registration to login and create tickets </p>
	-Note: Only for lab purposes. It'll be required to register in the work field
	</ul>

Configure Agents
	- This is for the workers
<ul>	
<p>	- Go to Admin Panel -> Agents -> Add new </p>
<p>	- Create at least 2 agents: e.g. Jane Doe and John Doe </p></ul>
Configure Users
	- This is adding customers
<ul>	
<p>	- Go to Admin Panel -> Users -> Add new </p>
<p>	- Create at least 2 users: e.g. Jenny Jen and Kenny Ken </p></ul>
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure SLA
	- This is to manage tickets on the level of urgency
<ul>	
<p>	- Go to Admin Panel -> Manage -> SLA </p>
<p>	- Sev-A (1 hour, 24/7) </p>
<p>	- Sev-B (4 hours, 24/7) </p>
<p>	- Sev-C (8 hours, 24/7) </p></ul>
Configure Help Topics
<ul>
<p>	- Go to Admin Panel -> Manage -> Help Topics </p></ul>
Select the following topics for users to choose from when deciding what their issue should fall under 
		<ul>
		<p> i. Business Critical Outage
		<p> ii. Personal Computer Issues
		<p> iii. Equipment Request
		<p> iv. Password Reset</ul>
</p>
<br />
