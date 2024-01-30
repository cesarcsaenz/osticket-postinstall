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
- Windows 10 (22H2)

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
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/24199b68-331a-4f3f-94fd-d4dfe99a73b0" height="40%" width="40%" alt="osticket-loginpage"/>
</p>
<br>

- In your portal ensure you run as the Administrator.
- If "Agent Panel" is displayed, you are the Admin section. Otherwise, click on Admin Panel to see the Admin portal from which we are going to set up new configurations.
</p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/fca4c2a2-4a32-4456-8642-7cabda22cc47" height="50%" width="50%" alt="osticket main page"/>
</p>
<br>

### >1. CONFIGURE NEW ROLES
- On the Admin Panel, go to Agents > Roles > Add New Role.
</p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/32e93894-ddff-4856-9594-09288cbcf262" height="50%" width="50%" alt="New roles configuration"/>
</p>
<br>

- Name it "System Administrator".
</p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/619a2ce4-c2a7-45d0-a739-7a5fd5a6078c" height="50%" width="50%" alt="New roles configuration"/>
</p>
<br>


- You may edit its permission tickets settings: Permissions > Tickets and, permission tasks settings: Permissions > Tasks
</p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/de38175a-e7e5-47fa-bcc7-3e5c0f1326ef" height="40%" width="40%" alt="New roles configuration"/>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/619c8d0a-783c-4a06-b2cb-fc315002d3a0" height="40%" width="40%" alt="New roles configuration"/>
</p>
<br>

### 2. CONFIGURE NEW DEPARTMENTS
- On the Admin Panel, go to Agents > Departments > Add New Role.
</p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/edf4f19e-69c3-4c1e-bf0a-a64b22135c7d" height="50%" width="50%" alt="New Department configuration"/>
</p>
<br>

- Name it "System Administrators" and keep its default settings.
</p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/50ed866d-d80a-4d28-802d-a38baf2577f1" height="50%" width="50%" alt="New department configuration"/>
</p>
<br>

### 3. CONFIGURE NEW TEAMS
- Still on the Admin Panel, go to Agents > Teams > Add New Teams. Name it "System Administrator".
</p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/1fa4933f-a161-4f0e-8588-26157e390540" height="50%" width="50%" alt="New Teams configuration"/>
</p>
<br>

- Name it however you like. I named mine "Level II Support", that'll handle more important matters.
</p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/e10a69af-924e-4041-8c09-1f47c99273b0)" height="50%" width="50%" alt="New Teams configuration"/>
</p>
<br>

- I also set myself as a member of the Level II Support Department.
- I moved to the neighboring tab " Member", clicked on my name and "Add".
</p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/50d730bc-f9c3-4108-a5ae-f53007d1407f" height="50%" width="50%" alt="New Team configuration"/>
</p>
<br>

### 4. ALLOW ANYONE TO CREATE A TICKET
- On the Admin Panel, go to Agents > Settings > User, and allow anyone to create tickets. Make sure you also check that registration is required.
</p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/478669fd-2e87-4734-b3b2-33a71dedd561" height="50%" width="50%" alt="New tickets creation"/>
</p>
<br>

### 5. CONFIGURE NEW AGENTS (WORKERS
- On the Admin Panel, go to Agents > Add New Agent.
- Create two agents: John Clear and Jane Doe.
</p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/88b17f51-15e3-4e4a-a530-f50598004bb8" height="50%" width="50%" alt="New agents configuration"/>
</p>
<br>

- Register John's full name and email address where users may reach him.
- Then set his login credentials by setting a new password. Click "password".
</p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/73b35d7b-5101-484b-ab32-6e36a5a16309" height="50%" width="50%" alt="New agents configuration"/>
</p>
<br>

- When setting John's or an agent's password, uncheck the email confirmation prompt.
</p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/03880f73-5daf-4cd3-bf38-1fdd4067cd25" height="50%" width="50%" alt="New agents configuration"/>
</p>
<br>

- You may configure your agent's permissions, assign your agent a department, a role as well, using the neighborings tabs.
</p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/8247002a-069b-405f-801b-dd5eda9ba917" height="40%" width="40%" alt="New agents configuration"/>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/7f781f4c-ace6-48d9-90ac-4c0731e28efa" height="40%" width="40%" alt="New agents configuration"/>
</p>
<br>

