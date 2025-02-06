<h1>Perform a MAC Flooding Attack using macof</h1>

 ## [Video Demonstration](https://drive.google.com/file/d/1mZ6HTZW-fkZRlJFb354HBnNDQg95EXE1/view?usp=sharing)

<h2>Description</h2>
Macof is a network attack tool that floods a switch with Ethernet frames containing random MAC addresses, effectively overloading its MAC address table. It is part of the dsniff suite and is commonly used for MAC flooding attacks to force a switch into hub mode, allowing an attacker to capture network traffic. <br><br>
Macof sends the packets with random MAC and IP addresses to all active machines in the local network. If multiple targets are used, the same packets can be observed on all target machines.<br><br>

In this lab I perform a MAC Flooding Attack using macof and observe the packets in Wireshark. 
<br />

<h2>Lab walk-through:</h2>

<p align="center">
macof commands: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
