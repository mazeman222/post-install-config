<p align="center">
<img src="imagesp/Screenshot%202024-12-25%20042807.png">
</p>

<h1>osTicket - Post-Install Configuration</h1>
Here I will outline the post-install configuration for the open-source help desk ticketing system osTicket.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of what is needed</h2>

- Desktop/Laptop
- Azure/AWS/Google Account (When you signup with Microsoft Azure free tier, you get a $200 credit.)
- Internet Information Services (IIS) Manager
- Remote Desktop Connection

  **********All OF THIS LIST ABOVE SHOULD ALREADY BE SETUP FROM THE INSTALLATION OF OSTICKET ******

- This is the window for submitting support tickets as an end user. When you want to get to that portal type: localhost/osticket/ in your brower bar and you will be directed to that portal.
<img src="imagesp/Screenshot%202024-12-26%20021148.png">

- When you login into the worker/admin portal: localhost/osticket/scp/login.php you will reach to the main dashboard where you can see your tickets. This picture below is of the worker panel and you can tell by the tabs that you have access to.
<img src="imagesp/Screenshot%202024-12-25%20043053.png">

When you click on the admin panel tab next to your name, then this window gives you the admin tabs, so that you can do admin responsibilities. Here you will be able to edit agents, tasks, knowledgebase, and many more functions.

- When you want to add a role to an employee, you go to the agents panel > roles > and then click "add new role". When you click "add new role" this window pops up:
<img src="imagesp/Screenshot%202024-12-25%20043115.png"><br>
Then click on the permissions tab and give them all access, tasks and knowledgebase.<br>
<img src="imagesp/Screenshot%202024-12-25%20043137.png"><br>
<img src="imagesp/Screenshot%202024-12-25%20043157.png"><br>
<img src="imagesp/Screenshot%202024-12-25%20043216.png">

- For ticket visibility you will want to ensure that the right departments will see the ticket when the end users submits it in the portal. While still in the "admin panel" go to the "agents tab". In the "agents tab" click on the "departments tab". Then click on the " add new department" button. When the window pops up, then you can fill out the information to create the department that will respond to the ticket.
<img src="imagesp/Screenshot%202024-12-25%20043315.png">

- Now you will create the teams that will belong to the "department" you just created. Click on the "add new team button". When you are done click the "create team button".
<img src="imagesp/Screenshot%202024-12-25%20043405.png">

- Here you will be adding a new agent, as if you hired them to your brand new company. In the "admin panel" go to "agents > add new agents" and click the button. In the picture below I am the only agent but I will add two more agents to the fictional company.
<img src="imagesp/Screenshot%202024-12-25%20043452.png"><br>
The two agents has been added "Sam and Susie".<br>
<img src="imagesp/Screenshot%202024-12-25%20043515.png">

- Click on the "agent panel" at the top right of the page and then click on "users". This account will be used for when you want to test the functionality of the system once everything is built out. "Amber Full" was the name of the account that I have created. You can see that she has "guest" in the status box.
<img src="imagesp/Screenshot%202024-12-25%20043536.png">

- Configuring the Service Level Agreements is the next step that needs to be done. Make sure that you are in the "admin panel" and click on "manage > SLA". When you click on SLA the service window will pop up and you can create new SLA's from there. Click on the "create new SLA plan button" to get started creating one. HEre you can set the grace period, status and the schedule of the SLA.
<img src="imagesp/Screenshot%202024-12-25%20043555.png">
<img src="imagesp/Screenshot%202024-12-25%20043612.png">
Three of them were created:
<img src="imagesp/Screenshot%202024-12-25%20043638.png">

- Now you have what you need to send and respond to tickets in osTicket.




