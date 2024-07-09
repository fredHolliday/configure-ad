# configure-ad
<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of Active Directory within Azure Virtual Machines.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1 Create a Server with Windows Server 2022.
- Step 2 Create a Client with Windows 10.
- Step 3 Set your Windows server DNS to static.
- Step 4 Join the client, to the domain.

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/I0LCJ0F.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The screenshot shows two Virtual Machines  (VMDC-1) server, and (Client-1) client two. Make sure that the virtual network is the same.

</p>
<br />

<p>
<img src="https://i.imgur.com/xf1XuoV.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
(VMDC-1) server you will need to set DNS to static.
</p>
<br />

<p>
<img src="https://i.imgur.com/Ep01Wvo.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Join the client, to the domain. (VMDC-1) server
</p>
<br />

<br />

<p>
<img src="https://i.imgur.com/eM7qhzu.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create Admin and organizational is active directory.  
</p>
<br />
