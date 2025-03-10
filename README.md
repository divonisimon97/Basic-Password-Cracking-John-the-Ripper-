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
Create a MD5-crypt hash of a weak password (starburst).: <br/>
<img src="https://i.imgur.com/br8M8TJ.png" height="80%" width="80%" alt="Creating a MD5-crypt hash"/>
<br />
<br />
Save the MD5-crypt hash into a file named fake_hashes.txt: <br/>
<img src="https://i.imgur.com/11IfxkN.png" height="80%" width="80%" alt="Saving the generated hash"/>
<br />
<br />
Run John the Ripper with the RockYou wordlist: <br/>
<img src="https://i.imgur.com/BsSboBx.png" height="80%" width="80%" alt="Analyzing HTTP Traffic"/>
<br />
<br />
Manually View John’s Pot File (optional):  <br/>
<img src="https://i.imgur.com/M6KvCpr.png" height="80%" width="80%" alt="Analyzing HTTP Traffic"/>
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
