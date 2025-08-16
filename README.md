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

- Create Agents in osTicket
- Create and assign Roles, Teams, and Departments
- Create Users
- Create SLA's (Service Level Agreements)
- Create Help Topics

<h2>Configuration Steps</h2>


<img width="771" height="593" alt="image" src="https://github.com/user-attachments/assets/2088fe23-b61b-43ec-90cf-96a96e90b6a8" >

First I logged into the osTicket admin webpage and then switched to the admin pannel. Then clicked "Agents"-"Roles"-"Add New Role" and created a new role. I named the new role "Super Admin" and checked all of the boxes under "Tickets", "Tasks", and "Knowledgebase".


<img width="482" height="598" alt="image" src="https://github.com/user-attachments/assets/2036282b-e7ac-4249-bfd2-d176e874128a" >

Then under "Agents"-"Departments" I created a new department named "Sysadmin". (I left evrything else default and only added a name)


<img width="549" height="534" alt="image" src="https://github.com/user-attachments/assets/f8e20107-6da9-4e45-bec8-95e5bb49b950" />

I then created a new team named "Online Banking".



<img width="708" height="624" alt="image" src="https://github.com/user-attachments/assets/b7061a1a-ad60-4f5f-a0b3-3b01240cd24d" />

Next I created an agent named "Jane Doe" and entered a filler email address then set the username as "Jane" and password as "Password1"



<img width="767" height="427" alt="image" src="https://github.com/user-attachments/assets/40cf77df-1369-4c19-8a9c-020498650dd5" />

<img width="764" height="386" alt="image" src="https://github.com/user-attachments/assets/c39e6cb4-b188-4c58-b46f-74fb559611a8" />


I assigned Jane to the sysadmin department with the "supreme admin" role that we created and added her to the online banking team 



<img width="754" height="610" alt="image" src="https://github.com/user-attachments/assets/d7f61337-cdb7-4207-a747-b551beecf556" />


<img width="697" height="689" alt="image" src="https://github.com/user-attachments/assets/7c962c2c-4768-4dc7-b39a-bea63a104d14" />



I also created an agent named John Doe and added him to the support department with the view only role and clicked "create". username for this agent is "John" and password is "Password1!"


<img width="817" height="573" alt="image" src="https://github.com/user-attachments/assets/4fe444d9-c6a3-4ea2-b3ff-2c76ff4fc3bf" />



Next, I went to the agent pannel in the top right of the screen and created a new user named "Karen"


<img width="768" height="543" alt="image" src="https://github.com/user-attachments/assets/8f86210f-db56-40a1-80bc-93400f00006c" />


Then I switched back to the admin pannel and clicked the "Manage" tab then "SLA" (Service Level Agreement) and created a new SLA named "SEV-A" with a 1 hour grace period on a 24/7 schedule.


<img width="768" height="541" alt="image" src="https://github.com/user-attachments/assets/c6ada10d-284e-4b2d-8c32-1c3f1cc70645" />

I created another SLA named "SEV-B" with a 4 hour grace period on a 24/7 schedule



<img width="768" height="555" alt="image" src="https://github.com/user-attachments/assets/84e2788c-edd5-4c04-9c76-0270ce54bad4" />


I made one last SLA named "SEV-C" with an 8 hour grace period on a business hour schedule (Mon-Fri 8-5)



<img width="770" height="545" alt="image" src="https://github.com/user-attachments/assets/854d6f2e-50a8-44f3-8e7c-204be7309955" />

Next I went to "Help Topics" and created a new help topic called "Business Critical Outage" and listed the parent topic as "Report a Problem".


<img width="782" height="575" alt="image" src="https://github.com/user-attachments/assets/0f30c306-c062-4f9e-b18f-9c2068790282" />

I made another help topic named "Personal Computer Issues" and made the parent topic "Report a Problem".


<img width="769" height="545" alt="image" src="https://github.com/user-attachments/assets/9092a6d0-aea8-4716-b687-4f8becb94c7a" />

Then I made a help topic named "Equipment Request" with the parent topic as "General Inquiry".

<img width="777" height="550" alt="image" src="https://github.com/user-attachments/assets/ecad8644-1741-4122-bb39-735d97f43368" />

I made another help topic and named it "Password Reset" with the parent topic as "Report a Problem".


<img width="796" height="552" alt="image" src="https://github.com/user-attachments/assets/0bb68196-1ebe-4268-ae79-c35d28d9a38f" />


Then I made one more help topic and named it "Other" with the parent topic as "General Inquiry"


Now we have completed the post installation steps for osTicket and are ready to use the software to create and resolve tickets.


