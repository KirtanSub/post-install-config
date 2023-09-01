<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)


<h2>Configuration Steps</h2>

<p>
</p>
<p>

Fantastic! You have now successfully installed osTicket, we will now need to configure some things, and do a "post-installation setup". After we have done this, we can go and "solve" tickets. We have to first configure some roles, let's create a "Senior Admin" by going to Admin Panel ---> Agents ---> Roles. Let's also make sure to give them permissions to close, delete, assign, and edit tasks to agents and teams.

<img src="https://i.imgur.com/Sj9RVbx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/hDHgc6A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
</p>
<p>

After this, let's configure the departments. Go to Admin Panel ---> Agents ---> Departments. Create a new department titled System Administrators. After this, configure the teams. For example, we can add a team for Level II support. Go to Admin Panel ---> Agents ---> Teams to create this.

<img src="https://i.imgur.com/RO19qF4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/kAXVt3Z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
<br />

<p>
</p>
<p>

Great! Let's now allow the end-users to create tickets, this just means that we should allow anyone to create tickets. Go to Admin Panel ----> Settings -----> User Settings, and under authentication settings, click to allow the requirement for registration and login to create tickets. After this, we should add new workers, to further create a more realistic environment of a helpdesk. Go to Admin Panel --> Agents --> Add New. Let's name these agents Jane and John (you can use whatever names you like) and fill out their "contact info".

<img src="https://i.imgur.com/4V0LWnH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/1MB861c.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/eBBLhHW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
<br />


<p>
</p>
<p>

Now let's create some "end-users". These people will serve as users that have reported "technical issues". Go to Agent Panel ---> Users ---> Add New. Let's name these users Julie and John (once again you may use whatever names you like). We can also configure our Service-Level Agreements or SLAs. Let's add three tiers of SLAs. Go to Admin Panel ---> Manage ---> SLA. We can call our first level as Sev-A, and add a grace period of 1 hour (meaning that the ticket should be solved in 1 hour), and also add another stipulation that these tickets can be solved 24/7. We can then add Sev-B, however this type of ticket will have a grace period of 4 hours, as it is more of a serious ticket/issue, and we can add the same stipulation that this type of ticket can be solved 24/7. Finally, we can add the last tier of tickets, Sev-C, this is the most serious of tickets, and as such, will get a grace period of 8 hours. Also, we will allow this ticket to be solved during business hours.

<img src="https://i.imgur.com/X86pIHl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/3t1CPp1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/sTMvJsc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/a5DMTkD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/9HhTbjB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
<br />



<p>
</p>
<p>

At our final step, we can configure which help topics we want to add, these will be the categories that end-users can select for the questions they ask. We can add categories such as: Password Reset, Equipment Request, and Personal Computer Issues.

<img src="https://i.imgur.com/Q6m1ADo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/5AqFhO3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/FxeFhWI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
<br />


