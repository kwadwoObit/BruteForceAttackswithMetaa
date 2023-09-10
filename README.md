<h1>Brute Force Attack with Metasploit</h1>


<h2>Description</h2>
Project consists of a Brute Force Attack on an open SSH port found after an assessment, this walks you through how metasploit is used to search for SSH, look for auxillary model/ssh_login, set threads, set pass_file, set rhosts, set username, set verbose and run it for execution. 
<br />


<h2> Utilities Used</h2>

- <b>Metasploit</b> 
- <b>Hydra</b>

<h2>Environments Used </h2>

- <b>Kali Linux</b>
- <b>VM Ware</b>


<h2>Program walk-through:</h2>

<p align="center">
Launch Metasploit: <br/>
<img src="https://i.imgur.com/Zpeat7i.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Type "search ssh" and find auxiliary/scanner/ssh/ssh_login:  <br/>
<img src="https://i.imgur.com/eiRsxkP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Type "use auxiliary/scanner/ssh/ssh_login" and then Type Options: <br/>
<img src="https://i.imgur.com/gGr0tJ8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Adjust the various as shown below: <br/>
<img src="https://i.imgur.com/tEbdGRu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Type "run" (may take some time):  <br/>
<img src="https://i.imgur.com/lDBhjLe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
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
