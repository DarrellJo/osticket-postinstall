<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
In continuation of our initial lab, our next task involves configuring and setting up roles, departments, SLAs (Service Level Agreements), and various topics. To commence this process, we will first need to establish a remote connection to our Virtual Machine, which was created during the previous lab session.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- [Remote Desktop](https://apps.apple.com/us/app/microsoft-remote-desktop/id1295203466?mt=12)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- [Roles](https://docs.osticket.com/en/latest/Admin/Agents/Roles.html)
- [Departments](https://docs.osticket.com/en/latest/Admin/Agents/Departments.html)
- [Teams](https://docs.osticket.com/en/latest/Admin/Agents/Teams.html)
- [Agents](https://docs.osticket.com/en/latest/Admin/Agents/Agents.html)
- [Users](https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html)
- [SLA](https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html)
- [Help Topics](https://docs.osticket.com/en/latest/Admin/Manage/Help%20Topic.html)

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Most of the setup requirements can be conveniently accessed from a single location. To access these settings, we simply need to navigate to the Admin Panel, which can be found in the top-left corner of the page. From there, we can proceed to the "Agents" section. Within this section, we will find options to configure Roles, Departments, Teams, and Agents.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Let's proceed with creating a new role called "Supreme Admin." This role will be granted extensive permissions, allowing the administrator to perform and modify various actions with flexibility. 
  
- Go to the "Roles" section in the Admin Panel.
- Click on "Create New Role" or a similar option to start creating the role.
- Give the role a name, such as "Supreme Admin" or any desired name.
- In the "Permissions" tab, select the checkboxes for "Tickets," "Tasks," and "Knowledgeable" to grant extensive access and control.
- Once all permissions are configured, save the role configuration.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  To create a new department named "System Administrators," please follow these steps:
  
  - From the same screen, navigate to the "Departments" section.
  - Look for an option such as "Add New Department" and click on it.
  - Provide the desired name for the department, such as "System Administrators."
  
    - Please note that there are additional options available for configuration from this screen, including adding managers, setting up outgoing email settings, configuring auto responders, and setting up alerts. For the purpose of this lab, we will skip these options.
  
  - Once all the necessary selections and entries have been made to your satisfaction, click on "Create Dept" to finalize the creation of the department.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>To access SLAs (Service Level Agreements) and Help Topics.
  
  Please follow these steps:

    - Within the Admin Panel, find the "Manage" section.
    - Click on either "SLA" or "Service Level Agreements" to access the SLA configuration.
    - Create three SLAs, naming them as desired. For this example, let's use "SEV-A," "SEV-B," and "SEV-C" to correlate with their respective time-frames and coverage.
       - "SEV-A" can have a 1-hour time-frame and provide 24/7 coverage.
       - "SEV-B" can have a 4-hour time-frame and provide 24/7 coverage.
       - "SEV-C" can have an 8-hour time-frame and be applicable during business hours.
   - Save the SLA configurations to create the three SLAs.

To create Help Topics, follow these steps:

    - Within the same "Manage" section in the Admin Panel, locate and click on "Help Topic."
    - Proceed with creating four help topics as follows:
        - "Business Critical Outage"
        - "Personal Computer Issues"
        - "Equipment Request"
        - "Password Reset"
    - Save the Help Topics for each topic created.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Great! Let's proceed with setting up some Users (customers) using the following steps:

- Click on the "Admin Panel" to access it.
- Within the Admin Panel, locate the option to switch to the Agent Panel.
- Once in the Agent Panel, find the "Users" section.
- Click on "Add New" or a similar option to create new user profiles.
- Using the same process we used for creating other environments, create two User profiles named Karen and Kevin. Feel free to modify the names as desired.
- Customize any additional details or settings for each user, such as contact information or preferences.
- Save the user profiles to create the Users Karen and Kevin within the system.

Congratulations! We have successfully set up our osTicketing Software with everything from roles to Help topics, and now we have also added two Users named Karen and Kevin (or any other desired names) to the system.

</p>
<br />
