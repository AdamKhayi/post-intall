<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" height="75%" width="100%"alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial demonstrates the post-install configuration of osTicket.<br />


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
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<h3 align="center">Configure Roles</h3>
<br />
<p>
  Admin Panel -> Agents -> Roles.
</p>
<p>
  Supreme Admin:
</p>
<p>
  <img src="https://i.imgur.com/WOz8S5j.png" height="75%" width="100%" alt="Definitions"/>
  <img src="https://i.imgur.com/JS7vXnJ.png" height="75%" width="100%" alt="Permissions"/>
  <img src="https://i.imgur.com/QfeHNN1.png" height="75%" width="100%" alt="More Permissions"/>
  <img src="https://i.imgur.com/Osx8gzC.png" height="75%" width="100%" alt="Even More Permissions"/>
  <img src="https://i.imgur.com/eB2O1lk.png" height="75%" width="100%" alt="Sys Admin Success"/>
</p>
<br />
<br />
<h3 align="center">Configure Departments</h3>
<br />
<p>
  Admin Panel -> Agents -> Departments.
</p>
<p>
  System Administrators:
</p>
<p>
  <img src="https://i.imgur.com/Pw5rGn1.png" height="75%" width="100%" alt="System Administrators"/>
</p>
<br />
<br />
<h3 align="center">Configure Teams</h3>
<br />
<p>
  Admin Panel -> Agents -> Teams.
</p>
<p>
  Level II Support:
</p>
<p>
  <img src="https://i.imgur.com/4SH0A2A.png" height="75%" width="100%" alt="Level II Support"/>
</p>
<br />
<br />
<h3 align="center">Allow anyone to create ticket</h3>
<br />
<p>
  Admin Panel -> Settings -> User Settings.
</p>
<p>
  Make sure to not select "Require registration and login to create tickets":
</p>
<p>
  <img src="https://i.imgur.com/eH8uirZ.png" height="75%" width="100%" alt="ticket creations"/>
</p>
<br />
<br />
<h3 align="center">Configure Agents (workers)</h3>
<br />
<p>
  Admin Panel -> Agents -> Add New.
</p>
<p>
  Jane Doe:
</p>
  <img src="https://i.imgur.com/z3cWnba.png" height="75%" width="100%" alt="agent one access"/>
<p>
  John Doe:
</p>
<p>
  <img src="https://i.imgur.com/OUFFuAI.png" height="75%" width="100%" alt="agent two"/>
  <img src="https://i.imgur.com/ZgEA2pv.png" height="75%" width="100%" alt="agent two access"/>
</p>
<h3 align="center">Configure Users (customers)</h3>
<br />
<p>
  Admin Panel -> Users -> Add New.
</p>
<p>
  Ken User:
</p>
  <img src="https://i.imgur.com/zatEUJu.png" height="75%" width="100%" alt="user access"/>
<p>
  Repeat the same above for Karen User.
</p>
<br />
<br />
<h3 align="center">Configure SLA</h3>
<br />
<p>
  Admin Panel -> Manage -> SLA.
</p>
<p>
  Sev-A (1 hour, 24/7).
</p>
<p>
  Sev-B (4 hours, 24/7).
</p>
<p>
  Sev-C (8 hours, business hours):
</p>
<p>
  <img src="https://i.imgur.com/pKHZ2o8.png" height="75%" width="100%" alt="sev one"/>
  <img src="https://i.imgur.com/sFrAWDn.png" height="75%" width="100%" alt="sev two"/>
  <img src="https://i.imgur.com/KPMoD8r.png" height="75%" width="100%" alt="sev three"/>
</p>
<br />
<br />
<h3 align="center">Configure Help Topics</h3>
<br />
<p>
  Admin Panel -> Manage -> Help Topics.
</p>
<p>
  Business Critical Outage.
</p>
<p>
  Personal Computer Issues.
</p>
<p>
  Equipment Request.
</p>
<p>
  Password Reset.
</p>
<p>
  <img src="https://i.imgur.com/HcWNoj5.png" height="75%" width="100%" alt="business critical outage"/>
  <img src="https://i.imgur.com/okx3hBV.png" height="75%" width="100%" alt="personal computer issues"/>
  <img src="https://i.imgur.com/l8dkCIB.png" height="75%" width="100%" alt="equipment request"/>
  <img src="https://i.imgur.com/xkddp1g.png" height="75%" width="100%" alt="password reset"/>
</p>
<br />
<br />
<p>
  This concludes the configuration osTicket.
</p>

[Click here to see the project that displays the lifecycle of a ticket within osTicket](https://github.com/AdamKhayi/ticket-lifecycle)
