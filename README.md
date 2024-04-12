<h1>Azure Honeypot (SIEM) Project</h1>


 ### [Click Here for the full breakdown of the project](https://medium.com/@smerene/azure-honeypot-project-8bb8a8826a7e) (Medium)


<h2>Description</h2>
<b>The objective of the Azure Honeypot Project was to create a simulated environment within Microsoft Azure to attract, monitor, and analyze potential cyber threats. This project allowed me to gain practical experience and hands-on knowledge in cybersecurity, particularly within the context of cloud computing and threat detection.
</b>
<br />
<br />

<p align="center">
<img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*xgjMRFFb5ICYBDpB3d98ww.jpeg"/>
</p>
<br />
The script is used in this demo where I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot.
We will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to
look up the attackers Geolocation information and plot it on an Azure Sentinel Map!
<br />
<h2>Languages Used</h2>

- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API

<h2>Attacks from Panama coming in; Custom logs being output with geodata</h2>

<p align="center">
<img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*xrLa3ABOG9xqAs4ZFzu6HQ.png"/>
</p>

<h2>World Map of all of the incoming attacks(built custom logs including geodata)</h2>

<p align="center">
<img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*ta4DsBB42u7RmvVi6QBmNg.png"/>
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
