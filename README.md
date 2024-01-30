<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Post-Install Configuration
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.
<br>

## Environments and Technologies Used
- Microsoft Azure
- Remote Desktop
- Internet Information Services (IIS)

## Operating Systems Used
- Windows 10</b> (22H2)

## Post-Install Configuration Objectives
- Configure new Roles
- Configure new Departments
- Configure new Teams
- Allow anyone to create tickets
- Configure new Agents
- Configure new Users
- Configure new SLAs
- Configure new Help Topics

## Configuration Steps
- Log in to your Help Desk portal with the credentials you created during the installation phase.
</p>
<img src="https://i.imgur.com/FAvGHoX.png" height="40%" width="40%" alt="osticket-loginpage"/>
</p>
<br>

- In your portal ensure you run as the Administrator.
- If "Agent Panel" is displayed, you are, in fact, running as the Admin. Otherwise, click on Admin Panel to see the Admin portal from which we are going to set up new configurations.
</p>
<img src="https://i.imgur.com/racELsD.png" height="50%" width="50%" alt="osticket main page"/>
</p>
<br>

### >1. CONFIGURE NEW ROLES
- On the Admin Panel, go to Agents > Roles > Add New Role.
</p>
<img src="https://i.imgur.com/yGafQOf.png" height="50%" width="50%" alt="New roles configuration"/>
</p>
<br>

- Name it "System Administrator".
</p>
<img src="https://i.imgur.com/gCBupbm.png" height="50%" width="50%" alt="New roles configuration"/>
</p>
<br>


- You may edit its permission tickets settings: Permissions > Tickets and,  permission tasks settings: Permissions > Tasks
</p>
<img src="https://i.imgur.com/uDq4oqM.png" height="40%" width="40%" alt="New roles configuration"/>
<img src="https://i.imgur.com/dxo957R.png" height="40%" width="40%" alt="New roles configuration"/>
</p>
<br>

### 2. CONFIGURE NEW DEPARTMENTS
- On the Admin Panel, go to Agents > Departments > Add New Role.
</p>
<img src="https://i.imgur.com/lyYvdzn.png" height="50%" width="50%" alt="New Department configuration"/>
</p>
<br>

- Name it :System Administrators" and keep its default settings.
</p>
<img src="https://i.imgur.com/oCHbCAW.png" height="50%" width="50%" alt="New department configuration"/>
</p>
<br>

### 3. CONFIGURE NEW TEAMS
- Still on the Admin Panel, go to Agents > Teams > Add New Teams. Name it "System Administrator".
</p>
<img src="https://i.imgur.com/uJcVeIm.png" height="50%" width="50%" alt="New Teams configuration"/>
</p>
<br>

- Name it however you like. I named mine "Level II Support", that'll handle more important matters.
</p>
<img src="https://i.imgur.com/eCYNKoV.png" height="50%" width="50%" alt="New Teams configuration"/>
</p>
<br>

- I also set myself as a member of the Level II Support Department.
- I moved to the neighboring tab " Member", clicked on my name and "Add".
</p>
<img src="https://i.imgur.com/wfALegn.png" height="50%" width="50%" alt="New Team configuration"/>
</p>
<br>

### >4. ALLOW ANYONE TO CREATE A TICKET
- On the Admin Panel, go to Agents > Settings > User, and allow anyone to create tickets. Make sure you also check that registration is required.
</p>
<img src="https://i.imgur.com/asOFNcN.png" height="50%" width="50%" alt="New tickets creation"/>
</p>
<br>

### 5. CONFIGURE NEW AGENTS (WORKERS
- On the Admin Panel, go to Agents > Add New Agent.
- We will create two agents: John Clear and Jane Doe.
</p>
<img src="https://i.imgur.com/IbjdNJz.png" height="50%" width="50%" alt="New agents configuration"/>
</p>
<br>

