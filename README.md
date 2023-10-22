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

- OSticket Installed
- Logins created in previous exercise

<h2>Configuration Steps</h2>

<p>
<img <a href="https://imgur.com/UXH1aPe"><img src="https://i.imgur.com/UXH1aPe.png" title="source: imgur.com" /></a>
<a href="https://imgur.com/b9dSAmO"><img src="https://i.imgur.com/b9dSAmO.png" title="source: imgur.com" /></a>
</p>
<p>
After installation clean up 2 things from the previous exercise.  Delete the setup file in the osTicket folder, and set the ost-config files to read only.  Now Logins for admin will be created (http://localhost/osTicket/scp/login.php) & for end users will be created( http://localhost/osTicket).
</p>
<br />

<p>
<img <a href="https://imgur.com/h8uK1Aa"><img src="https://i.imgur.com/h8uK1Aa.png" title="source: imgur.com" /></a>
<a href="https://imgur.com/OLjRt3l"><img src="https://i.imgur.com/OLjRt3l.png" title="source: imgur.com" /></a>
<a href="https://imgur.com/tpcInOB"><img src="https://i.imgur.com/tpcInOB.png" title="source: imgur.com" /></a>
<a href="https://imgur.com/ZtAiIRx"><img src="https://i.imgur.com/ZtAiIRx.png" title="source: imgur.com" /></a>
</p>
<p>
Login to the Admin portal and navigate Admin panel and create Roles, a Department, Team, & Agent.  Next make head to user settings and Require registration for creating a ticket. 
 After this is done create agents, customers, & SLA system.  Along with Help topics for issues to be sorted to.  Once this is done Osticket is setup and ready to proceed with handling tickets. 
</p>
<br />
