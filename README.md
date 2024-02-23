<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

<h2>High-Level Steps</h2>

- Step 1 Build Intuition For DNS and create A-Record in DC (Domain Controller). 
- Step 2 Create CNAME record, and observe changes with ping "search", nslookup, ipconfig, and other commands.
- Step 3 Create file shares "read-access", "write-access", "no-access", "accounting" with various permissions. Attempt to access file shares as a normal user.
- Step 4 Create an "ACCOUNTANTS" (Security Group) in Active Directory, and assign permissions to test access.
- 
<h2>Actions and Observations</h2>

<p> 
<img src="https://github.com/AndreRobinsonCC/azure-network-protocols/assets/133404844/71c0ba52-cebf-4408-8298-06f1f6ffdf0e" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
A-Record in DC (Domain Controller).  
</p>
<br />

<p>
<img src="https://github.com/AndreRobinsonCC/azure-network-protocols/assets/133404844/72ec083e-418e-42b7-a28c-601b8c88616b" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
CNAME record created. Observe (ipconfig). 
</p>
<br />

<p>
<img src="https://github.com/AndreRobinsonCC/azure-network-protocols/assets/133404844/e11757ba-387e-412e-a312-55e0257de461" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 File shares "read-access", "write-access", "no-access", "accounting" created with permissions.
</p>
<br />
