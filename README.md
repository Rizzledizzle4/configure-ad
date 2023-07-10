<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of Active Directory within Azure Virtual Machines.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computers)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Setup Resources in Azure
- Ensure Connectivity between virtual Machines
- Install Active Directory
- Create Infasructure within Active Directory

<h2>Deployment and Configuration Steps</h2>


![image](https://github.com/Rizzledizzle4/configure-ad/assets/135624545/1df0ee58-eca5-4f15-97c6-7fb1d62a7b24)

Create the Domain Controller VM (Windows Server 2022) named “DC-1”
Set Domain Controller’s NIC Private IP address to be static.
Create the Client VM (Windows 10) named “Client-1”. 
Ensure that both VMs are in the same Vnet (you can check the topology with Network Watcher.

</p>
<br />

![image](https://github.com/Rizzledizzle4/configure-ad/assets/135624545/1d95f4df-0e0b-4b94-87c9-cce70ba4ab31)



Login to Client-1 with Remote Desktop and ping DC-1’s private IP address with ping -t <ip address> (perpetual ping).
Login to the Domain Controller and enable ICMPv4 in on the local windows Firewall.
Check back at Client-1 to see the ping succeed.


</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
