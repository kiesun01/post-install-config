<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Installation Configuration</h1>
Tutorial for Configuration of ticket system operations.<br />
<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure: Utilized for Virtual Machines and compute resources.
- Remote Desktop: Used for accessing and managing the virtual machine.
- Internet Information Services: Employed as the web server to host osTicket.

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Documentation</h2>

- Roles: https://docs.osticket.com/en/latest/Admin/Agents/Roles.html
- Departments: https://docs.osticket.com/en/latest/Admin/Agents/Departments.html
- Teams: https://docs.osticket.com/en/latest/Admin/Agents/Teams.html
- Agents: https://docs.osticket.com/en/latest/Admin/Agents/Agents.html
- Users: https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html
- SLA: https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html
- Help Topics: https://docs.osticket.com/en/latest/Admin/Manage/Help%20Topic.html

<h2>List of Prerequisites</h2>

- Microsoft Azure Active Subscription (Creation of Reasearch Group, VMs, Virtual Networks, Subnets)
- Enable Internet Information Services(IIS)
- PHP Manager
- Rewrite Manager
- C++ Redistributbal
- MySQL Server
- Install osTicket
- Access Provisioning

<h2>Configuration Steps: 1 - 12</h2>

![image](https://github.com/kiesun01/post-install-config/assets/132006466/a71539e6-f4b3-4b34-986c-8911e07fb4e4)
<p>
Step 1: Open a browser in the VM and enter http://localhost/osTicket/scp/login.php in the bar. Login with credentials we created. (ex: admin username: jerry)
</p>
<br />

![image](https://github.com/kiesun01/post-install-config/assets/132006466/bb5b4644-2800-44cc-b41e-45148069703c)
<p>
Step 2: Configure Roles. Admin Panel -> Agents -> Roles
</p>
<br />

![image](https://github.com/kiesun01/post-install-config/assets/132006466/08456a92-c562-4baa-9a59-d0be4cbe3121)
![image](https://github.com/kiesun01/post-install-config/assets/132006466/a5bc663c-534f-49af-a58c-1d3cb6136f13)
<p>
Step 3: Admin Panel -> Add New Role -> Enter name (ex: Chief Admin) -> Permissions -> Allow All
</p>
<br />

![image](https://github.com/kiesun01/post-install-config/assets/132006466/586d3606-5481-439c-9c41-775c679bff73)
![image](https://github.com/kiesun01/post-install-config/assets/132006466/2d460558-3b17-4abe-8ff9-8cf1cf6c2023)
<p>
Step 4: Tasks -> Admin Panel -> Allow all -> Knowledgebase -> Check in Premade -> Click "Add Role"
</p>
<br />

![image](https://github.com/kiesun01/post-install-config/assets/132006466/1f5defdd-d3b5-43fe-86b1-5d2f883d1d97)
![image](https://github.com/kiesun01/post-install-config/assets/132006466/87fb3b0e-4767-4612-bc44-96cf966a5bd9)
<p>
Step 5: Configure Deparments -> Add New Department -> set parameters. ex: Top Level Department(ex: System Administrators) -> Creat Dept
</p>
<br />
<p>

![image](https://github.com/kiesun01/post-install-config/assets/132006466/9130c697-f4a6-4c51-b128-d672c09f423f)
Step 6: Configure Teams -> Admin Panel -> Add New Team -> Fill out parameters (ex: Name: Level II Support, Members: Jerry Lu) -> Create Team
</p>
<br />

![image](https://github.com/kiesun01/post-install-config/assets/132006466/016770a0-b98e-4508-98f0-6cefbadeaee7)
<p>
Step 7: Allow anyone to create a ticket. Admin Panel -> Settings -> Users -> Uncheck "Registration Required" -> Save Changes
</p>
<br />

![image](https://github.com/kiesun01/post-install-config/assets/132006466/341b37ae-9dcd-489e-b827-0875188f9782)
<p>
Step 8: Configure Agents -> Admin Panel -> Agents -> -> Fill out parameters -> ex:Add New Agent(ex: Cameron Jones) 
</p>
<br />


<p>
Set Agent Password -> Uncheck Sent the Agent a Password Again -> Uncheck REquire Password at Next Login -> Click Set -> Create
</p>
<br />
