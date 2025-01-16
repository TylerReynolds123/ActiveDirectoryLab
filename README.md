<h1>Active Directory Home Lab</h1>

 

<h2>Description</h2>
Project consists of walking through how to create an Active Directory home lab environment using Oracle Virtual Box. Configuring and running this lab will definitely help develop your understanding of how active directory and windows networking works, so I highly recommend running through it a few times, ask questions where things may seem unclear, and eventually try to build your own. Please let me know if you have any questions!
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b>
- <b>Oracle Virtual Box</b>


<h2>Environments Used </h2>

- <b>Windows 10</b> 
- <b>Server 2019</b>

<h2>Program walk-through:</h2>

<p align="center">
Create Virtual Machine Domain Controller (DC): <br/>
<img src="https://i.imgur.com/ecLpPBK.jpg" height="80%" width="80%" alt="VM Steps"/> 
<br />
<br />
Configure Internet and Internal NICs:  <br/>
<img src="https://i.imgur.com/apPkzqr.jpg" height="80%" width="80%" alt="VM Steps"/>
<br />
<br />
Configure IP address settings: <br/>
<img src="https://i.imgur.com/YHd9Ybh.jpg" height="80%" width="80%" alt="VM Steps"/>
<br />
<br />
Add Active Directory to Virtual Machine:  <br/>
<img src="https://i.imgur.com/kQYvXsC.jpg" height="80%" width="80%" alt="VM Steps"/>
<br />
<br />
Created myself as a user:  <br/>
<img src="https://i.imgur.com/JpgYxrQ.jpg" height="80%" width="80%" alt="VM Steps"/>
<br />
<br />
Configure Routing/Remote Access:  <br/>
<img src="https://i.imgur.com/295qODC.jpg" height="80%" width="80%" alt="VM Steps"/>
<br />
<br />
Created users from script:  <br/>
<img src="https://i.imgur.com/hRVrrSL.jpg" height="80%" width="80%" alt="VM Steps"/>
<br />
<br />
Create and Configure "CLIENT1" VM:  <br/>
<img src="https://i.imgur.com/nYs6NgN.jpg" height="80%" width="80%" alt="VM Steps"/>
<br />
<br />
Use the "ping" command to verify internet connectivity/confirm DNS resolution:  <br/>
<img src="https://i.imgur.com/i1WvOiF.jpg" height="80%" width="80%" alt="VM Steps"/>
<br />
<br />
Verify client is in DHCP lease:  <br/>
<img src="https://i.imgur.com/0AgvMw5.jpg" height="80%" width="80%" alt="VM Steps"/>
<br />
<br />
Ensure client is a member of DC: <br/>
<img src="https://i.imgur.com/LBUNYT2.jpg" height="80%" width="80%" alt="VM Steps"/>
<br />
<br />
Verify successful login to mydomain.com: <br/>
<img src="https://i.imgur.com/xlXIanu.jpg" height="80%" width="80%" alt="VM Steps"/>
</p>
