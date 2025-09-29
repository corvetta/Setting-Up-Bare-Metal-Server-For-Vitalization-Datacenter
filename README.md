<h1>Server Setup Project 0</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
Lab 0 began with a Dell PowerEdge R620 server. I installed Proxmox Virtual Environment to create a base platform for virtualization. I uploaded ISO images for Windows Server, Windows 10, Ubuntu Server, Kali Linux, and pfSense. I configured storage and networking to support future virtual machines. This setup provided the foundation for building firewalls, directory services, monitoring tools, and cloud integrations in later labs.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Proxmox Virtual Environment:</b> Hypervisor platform  
- <b>Windows Server ISO:</b> Directory services and DNS  
- <b>Windows 10 ISO:</b> Client operating system  
- <b>Ubuntu Server ISO:</b> Logging and monitoring services  
- <b>Kali Linux ISO:</b> Penetration testing tools  
- <b>pfSense ISO:</b> Firewall and router  
- <b>Linux Command Line:</b> System management and configuration  
- <b>Proxmox Web Interface:</b> VM and storage management  
- <b>ZFS:</b> Storage configuration  
- <b>LVM:</b> Alternative storage option  
- <b>Proxmox Network Bridges:</b> Virtual networking  
- <b>VLANs:</b> Network segmentation  

<h2>Environments Used </h2>
- <b>Dell PowerEdge R620:</b> Bare metal server hardware  
- <b>Proxmox VE 8.x:</b> Virtualization environment  
- <b>Windows Server 2019/2022:</b> Domain services  
- <b>Windows 10/11:</b> Client environment  
- <b>Ubuntu Server 22.04:</b> Logging and monitoring  
- <b>Kali Linux:</b> Security testing environment  
- <b>pfSense:</b> Network firewall and router  



<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
