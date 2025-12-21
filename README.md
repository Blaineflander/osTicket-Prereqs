<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<p align="center"
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This outlines the prerequisites and installation of the open-source help desk ticketing system osTicket. osTicket is an open‑source support ticketing system designed to streamline customer service operations. It centralizes inquiries from email, web forms, and APIs into a single, organized dashboard. I successfully created both agent and administrator accounts within a virtual testing environment, generated business‑related and basic support tickets, and gained hands‑on experience performing administrative tasks, including configuring user permissions and managing access to accounts and files.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: Creating a Virtual Machine: Part 1](https://youtu.be/BQ98WaJMrus)
- ### [YouTube: Accessing The VM through RDP: Part 2](https://www.youtube.com/watch?v=m95UgmUnw0I)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating/Applications Systems Used </h2>

- Windows 10 (21H2)
- Azure
- (osTicket, Azure Storage, Azure Virtual Machines)</b> 

<h2>List of Prerequisites</h2>

- Provision a Windows 10 virtual machine in Microsoft Azure.
    - The VM will serve as the host environment for installing and running osTicket.
      
- Establish a Remote Desktop Protocol (RDP) connection to the virtual machine.
    - This provides administrative access for software installation and system configuration.
 
- Install all required software components and deploy the osTicket application.
    - This includes configuring both Agent and Administrator roles within the system.
      
- Perform functional testing and implement helpdesk ticket workflows.
    - Validate that ticket creation, assignment, and communication processes operate as expected.
      
-  Resolve and close test tickets to confirm end‑to‑end system functionality.
    - This ensures the helpdesk environment is fully operational and ready for production use.

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/Ra3YyoG.png"nheight="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/VHBDzwm.png"nheight="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I began by creating a Azure account and signing in. From there, I set up a new resource group and deployed a Windows 10 virtual machine. After the VM was successfully created, I located its public IP address, which allowed me to connect to the virtual machine through Remote Desktop Protocol (RDP)
</p>
<br />

<p>
<img src="https://i.imgur.com/vGaKcxZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once I logged into the virtual machine, I downloaded the remaining required software and configured the necessary permissions to ensure the osTicket application could run properly.
</p>
<br />

<p>
<img src="https://i.imgur.com/KbKIWDr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After preparing the virtual machine, I installed the remaining prerequisites and configured everything needed for osTicket to function properly. 
<br />


