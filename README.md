<h1>Capturing a Packet Using Wireshark</h1>



<h2>Description</h2>
In this lab, I learned to capture a packet using Wireshark. Wireshark is an open-source software tool that captures packets and analyzes protocol information from that captured data.
<br />



<h2>Environments Used </h2>

- <b>Windows Server 2016 Standard</b> 


<h2>Languages and Utilities</h2>

- <b>Wireshark<b>

<h2>Program walk-through:</h2>

<p align="center">
From the desktop open up wireshark: <br/>
<img src="https://i.postimg.cc/7hkZ23vm/Screen-Shot-2022-08-31-at-10-18-50-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
<br>
In the Wireshark Analyzer window select your ethernet and then click the start capturing packets icon:<br>
<img src="https://i.postimg.cc/ncbbkFP9/Screen-Shot-2022-08-31-at-10-23-25-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
  
<br />
Minimize the Wireshark window and open up ggogle chrome and visit any website you wish:</br>
<img src="https://i.postimg.cc/0yGwQyLY/Screen-Shot-2022-08-31-at-10-26-18-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
  
<br />
After several minutes close the internet browser and then navigate back to Wireshark and stop the packets:  <br/>
<img src="https://i.postimg.cc/LXWc1RrD/Screen-Shot-2022-08-31-at-10-28-52-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />


<br />
In the filter toolbar type in "http" to find packets with this protocol:  <br/>
<img src="https://i.postimg.cc/VsCGR2pJ/Screen-Shot-2022-08-31-at-10-31-48-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />



<br />
In the Packet list choose any packet and then observe that it says Hyper Text Transfer Protocol:  <br/>
<img src="https://i.postimg.cc/mrhkf3W5/Screen-Shot-2022-08-31-at-10-34-30-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />




<br />
Expand the packet to view its contents then right click the selected packet and select follow>TCP Stream:  <br/>
<img src="https://i.postimg.cc/vBk3LvGF/Screen-Shot-2022-08-31-at-10-38-30-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />





<br />
View the information from TCP stream for extra information then close the window:  <br/>
<img src="https://i.postimg.cc/LXxMHwkk/Screen-Shot-2022-08-31-at-10-41-11-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />




<br />
From the menu bar, click file and save. then name the file and save the packet information:  <br/>
<img src="https://i.postimg.cc/dt4n5vsj/Screen-Shot-2022-08-31-at-10-43-36-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />














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
