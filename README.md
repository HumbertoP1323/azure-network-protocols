<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
Here we'll explore diverse network traffic involving Azure Virtual Machines using Wireshark, alongside hands-on experimentation with Network Security Groups. <br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- create a virtual machine
- Download Wireshark
- Utilize commands within the command prompt and PowerShell to observe and track network traffic.
- Use filters in Wireshark to see certain network traffic by focusing on specific pathways.

<h2>Actions and Observations</h2>
   <img src="https://i.imgur.com/HGgWRAt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
You can use both Wireshark and PowerShell to keep an eye on the traffic flowing between the two virtual machines you've created. Wireshark's filters allow you to concentrate on particular traffic triggered by your PowerShell pings.
<p>
