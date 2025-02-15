# <h1>Basic Password Cracking (John the Ripper) </h1>

<h2>Description</h2>
In this project, I focus on a password cracking lab using John the Ripper. The goal is to demonstrate how weak passwords can be cracked and highlight the importance of strong password policies.
<br />


<h2>Languages and Utilities Used</h2>
- <b>John the Ripper </b> (1.9.0) 

<h2>Environments Used </h2>

- <b>Linux</b> (6.11.2)

<h2>Program walk-through:</h2>

<p align="center">
Create a SHA-512 hash of a weak password (starburst).: <br/>
<img src="https://i.imgur.com/4x8eBWc.png" height="80%" width="80%" alt="Creating a SHA-512 hash"/>
<br />
<br />
Save the generated hash into a file named fake_hashes.txt: <br/>
<img src="https://i.imgur.com/QuDGxwL.png" height="80%" width="80%" alt="Saving the generated hash"/>
<br />
<br />
Launch the Website & Enter Login Info: <br/>
<img src="https://i.imgur.com/inuqTYk.png" height="80%" width="80%" alt="Analyzing HTTP Traffic"/>
<br />
<br />
Filter and Inspect HTTP Traffic:  <br/>
<img src="https://i.imgur.com/KTEkYrf.png" height="80%" width="80%" alt="Analyzing HTTP Traffic"/>
<br />
<br />
Locate HTTP POST request: <br/>
<img src="https://i.imgur.com/baJPWiA.png" height="80%" width="80%" alt="Analyzing HTTP Traffic"/>
<br />
<br />
Open HTML Form URL Encoded & Extract Login Credentials:  <br/>
<img src="https://i.imgur.com/RLhXII5.png" height="80%" width="80%" alt="Analyzing HTTP Traffic"/>
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
