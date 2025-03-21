<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" height="75%" width="100%"alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This guide outlines the post-install configuration steps of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machine)
- Remote Desktop (RDP)
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10 (22H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

# Configuration Steps</b>
</p>

Step one is to configure roles inside the admin panel. Create role "**Supreme Admin**", give full control.

Admin Panel -> Agents -> Roles

![image](https://github.com/user-attachments/assets/1fafca69-c42e-47f6-a8fd-63a60f2ec978)

![image](https://github.com/user-attachments/assets/c6dc6136-f7f0-482c-b011-956752a2489f)

![image](https://github.com/user-attachments/assets/53688c57-be92-4dee-880e-d225fd0dc779)

![image](https://github.com/user-attachments/assets/816fdd7f-666f-40d5-ac2f-c04542f39d26)

Now, create the "**System Administrators**" department.

Admin Panel -> Agents -> Departments

![image](https://github.com/user-attachments/assets/fe37d425-e2ad-4db7-a229-fa329d63b844)

Next, we are going to create the "**Online Banking**" team.

Admin Panel -> Agents -> Teams

![image](https://github.com/user-attachments/assets/4965a9ea-8664-4ae4-9ada-25b927d5f157)

Next navigate to this path, and make sure "**Require registration and login to create tickets**", is *unchecked*.

Admin Panel -> Settings -> User Settings

![image](https://github.com/user-attachments/assets/18aea986-937f-4b45-8ec2-c342faa81968)

Next, create agent. Give "Supreme Admin" role.

Admin Panel -> Agents -> Add New Agent

![image](https://github.com/user-attachments/assets/6c9ab028-c0aa-4fc1-9115-c0e93afce4de)

Set password.

![image](https://github.com/user-attachments/assets/973a059a-06da-4862-98c8-7a7734c28dd6)

![image](https://github.com/user-attachments/assets/c6ef084c-b43f-4891-a263-38940bf9dea2)

Next, create another agent. Give "Support" role.

![image](https://github.com/user-attachments/assets/2f25b05d-0836-4a55-bb92-4a4b21a6fc6c)

Set password.

![image](https://github.com/user-attachments/assets/d097516e-3238-406a-ab87-274754ba3d8d)

![image](https://github.com/user-attachments/assets/6b081c09-caca-49d3-9152-5018db0743d5)

Now that the agents have been created, we are going to create an end user. (This is what we will use to create and solve mock tickets.)

Admin Panel -> Users -> Create New

![image](https://github.com/user-attachments/assets/ec5f0327-2376-406a-a77d-1af0d7979d68)

Now, we need to configure SLA.

Admin Panel -> Manage -> SLA

Sev-A (Grace Period: 1 hour, Schedule: 24/7)</p>

Sev-B (Grace Period: 4 hours, Schedule: 24/7)</p>

Sev-C (Grace Period: 8 hours, Business Hours)</p>

![image](https://github.com/user-attachments/assets/e255ed8c-4a19-491c-a033-0d22deaad496)

![image](https://github.com/user-attachments/assets/231bc552-7726-474b-93d5-f72a2769779d)

![image](https://github.com/user-attachments/assets/d2a759e7-84e7-4fa1-a508-916995eabd37)

![image](https://github.com/user-attachments/assets/79923d35-1cec-4157-8e07-60af79ce41d1)

Lastly, we will configure Help Topics.

Admin Panel -> Manage -> Help Topics










