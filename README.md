<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration </h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)


<h2>Installation Steps</h2>


<p>
Login to Admin/Analyst Login Page URL:  http://localhost/osTicket/scp/login.php

![Screenshot 2024-12-22 224643](https://github.com/user-attachments/assets/8888d416-f54b-48f5-b7a4-f4312f830058)

Login to End Users osTicket URL: http://localhost/osTicket 

![Screenshot 2024-12-22 224720](https://github.com/user-attachments/assets/964e098b-3d31-4116-b37f-cb53d82b3032)



<br />



<p>
Configure SysAdmins Department (Admin Panel -> Agents -> Departments)
  

![Screenshot 2024-12-22 225208](https://github.com/user-attachments/assets/c0ce89b6-8263-4544-959e-89bd4c7dcd12)
![Screenshot 2024-12-22 225325](https://github.com/user-attachments/assets/a2c43aeb-705c-4047-a95c-253e01abcc35)


  
</p>
<br />


<p>
Configure Online Banking Teams (Admin Panel -> Agents -> Teams)

![Screenshot 2024-12-22 225414](https://github.com/user-attachments/assets/2f3f03dc-f591-4464-8826-f5bb95408b6e)
![Screenshot 2024-12-22 225452](https://github.com/user-attachments/assets/b0b23480-1e86-40d5-8e3c-219d99687a4a)


  
</p>
<br />


<p>
Allow anyone to create tickets

Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)

Registration Required: Require registration and login to create tickets 

![Screenshot 2024-12-22 225603](https://github.com/user-attachments/assets/f2613423-a79a-472b-b80a-7b5ad598f257)


 
</p>
<br />


<p>

Configure Agents (Admin Panel -> Agents -> Add New)

![Screenshot 2024-12-22 225722](https://github.com/user-attachments/assets/dffb4c55-17e3-46bb-869b-f55379a25411)


Jane (Dept: SysAdmins)
![Screenshot 2024-12-22 225843](https://github.com/user-attachments/assets/e4f037e5-4a26-4119-8910-de6a5874bcca)
![Screenshot 2024-12-22 225943](https://github.com/user-attachments/assets/bf80bce5-4f15-4825-aa0f-f51b9ba0bd0c)
![Screenshot 2024-12-22 230118](https://github.com/user-attachments/assets/1f0cbdf5-bb53-4a99-9698-0c39eb7e75f6)
![Screenshot 2024-12-22 230210](https://github.com/user-attachments/assets/f702259b-3bca-40bf-9543-668961ffdb45)
![Screenshot 2024-12-22 230227](https://github.com/user-attachments/assets/2f621776-092b-4012-8238-15702d1a01b1)



John (Dept: Support)
![Screenshot 2024-12-22 230528](https://github.com/user-attachments/assets/0a485c8e-4709-4d6f-ace7-4862a03b456c)
Make sure you select All Access instead of view only
![Screenshot 2024-12-22 230555](https://github.com/user-attachments/assets/b7396dd1-cee4-4954-8de5-410f33d73d60)


  
</p>
<br />


<p>
Configure User: Karen (Agent Panel -> Users -> Add New)
  
![Screenshot 2024-12-22 233532](https://github.com/user-attachments/assets/41f96d0b-c824-47b9-bd17-08eeb6dd9343)
![Screenshot 2024-12-22 233615](https://github.com/user-attachments/assets/ac16e712-a784-4e9d-8600-57797692e24e)
![Screenshot 2024-12-22 233727](https://github.com/user-attachments/assets/9d2d1123-eda3-45bf-a179-d1cc9773006d)




<br />


<p>
Configure SLA (Admin Panel -> Manage -> SLA)

![Screenshot 2024-12-22 233832](https://github.com/user-attachments/assets/c761ef61-2deb-4cbf-9d8f-03634bf92409)


```
  Sev-A (Grace Period: 1 hour, Schedule: 24/7)
  Sev-B (Grace Period: 4 hours, Schedule: 24/7)
  Sev-C (Grace Period: 8 hours, Business Hours)
```
![Screenshot 2024-12-22 234911](https://github.com/user-attachments/assets/16834b5d-1be5-4dbf-9e91-253dfd6430ae)
![Screenshot 2024-12-22 234945](https://github.com/user-attachments/assets/89158163-e5d9-4eb5-9645-ecba6bd851aa)
![Screenshot 2024-12-22 235020](https://github.com/user-attachments/assets/7eb1641c-2759-47be-9ae7-324c103ea7ad)




<br />


<p>
Configure Help Topics (Admin Panel -> Manage -> Help Topics)

![Screenshot 2024-12-22 235102](https://github.com/user-attachments/assets/05ef0188-f9f6-4ac1-a2ac-cace212e4eed)

  
```
  Business Critical Outage (Parent Topic: Report a Problem)
  Personal Computer Issues(Parent Topic: Report a Problem)
  Equipment Request(Parent Topic: General Inquiry )
  Password Reset(Parent Topic: Report a Problem)
  Other(Parent Topic: General Inquiry )

```
![Screenshot 2024-12-22 235205](https://github.com/user-attachments/assets/f25e8d06-b2c0-4a22-a423-9ebbbe0579d3)

![Screenshot 2024-12-22 235712](https://github.com/user-attachments/assets/e0ae9e41-1d16-414b-b9bd-6dd9115f083f)



</p>
<br />