- Register John's full name and email address where users may reach him
- Then set his login credentials by setting a new password. Click "password".
</p>
<img src="https://i.imgur.com/1g8ucDv.png" height="50%" width="50%" alt="New agents configuration"/>
</p>
<br>

- When setting John's or an agent's password, uncheck the email confirmation prompt.
</p>
<img src="https://i.imgur.com/QeWFnwi.png" height="50%" width="50%" alt="New agents configuration"/>
</p>
<br>

- You may configure your agent's permissions, assign your agent a department, a role as well, using the neighborings tabs.
</p>
<img src="https://i.imgur.com/O5f5Isb.png" height="40%" width="40%" alt="New agents configuration"/>
<img src="https://i.imgur.com/HUQa0fJ.png" height="40%" width="40%" alt="New agents configuration"/>
</p>
<br>

- The new agents' list.
/p>
<img src="https://i.imgur.com/gpYZczx.png" height="50%" width="50%" alt="New agents configuration"/>
</p>
<br>

### >6. CONFIGURE NEW USERS (CUSTOMERS)
- Switch to Agent Panel by clicking on it.
</p>
<img src="https://i.imgur.com/racELsD.png" height="50%" width="50%" alt="New USERS configuration"/>
</p>
<br>

- I will create two users but you can create as many as you want.
</p>
<img src="https://i.imgur.com/lxX7CXC.png" height="50%" width="50%" alt="New users configuration"/>
</p>
<br>

- On the Agent Panel, go to Users > Add New User.
</p>
<img src="https://i.imgur.com/5iFr2GM.png" height="50%" width="50%" alt="New users configuration"/>
</p>
<br>

- I created Teddy's profile and followed the same procedure with Suszy's. Then I click on "Add User".
</p>
<img src="https://i.imgur.com/0xxTZom.png" height="50%" width="50%" alt="New users configuration"/>
</p>
<br>

### 7. CONFIGURE NEW SLA
- Back to the Admin Panel, go to Manage > SLA > Add SLA plan
</p>
<img src="https://i.imgur.com/gUqOYzp.png" height="50%" width="50%" alt="New SLA configuration"/>
</p>
<br>

- I created 3 SLAs (SEV-A, SEV-B, SEV-C) with varying severity and deadlines to solving issues.
- SEV-A is considered the most pressent issues that may severely impact the business operations. Thus I set its SLA to 1 hour.
</p>
<img src="https://i.imgur.com/jY4Ybid.png" height="50%" width="50%" alt="New SLA configuration"/>
</p>
<br>

 - Set SEV-B and SEV-C of decreasing importance and with a more generous SLA, as shown.
 - 4 hours on a 24/7 schedule for SEV-B and 8 hours on business hours for SEV-C matters.
</p>
<img src="https://i.imgur.com/IGKhC2K.png" height="50%" width="50%" alt="New SLA configuration"/>
</p>
<br>

### 8. CONFIGURE HELP TOPICS
- On the Admin Panel, go to Agents > Manage > Help Topics > Add New Help Topic.
</p>
<img src="https://i.imgur.com/LiGTa8B.png" height="50%" width="50%" alt="New Help Topics configuration"/>
</p>
<br>

- I named mine "Business Critical Outage" which is the most pressing issue. Name yours.
</p>
<img src="https://i.imgur.com/ddXJ1Fi.png" height="50%" width="50%" alt="New Help Topics configuration"/>
</p>
<br>

- Click the "New Ticket Options" the tab next to the "Help Topic information" tab you've entered your help topic's name.
- Assign it a SLA group. Due to the severity of a business outage, I assigned it to SEV-A thus has 1 hour to be addressed and solved.
</p>
<img src="https://i.imgur.com/mnDqfpT.png" height="50%" width="50%" alt="New Help Topics configuration"/>
</p>
<br>

- I also assigned this type of issue to a particular worker (here John).
</p>
<img src="https://i.imgur.com/fGVORyP.png" height="50%" width="50%" alt="New Help Topics configuration"/>
</p>
<br>
