<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com/watch?v=mbckqBHjLxM)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- User Access Management: Define roles and permissions for agents, admins, and users to ensure proper access control.
- Email Notifications Setup: Configure notification settings to ensure timely communication for ticket updates and responses.
- Custom Fields and Forms: Create custom fields and forms to capture specific information relevant to your support process.
- Knowledge Base Creation: Set up a knowledge base to provide self-service resources for users and reduce ticket volume.


<h2>Configuration Steps</h2>
<p>
<h3>Step 1: Login to the Admin Panel</h3>

1. URL: Navigate to your osTicket admin panel by visiting -> http://yourdomain.com/scp.</p>
2. Login: Use the admin username and password created during installation.

 ![step 1 image](https://github.com/user-attachments/assets/2906f395-88e9-41c6-a78a-5938dbc91965)

<p>
<br />
<br />
<p>
<h3>Step 2: Set Up Email Integration</h3>

1. Go to Admin Panel -> Email.</p>
2. Add Mailboxes: Configure the email addresses osTicket will use to send and receive tickets (example -> support@yourdomain.com).</p>
3. Choose the method for receiving emails and configure the SMTP server for sending out notifications.</p>

 ![step 2 image](https://github.com/user-attachments/assets/b6746f5d-b09a-4246-a5e3-defd1bbb45d1)
  
<p>
<br />
<br />
<p>
<h3>Step 3: Configure Help Topics and Departments</h3>

1. Navigate to Admin Panel -> Manage -> Help Topics to define the types of issues your users can submit tickets for (example -> Billing, Technical Support, etc.).</p>

![step 3 1 image](https://github.com/user-attachments/assets/2bba7706-0a29-473c-b893-adae6162e704)</p>

<br />
2. Set up Departments (example -> Sales, Support) to assign tickets based on specific areas of responsibility.</p>

<img width="958" alt="step 3 2 image" src="https://github.com/user-attachments/assets/284d452c-2032-44f9-833a-f542b1cbd2d3"></p>

3. Ensure the Help Topics are linked to the appropriate departments.</p>

<p>
<br />
<br />
<p>
<h3>Step 4: Set Up Ticket Priorities & SLA Plans</h3>

1. Admin Panel -> Manage -> Ticket Priorities: Define different priority levels (example -> Low, Medium, High).</p>

<img width="960" alt="step 4 image" src="https://github.com/user-attachments/assets/a282aa80-b3af-4660-b589-8cbfb0f0a21a"></p>

<br />
2. Set up SLA Plans under Admin Panel -> Manage -> SLA Plans to define expected response and resolution times based on ticket priority and department.</p>

![step 4 2 image](https://github.com/user-attachments/assets/8aad3475-f5d3-43df-939d-2f0f49465b67)

<p>
<br />
<br />
<p>
<h3>Step 5: Create User Groups and Permissions</h3>

1. Go to Admin Panel -> Manage -> Teams to create groups for your support agents (example -> Tier 1, Tier 2).</p>

<img width="960" alt="step 5 image" src="https://github.com/user-attachments/assets/e2a0d3b5-5594-4265-ad66-f31ab178d1aa"></p>

<br />
2. Set Permissions for each group under Admin Panel -> Manage -> Roles to control what agents can access and do within the system (example -> View Tickets, Assign Tickets, Manage Settings).</p>

<img width="739" alt="step 5 2 image" src="https://github.com/user-attachments/assets/a65f1442-9f55-484f-8feb-db2e6b0b97b3">

<p>
<br />
<br />
<p>
