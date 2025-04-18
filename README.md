<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Admin vs Agent Panel 
- Configure Roles (Permission Groups)
- Configure Departments (Ticket Routing & Visibility)
- Configure Teams (Cross-Department Collaboration)
- User Settings – Ticket Creation Rules
- Configure Agents (Support Staff Setup)
- Configure Users (Customers/End Users)
- Configure SLA (Service Level Agreements)
- Configure Help Topics (Ticket Categorization)

<h2>Configuration Steps</h2>

<p>
<img width="1440" alt="Screenshot 2025-04-17 at 5 07 15 PM" src="https://github.com/user-attachments/assets/a6a3d75e-574e-4d0a-bfd6-c6ee24a938e2" />
<img width="1440" alt="Screenshot 2025-04-17 at 5 06 38 PM" src="https://github.com/user-attachments/assets/aeb023d9-6472-4efe-877c-e51e57794e30" />
</p>
<p>
🔹 1. Admin vs Agent Panel
Description:
After installation, it's crucial to distinguish between the Admin Panel (for managing system-wide settings, agents, roles, etc.) and the Agent Panel (used by help desk staff to view and respond to tickets). Understanding these two interfaces ensures proper navigation and role-based responsibilities.
</p>
<br />

<p>
<img width="1440" alt="Screenshot 2025-04-17 at 5 08 12 PM" src="https://github.com/user-attachments/assets/f97dc64b-953b-4235-bd53-3b8ba51f9b2e" />
</p>
<p>
🔹 2. Configure Roles (Permission Groups)

Description:
Roles define what actions agents can perform in the system. In this step, you create custom roles (like Supreme Admin) to group permissions for various agent responsibilities. This ensures each agent has the correct access level based on their duties.
</p>
<br />

<p>
<img width="1440" alt="Screenshot 2025-04-17 at 5 09 25 PM" src="https://github.com/user-attachments/assets/313bebbc-4798-47ac-96a6-574aaa46b08b" />
</p>
<p>
🔹 3. Configure Departments (Ticket Routing & Visibility)

Description:
Departments control which tickets are visible to which agents. You can create departments such as Help Desk, SysAdmins, and Networking. Assigning agents to specific departments ensures tickets are routed correctly and only seen by relevant staff.
</p>
<br />

<p>
<img width="1440" alt="Screenshot 2025-04-17 at 5 10 09 PM" src="https://github.com/user-attachments/assets/cdf2df2c-399d-4fe0-9051-6b4833d47d6f" />
</p>
<p>
🔹 4. Configure Teams (Cross-Department Collaboration)
Description:
Teams allow agents from different departments to collaborate on tickets without being in the same department. For example, a team like Online Banking can include members from multiple departments to tackle tickets more efficiently across specialties.
<br />

<p>
<img width="1440" alt="Screenshot 2025-04-17 at 5 11 01 PM" src="https://github.com/user-attachments/assets/79db4e1b-0856-4d41-a4c4-ab6e79fbbcc7" />
</p>
<p>
🔹 5. User Settings – Ticket Creation Rules

Description:
This configuration controls who can submit tickets. By requiring user registration, you ensure only authenticated users can create tickets. This helps with user management and ticket tracking while preventing spam or anonymous submissions.
</p>
<br />

<p>
<img width="1440" alt="Screenshot 2025-04-17 at 5 12 50 PM" src="https://github.com/user-attachments/assets/ed8f49db-69c3-48fa-9afd-4a55de92be40" />
</p>
<p>
🔹 6. Configure Agents (Support Staff Setup)

Description:
Agents are your help desk team members. In this step, you add staff like Jane (SysAdmins) and John (Support), assigning them to the appropriate departments so they can begin handling tickets.
</p>
<br />

<p>
<img width="1440" alt="Screenshot 2025-04-17 at 5 13 37 PM" src="https://github.com/user-attachments/assets/8f5243b5-644b-43d2-a59a-c62f1cb80175" />
</p>
<p>
🔹 7. Configure Users (Customers/End Users)

Description:
Users are the customers who submit tickets. You manually add users such as Karen and Ken or allow self-registration, so they can begin requesting support and tracking their issues through the system.
</p>
<br />

<p>
<img width="1440" alt="Screenshot 2025-04-17 at 6 08 18 PM" src="https://github.com/user-attachments/assets/4c08fc92-29d8-4412-86d7-265709272cba" />
</p>
<p>
🔹 8. Configure SLA (Service Level Agreements)
Description:
SLAs define the expected response and resolution time for tickets. You configure different levels:

Sev-A: 1-hour response, 24/7

Sev-B: 4-hour response, 24/7

Sev-C: 8-hour response, business hours
This helps prioritize tickets and sets expectations for both users and agents.
</p>
<br />

<p>
<img width="1440" alt="Screenshot 2025-04-17 at 5 15 09 PM" src="https://github.com/user-attachments/assets/8a2fc57c-4c38-44f3-a864-260ea4ef335e" />
</p>
<p>
🔹 9. Configure Help Topics (Ticket Categorization)

Description:
Help Topics help users categorize their issues during ticket submission. You create common topics such as:

Business Critical Outage

Personal Computer Issues

Equipment Request

Password Reset
This improves ticket routing and ensures tickets go to the right teams automatically.
</p>
<br />
