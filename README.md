<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" height="40%" width="70%"alt="Microsoft Active Directory Logo"/>
</p>

<h1>Configuring Active Directory (On-Premises) Within Azure</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />



<h2>Technologies Used</h2>

* Microsoft Azure (Virtual Machine Instance)
* Microsoft Remote Desktop
* Active Directory Domain Services
* PowerShell ISE

<h2>Operating Systems</h2>

* Windows Server 2022
* Windows 10 (21H2)

<h2>Configuration Steps</h2>

* Create Resources
* Enstablish Connectivity between the Client and Domain Controller
* Install Active Directory
* Create Admin and Normal User Account in AD
* Join Client-1 to your domain (mydomain.com)
* Setup Remote Desktop for non-administrative users on Client-1
* Create additional users and attempt to log into client-1 with one of the users

<h2>Deployment and Configuration Steps</h2>
<br />
<br />
<h3 align="center">Setting Up Resources in Azure</h3>
<br />

<p>
<img src="https://i.imgur.com/aNstDo2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/JQFWaFp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Step 1 create two VM instances, Client (Client1) and Domain Controller (DC-1). Client 1 is a windows 10 VM and DC-1 uses windows server.  In Azure Navigate to NIC of DC1 and set to static
</p>
<br />

<p>
<img src="https://i.imgur.com/9dKyyML.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 2 Using Remote Desktop login to DC-1 and enable ICMP echo request
</p>
<br />

<p>
<img src="https://i.imgur.com/BbFnQEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 3 In DC1 open server manager and click  add roles and features. select active directory domain  services.
</p>
<br />

<p>
<img src="https://i.imgur.com/PRDco93.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p> Step 4 Setup name for domain controller. For this lab will  dc will be called mydomain.com
</p>
<br />

<p>

<p>
<img src="https://i.imgur.com/QDOiqeU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>