- The new agents' list.
/p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/526b842f-4f58-4011-8fad-c693bc4aea36" height="50%" width="50%" alt="New agents configuration"/>
</p>
<br>

### >6. CONFIGURE NEW USERS (CUSTOMERS)
- Switch to Agent Panel by clicking on "Agent Panel".
</p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/68aa09b6-cf3c-4d0e-8293-c8f6939def6f" height="50%" width="50%" alt="New USERS configuration"/>
</p>
<br>

- Create two users, or you can create as many as you want.
</p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/b13a2be4-6a5f-45b8-8e9a-b81b8a4be075" height="50%" width="50%" alt="New users configuration"/>
</p>
<br>

- On the Agent Panel, go to Users > Add New User.
</p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/001288ad-ca95-4f2c-b2f4-a268aca12873" height="50%" width="50%" alt="New users configuration"/>
</p>
<br>

- I created Teddy's profile and followed the same procedure with Suszy's. Then I click on "Add User".
</p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/e1380541-5b8b-4b1c-aa5a-1af0b0638ea0" height="50%" width="50%" alt="New users configuration"/>
</p>
<br>

### 7. CONFIGURE NEW SLA
- Back to the Admin Panel, go to Manage > SLA > Add SLA plan
</p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/005f48a5-aa79-42d7-9f98-3608a67fd875" height="50%" width="50%" alt="New SLA configuration"/>
</p>
<br>

- Create 3 SLAs (SEV-A, SEV-B, SEV-C) with varying severity and deadlines to solving issues.
- SEV-A is considered the most pressent issues that may severely impact the business operations. Set its SLA to 1 hour.
</p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/42f6b3f4-3c3e-4caa-9607-f8fb91cf8be2" height="50%" width="50%" alt="New SLA configuration"/>
</p>
<br>

 - Set SEV-B and SEV-C of decreasing importance and with a more generous SLA, as shown.
 - 4 hours on a 24/7 schedule for SEV-B and 8 hours on business hours for SEV-C matters.
</p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/3104ec3a-5d25-4de0-b025-5d68cdda9c84" height="50%" width="50%" alt="New SLA configuration"/>
</p>
<br>

### 8. CONFIGURE HELP TOPICS
- On the Admin Panel, go to Agents > Manage > Help Topics > Add New Help Topic.
</p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/83fcf39c-f88b-4a51-8708-44f6458a4230" height="50%" width="50%" alt="New Help Topics configuration"/>
</p>
<br>

- Name it "Business Critical Outage" which is the most pressing issue. (You can name yours as you like).
</p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/ec9cd70c-31a2-4cb5-abc6-1cd8f9e36f3a" height="50%" width="50%" alt="New Help Topics configuration"/>
</p>
<br>

- Click the "New Ticket Options" the tab next to the "Help Topic information" tab you've entered your help topic's name.
- Assign it a SLA group. Due to the severity of a business outage, I assigned it to SEV-A thus has 1 hour to be addressed and solved.
</p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/ea8e62b8-139b-4573-83d5-8d4dfb3f226e" height="50%" width="50%" alt="New Help Topics configuration"/>
</p>
<br>

- I also assigned this type of issue to a particular worker (here John).
</p>
<img src="https://github.com/cesarcsaenz/osticket-postinstall/assets/153584649/136f0d07-a92d-495c-83ba-efe496b4754f" height="50%" width="50%" alt="New Help Topics configuration"/>
</p>
<br>

## osTicket Documentation
Links to Documentation in osTicket for the configurations above:

- [Roles](https://docs.osticket.com/en/latest/Admin/Agents/Roles.html)
- [Departments](https://docs.osticket.com/en/latest/Admin/Agents/Departments.html)
- [Teams](https://docs.osticket.com/en/latest/Admin/Agents/Teams.html)
- [Agents](https://docs.osticket.com/en/latest/Admin/Agents/Agents.html)
- [Users](https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html)
- [SLA](https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html)
- [Help Topics](https://docs.osticket.com/en/latest/Admin/Manage/Help%20Topic.html)
