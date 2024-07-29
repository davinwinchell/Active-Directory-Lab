<h1>Active Directory Home Lab</h1>

<h2>Description</h2>

<br />


<h2>Languages and Programs Used</h2>

- <b>PowerShell ISE</b> 
- <b>Windows Active Directory</b>
- <b>Oracle VirtualBox</b>

<h2>Environments Used </h2>

- <b>Windows 10 Enterprise</b>
- <b>Windows Server 2019</b>

<h2>Program walk-through:</h2>

<p align="center">
Create a network diagram: <br/>
<img src="https://i.imgur.com/EBC49v7.png" height="80%" width="80%"/>
<br />
<br />
Set up a VM for the Domain Controller:  <br/>
<img src="https://i.imgur.com/LbdEusn.png" height="80%" width="80%"/>
<br />
<br />
Install Windows Server 2019 on the Domain Controller VM: <br/>
<img src="https://i.imgur.com/SCw3FR6.png" height="80%" width="80%"/>
<br />
<br />
Set up ethernet adapters on the Domain Controller:  <br/>
<img src="https://i.imgur.com/2XIg8dS.png" height="80%" width="80%"/>
<br />
<br />
Install Active Directory Domain Services:  <br/>
<img src="https://i.imgur.com/qKJQkfv.png" height="80%" width="80%"/>
<br />
<br />
Create domain forest and promote the machine to domain controller:  <br/>
<img src="https://i.imgur.com/yU8OK32.png" height="80%" width="80%"/>
<br />
<br />
Create a new user and add to domain group:  <br/>
<img src="https://i.imgur.com/dQ7KdPX.png" height="80%" width="80%"/>
<br />
Create domain forest and promote the machine to domain controller:  <br/>
<img src="https://i.imgur.com/yU8OK32.png" height="80%" width="80%"/>
<br />
<br />
Install Remote Access role:  <br/>
<img src="https://i.imgur.com/8iKZuKf.png" height="80%" width="80%"/>
<br />
<br />
Set up network address translation on the domain controller:  <br/>
<img src="https://i.imgur.com/pwgOF6l.png" height="80%" width="80%"/>
<br />
<br />
Install DHCP server role:  <br/>
<img src="https://i.imgur.com/VYK3dcJ.png" height="80%" width="80%"/>
<br />
<br />
Set up DHCP scope:  <br/>
<img src="https://i.imgur.com/MztQGMO.png" height="80%" width="80%"/>
<br />
<br />
Use a PowerShell script to create hundreds of users (credit: @JoshMadakor/YT):  <br/>
<img src="https://i.imgur.com/2RaVk0q.png" height="80%" width="80%"/>
<br />
<br />
Set up client VM:  <br/>
<img src="https://i.imgur.com/A265ZDj.png" height="80%" width="80%"/>
<br />
 <br />
Install Windows 10 Enterprise on client VM:  <br/>
<img src="https://i.imgur.com/Tiek5YB.png" height="80%" width="80%"/>
<br />
 <br />
Rename client PC and join domain:  <br/>
<img src="" height="80%" width="80%"/>
<br />
 <br />
Log into client PC using one of the newly created users:  <br/>
<img src="" height="80%" width="80%"/>
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
