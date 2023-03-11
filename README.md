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
* Join Client-1 to your domain mydomain.com
* Setup Remote Desktop for non-administrative users on Client-1
* Create additional users and attempt to log into client-1 with one of the users

<h2>Deployment and Configuration Steps</h2>
<br />
<br />
<h3 align="center">Setting Up Resources in Azure</h3>
<br />
