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

- Now you will create the teams that will belong to the "department" you just created. Click on the "add new team button". When you are done click the "create teams button".
<img src="imagesp/Screenshot%202024-12-25%20043405.png">








