<h1>Powershell Active Directory Bulk User Creation</h1>


<h2>Description</h2>
Project consists of a simple of creating bulk user using powershell script<br/>
<br />
<h2>Platforms and Technology Used</h2>

- <b>Virtual Box </b>
- <b>Windows 19 Server</b>


<h2>Lab walk-through:</h2>

<p align="center">
Running Powershell as administrator on Windows 19 server <br/>
<img src="https://i.imgur.com/EENglgf.png" height="80%" width="80%" alt="VB"/>
<br />
<br />
Going to the directory where the list of names are stored in a text file  <br/>
<img src="https://i.imgur.com/7yJOzkV.png" height="80%" width="80%" alt="AD lab"/>
<br />
<br />
Full path directory of the file. <br/>
<img src="https://i.imgur.com/BSKZoIN.png" height="80%" width="80%" alt="AD lab"/>
<br />
<br />
Setting Execution policy to unrestricted. Otherwise script won't be executed.<br/>
<img src="https://i.imgur.com/YHQxwXb.png" height="80%" width="80%" alt="AD lab"/>
<br />
<br />
Powershell script to create users from the list stored in the file named names.txt. This will give a common pass word as Password1 to every user. 
It will take first letter from first name and full last name to create the user name i.e. Prince Milkan will be p.milkan.
This passsword will never expire and will be stored into a Organizational Unit named _USERS
  <br/>
<img src="https://i.imgur.com/FXzr4yL.png" height="80%" width="80%" alt="AD lab"/>
<br />
<br />
Script is being run <br/>
<img src="https://i.imgur.com/C3EgjBc.png" height="80%" width="80%" alt="AD lab"/>
<br />
<br />
Refreshing the OU to see created users <br/>
<img src="https://i.imgur.com/hvHiXfp.png" height="80%" width="80%" alt="AD lab"/>
<br />
<br />
1000+ Users have been created. Prince Milkan is one of them  <br/>
<img src="https://i.imgur.com/yuXMdVn.png" height="80%" width="80%" alt="AD lab"/>
<br />
<br />
We can sign in using pmilkan credentials and password <br/>
<img src="https://i.imgur.com/XoCLyAt.png" height="80%" width="80%" alt="AD lab"/>
<br />
<br />

</p>
