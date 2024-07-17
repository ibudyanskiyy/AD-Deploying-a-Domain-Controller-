<h1>Deploying a Domain Controller</h1>

 ### [YouTube Demonstration](https://www.youtube.com/watch?v=AvRh61ei2n8&t=555s&ab_channel=ianskyBytes)

<h2>Description</h2>
Deploying a domain controller on Active Directory Server 2019 involves installing the Active Directory Domain Services (AD DS) role via Server Manager and promoting the server to a domain controller. This process includes setting up a new forest, configuring a static IP address, specifying directory paths, and ensuring all prerequisites are met. After installation, the server will automatically reboot, and you can verify the setup through Active Directory Users and Computers. This deployment enables network management and integration of computers into the domain.
<br />

<h2>Languages & Utilities:</h2>

- <b>Server Manger</b>

<h2>Environments:</h2>

- <b>Windows 10</b>
- <b>Oracle VirtualBox<b> 

<h2>Step Demonstration:</h2>
<p align="center">
Open the Virtual Machine with Server 2019 Privileges: <br/>
<img src="https://i.imgur.com/MJqpPjW.png" height="80%" width="80%" alt=
<br />
<br />
Open Server Manager & Select Add Roles & Features: <br/>
<img src="https://i.imgur.com/L43fd6Y.png" height="80%" width="80%" alt= 
<br />
<br />
Select (Role Based) Installation Type & Destination Server: <br/>
<img src="https://i.imgur.com/HKml7V0.png" height="80%" width="80%" alt=
<br />
<br />
Select AD DS Role & Verify Installation Selections: <br/>
<img src="https://i.imgur.com/XkiAP2L.png" height="80%" width="80%" alt=
<br />
<br />
Proceed to Install Active Directory Domain Services: <br/>
<img src="https://i.imgur.com/1V8Zs1P.png" height="80%" width="80%" alt=
<br />
<br />
Open Server Manager & Open AD DS Configuration Wizard (Select: Promote this Server to a Domain Controller"):  <br/>
<img src="blob:https://imgur.com/054ab7af-898e-4397-8c98-e074991f417b height="80%" width="80%" alt=
<br />
<br />
Add a New Forest & Root Domain Name:  <br/>
<img src="https://i.imgur.com/Bd7JqwI.png" height="80%" width="80%" alt=
<br />
<br /> 
Verify Additional DC Configurations: <br/> 
<img src="https://i.imgur.com/6eh6zJA.png" height="80%" width="80%" alt=
<br />
<br />
Check Prerequisites & Complete Installation: <br/>
<img src="https://i.imgur.com/sRlzXIj.png" height="80%" width="80%" alt=
<br />
<br />
Restart Computer to Complete Server Promotion: <br/>                                                                
<img src="https://i.imgur.com/tAJKSiv.png" height="80%" width="80%" alt=
<br />
<br />             
Verify Server is a Domain Controller in Active Directory Users & Computers (Role Should Now Be Visible): <br/>                                                                
<img src="https://i.imgur.com/vqvGHSh.png" height="80%" width="80%" alt=
<br />
<br />                                 
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
