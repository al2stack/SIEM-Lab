# SIEM-Lab
This was a guided lab on using the Microsoft Azure Portal to build a honeypot virtual machine and capture all failed RDP log in attempts and gather their geolocation data and visualize it onto a map using Microsoft Sentinel, a cloud-based SIEM (Security Information and Event Management) tool. 
<h2>Platforms Used</h2> 
Azure Virtual Machines: Creation of the virtual machine with the weakest security configurations possible<br/>
Microsoft Sentinel (SIEM): Visualization of attacks on a world map and graphs<br/>  
Log Analytics: Collecting data and query scripting<br/> 
ipgeolocation.io: Gives us an API key which we use to track geo data<br/>
PowerShell: Extract RDP failed login attempts from Windows Event Viewer<br/>
<h2>Attacks After 5 Days of Running VM</h2> 

![Picture6](https://github.com/user-attachments/assets/b9c4583b-a664-4734-95e8-630018668b71)

<h2>Bar Graph of Most Commonly Attempted Usernames</h2> 

![Picture3](https://github.com/user-attachments/assets/deabb503-3b51-4a50-a418-f9c685162293)

<h2>Attack Events By Country</h2> 

![Picture4](https://github.com/user-attachments/assets/f8c36018-edd0-4118-ac1c-51d753c4f8a1)
