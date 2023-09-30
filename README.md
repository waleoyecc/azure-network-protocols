<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

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

- Step 1 Created two Virtual Machines on Azure, with One running on Windows and the other running on Linux
- Step 2 Logged into the Remote Desktop Computers with the IP address from the Virtual Machines created
- Step 3 Connected to some Network Protocols (DNS, SSH, ICMP)
- Step 4 Wireshark ping and traffic was tested 

<h2>Actions and Observations</h2>

![Created vms wndws et Linx](https://github.com/waleoyecc/azure-network-protocols/assets/140360882/04ed117b-b87d-4da2-bc62-29cb1d8ba4e4)

Created two Virtual Machines, one running on Windows and the other running on Linux

![Created vms in 1 RG](https://github.com/waleoyecc/azure-network-protocols/assets/140360882/ac7ff8d8-161c-49a3-b2d4-a805145c62a3)

![Created vms in 1 RG](https://github.com/waleoyecc/azure-network-protocols/assets/140360882/1449bd85-4241-4cc6-bce6-95a947020e74)

The two Virtual machines created in the same Resource group

![Log to RDsktp1](https://github.com/waleoyecc/azure-network-protocols/assets/140360882/5c3dcd1d-7a0b-4426-b3e3-abe5a30e139f)

Logged into the Remote Desktop with Virtual Machine IP address

![ping denied](https://github.com/waleoyecc/azure-network-protocols/assets/140360882/3ec910f2-4692-44af-bd28-b21ba4593b97)

ping command for ICMP denied

![ping allowed again](https://github.com/waleoyecc/azure-network-protocols/assets/140360882/a124d1f5-19ed-4913-9cae-ef5547275ddd)

ping command for ICMP allowed

![ping for vm wale2 wt powershell2](https://github.com/waleoyecc/azure-network-protocols/assets/140360882/45bb4548-86ff-4f4f-b821-370d0744aae9)

ping command to Wale2

![ssh connect establshed and closed](https://github.com/waleoyecc/azure-network-protocols/assets/140360882/c2af87ab-b84c-46bd-945d-0a56c97a8300)

SSH connection established. 

   ![dns traffic](https://github.com/waleoyecc/azure-network-protocols/assets/140360882/9b12802f-7d73-4b19-82e1-6b015e09705d)

DNS traffic 

![wireshark ping](https://github.com/waleoyecc/azure-network-protocols/assets/140360882/b497d840-9949-45f1-85b1-7d372ef69e0d)

WireShark ping

![Wireshark traffic](https://github.com/waleoyecc/azure-network-protocols/assets/140360882/36b3dfc4-bebf-4103-8761-660692fcbde2)

Wireshak traffic

