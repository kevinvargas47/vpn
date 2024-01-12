<p align="center">
<img src="https://pbs.twimg.com/media/FUBLRgdWYAAH6nD?format=jpg&name=medium" height = 20% width = 20%/>
</p>

<h1 align = "center">Understanding and Installing Virtual Private Networks</h1>
A Virtual Private Network is a service that securely links two computers (or networks) together accross an insecure network such as the Internet, allowing them to send encapsulated and encrypted data to each other. This tutorial shows how to install a VPN through Microsoft Azure.
<p>
<br />
<h2>Environments and Technologies Used</h2>
<ul>
  <li>Microsoft Azure (Virtual Machines/Compute)</li>
  <li>Remote Desktop</li>
  <li>Internet Browser (of your choice)</li>
  <li>Proton VPN</li>
  <li>Notepad to write down information</li>
</ul>

<br />

<h2>Operating Systems Used</h2>
<ul>
  <li>Windows 10 Pro (21H2)</li>
</ul>

<br />

<h2>Installing Proton VPN</h2>

<h3>Setting up Resources and Citing IP Addresses</h3>

<p>
Go to https://whatismyipaddress.com/. Take note of the IPv4 Address, this is for the local computer
<p>
<img src="https://i.imgur.com/jQ2RZXU.jpg" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<p>
Access the Azure Portal to create a virtual machine, like this as an example. When creating it make sure the Region is set to a region outside of your country.
<p>
<img src="https://i.imgur.com/X6RFc1W.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
Log in to the virtual machine through Remote Desktop and go to https://whatismyipaddress.com/. The IPv4 address should be different than the one on the local computer, take note of this.
<p>
<img src="https://i.imgur.com/J1vXssE.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<p>
Create an account on Proton VPN on the local computer
<p>
<img src="https://i.imgur.com/VlSs0PG.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<p>
At home page copy and paste URL to sign in on the virtual machine, download Windows VPN Client.
<p>
<img src="https://i.imgur.com/REU46O8.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<p>
Install Proton VPN in downloads the launch program. In Proton VPN launch the Japan server then go to https://whatismyipaddress.com/
<p>
<img src="https://i.imgur.com/vKRiQNB.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<p>
Refresh the page and note the virtual machine with vpn
<p>
<img src="https://i.imgur.com/eESVGyN.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<p>
This is the conclusion of the lab
