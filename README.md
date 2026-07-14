
 <h1> OpenVas-Vulnerabilty-Assessment--Metasploitable2-  </h1>



<h2>Description</h2>
This project documents a vulnerability assessment conducted against a Metasploitable 2 virtual machine within an isolated lab environment using OpenVAS . The objective was to identify exposed services, validate discovered vulnerabilities, assess risk based on severity and exploitability, and develop practical remediation recommendations following industry standard vulnerability management practices.


<br />


<h2> Target Goal </h2>
The primary goal of this lab was to understand :

- <b>Perform host discovery and service enumeration.
- <b>Identify vulnerabilities using OpenVAS.
- <b>Prioritize vulnerabilities based on business risk.
- <b>Recommend realistic remediation strategies.
- <b>Document findings in a professional format.


<h2> Actions Performed </h2>
 
- <b>Verified network connectivity.
- <b>Performed service enumeration with Nmap. 
- <b>Created and configured OpenVAS  alongside its  scan target.
- <b>Executed a Full and Fast scan.
- <b>Reviewed vulnerability findings.
- <b>Prioritized vulnerabilities by severity and exploitability.
- <b>Developed remediation recommendations.
- <b>Validated findings against exposed services.
  



 <h2> Outcome of Actions  </h2> 

- <b>This vulnerability assessment successfully identified multiple security weaknesses across the Metasploitable 2 virtual machine using OpenVAS, with findings validated through service enumeration using Nmap where appropriate. The assessment uncovered vulnerabilities ranging from critical remote code execution flaws and insecure default configurations to authentication weaknesses and outdated cryptographic protocols.

- <b>To provide a realistic representation of a professional vulnerability management process, findings were prioritized according to severity, exploitability, and potential business impact rather than documenting every detected vulnerability. This approach enabled the development of targeted remediation recommendations for the most significant risks while demonstrating the importance of risk-based prioritization over vulnerability volume.

---Overall, the project reinforced the value of combining automated vulnerability scanning with manual validation to produce accurate, actionable security findings.

<h2> Lessons Learned </h2>
- <b>Vulnerability scanners significantly accelerate the discovery process but should not be relied upon without validation, as false positives and duplicate findings may occur.
 
- <b>Effective vulnerability management extends beyond identifying weaknesses; it requires understanding the associated business risk, validating findings, and prioritizing remediation efforts.

- <b>Outdated software and insecure default configurations remain among the most common causes of critical security exposures

- <b>Cross-validating OpenVAS findings with Nmap improved confidence in detected services and demonstrated the importance of using multiple tools during an assessment

- <b>documentation is an essential component of vulnerability management, enabling technical findings to be communicated clearly to both technical teams and management

  This project significantly made me realize :

-that vulnerability management is an ongoing process rather than a one-time scan. Identifying vulnerabilities is only the first step; validating findings, assessing risk, implementing remediation, and continuously reassessing systems are equally critical to maintaining a strong security posture.

   
<h2>Environments & Tools Used </h2>
- <b> Kali Linux </b>
- <b> Scanner OpenVAS Community Edition </b>
- <b> Metasploitable 2 </b>
- <b> VirtualBox Host-Only Network </b>


<h2>Program walk-through:</h2>

<p align="center">
Installed OpenVas and ran Full scan on Metasploitable 2  <br/>
<img src="https://i.imgur.com/lFncVFj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

 

 <p align="center">
 Vulnerabilty Scan result 
   <br/>
<img src="https://i.imgur.com/Jupeaaa.png"' height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

 <p align="center">
 Vulnerabilty Scan result for VSFTPD 2.3.4 Compromised Source Package Backdoor
   <br/>
<img src="https://i.imgur.com/CBmfE6t.png' height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


 <p align="center">
 Vulnerabilty Scan result for Apache Tomcat 'Ghostcat' (AJP) Remote Code Execution
   <br/>
<img src="https://i.imgur.com/8brR5jU.png' height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

 <p align="center">
 Vulnerabilty Scan result for TWiki < 4.2.4 Multiple XSS / Command Execution Vulnerabilities
   <br/>
<img src="https://i.imgur.com/69Glhmg.png' height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<p align="center">
 Vulnerabilty Scan result for TWiki < 4.2.4 Multiple XSS / Command Execution Vulnerabilities
   <br/>
<img src="https://i.imgur.com/69Glhmg.png' height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


