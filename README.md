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


