
 <h1> OpenVas-Vulnerabilty-Assessment--Metasploitable2-  </h1>



<h2>Description</h2>
This project documents a vulnerability assessment conducted against a Metasploitable 2 virtual machine within an isolated lab environment using OpenVAS and Nmap. The objective was to identify exposed services, validate discovered vulnerabilities, assess risk based on severity and exploitability, and develop practical remediation recommendations following industry-standard vulnerability management practices.


<br />


<h2> Target Goal </h2>
The primary goal of this lab was to understand :

- <b>Perform host discovery and service enumeration.
- <b>Identify vulnerabilities using OpenVAS.
- <b>Prioritize vulnerabilities based on business risk.
- <b>Recommend realistic remediation strategies.
- <b>Document findings in a professional format.


<h2> Actions Performed </h2>
 
- <b>Created a sub-user account on a Linux virtual machine (VMware environment)
- <b>avoided initial password complexity while setting up account 
- <b>Ensured controlled and isolated testing conditions in lab environment set up 
- <b>Accessed the /etc/shadow file ( This step demonstrated Linux secures password storage mechanism using hashed              credentials rather than plaintext)
- <b>Identified and extracted hashed password entries associated with the created user
- <b>Located and decompressed the rockyou.txt wordlist
- <b>Used it as a dictionary input for offline password cracking attempts
- <b>Initiated John the Ripper against the extracted hash file
- <b>Executed dictionary-based attack using the RockYou wordlist
- <b>Monitored cracking progress in real time
  



 <h2> Outcome of Actions and Lessons Learned </h2> 

- <b>The target password was successfully cracked within seconds
 
- <b>Demonstrated high vulnerability of weak passwords against precompiled wordlists
 
- <b>Reinforced the effectiveness of offline attacks where no network detection is involved

This project significantly made me realize :

- <b>Weak passwords are highly vulnerable to dictionary based attacks
- <b>Offline attacks bypass traditional networkbased security monitoring
- <b>MFA significantly reduces risk even if credentials are compromised
- <b>Hashing algorithms must eb secured with "salting' 
- <b>The need for password policies and complexity 
   
<h2>Environments & Tools Used </h2>
- <b> Kali Linux </b>
- <b> Scanner OpenVAS Community Edition </b>
- <b> Metasploitable 2 </b>
- <b> VirtualBox Host-Only Network </b>


<h2>Program walk-through:</h2>

<p align="center">
Installed 'John the Ripper" and created a sub-user on my linux vmware   <br/>
<img src="https://i.imgur.com/rmWRJki.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

 
 <p align="center">
 Identified and extracted hashed password entry associated with the created user from /etc/shadow directory
   <br/>
<img src="https://i.imgur.com/j7Pa4Aa.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

 <p align="center">
 Used it as a dictionary input for offline password cracking attempts & Monitored cracking in real time 
   <br/>
<img src="https://i.imgur.com/s5eiXDp.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
