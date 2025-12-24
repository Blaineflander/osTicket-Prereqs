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
    - Provisioning administrative access for software installation and system configuration.
 
- Insstalation of all required software components and to deploy the osTicket application.
    - windows IIS With CGI
    - PHP Manger for IIS
    - SQL database and provisioning
    - 

<h2>Installation Steps</h2>


<p>
 I began by creating an Azure account and signing in. From there, I created a new resource group and deployed a Windows 10 virtual machine. After the VM finished provisioning, I retrieved its public IP address and used it to connect via Remote Desktop Protocol (RDP). Once logged into the VM, I downloaded the necessary files and extracted the contents of the compressed folders.
</p>
<br />

<p>
<img src="https://i.imgur.com/VHBDzwm.png"nheight="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/vGaKcxZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/EM3yvhG.png"nheight="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once I was in the vm I then had a set of tools that I needed to install and instrutions I had to follow.
First I was start by setting up IIS. Then I began to install IIS with CGI (Common Gateway Interface). After, I installed the PHP manger for IIS. 
</p>
<br />
<p>
<img src="https://i.imgur.com/kit3pZ0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/QIN0rj4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here I was installing the Rewriting Module. After I created the Directory PHP on the C drive. Then extracted the intallation files in the diectorty folder. after I installed other arburtraies that were needed. 
</p>
<br />
<p>
<img src="https://i.imgur.com/VFAMHIl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/mfqLcml.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/iE3gX58.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next I installed and provisioned SQL database, an I Set up an admin account.
<p>
<p>
<img src="https://i.imgur.com/2CQSMLR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/xJIqnmO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After I registered the PHP from within the IIS, There I was able to nativagte to the the PHP directory I made up earlier. 
<br />
<p>
<img src="https://i.imgur.com/BkWcmCg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I restarted the IIS, Then I had to add the folder into the C drive. I had to rename it. here I am editing the directory for osTicket, and finshing the install and the final edits.
<br />
<p>
<img src="https://i.imgur.com/wPGMJcF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now I have osTicket installed, I now am provisioning the needed extentions 
<br />
<p>
<img src="https://i.imgur.com/PuVWUs2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/M0bMl95.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

