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

<h2>High-Level Steps</h2>

- Create Two Virtual Mahcines in Azure (Windows 10 & Linux)
- Download Wireshark
- Observe ICMP Traffic
- Observe SSH Traffic
- Observe DNS Traffic

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/lldRtKH.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download Wireshark within your Windows 10 virtual machine.
</p>
<br />

<p>
<img src="https://i.imgur.com/xxKtc2X.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Ping the second virtual mahcine from it's private IP address. Filter Wireshark to view ICMP Traffic
</p>
<br />

<p>
<img src="https://i.imgur.com/nX5nuFj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
SHH into other Virtual Machine and view traffic.
</p>
<br />


<p>
<img src="https://i.imgur.com/1OxCUwW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Observe DNS Traffic and use nslookup to find www.google.com's IP address.
</p>
<br />
