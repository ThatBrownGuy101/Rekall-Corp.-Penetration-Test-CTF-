# Rekall Corp. Penetration Test (CTF)   (Need to add Report)

## Objective
The objective of this project was to assume the role of Penetration Tester and conduct a comprehensive penetration test for a fictional company, Rekall Corporation, focusing on identifying vulnerabilities across their web application, Linux servers, and Windows servers. The goal was to assess the overall security of Rekall’s infrastructure and provide actionable insights on how to mitigate discovered vulnerabilities. This project involved offensive security techniques, vulnerability scanning, and exploitation, culminating in a detailed report of findings and recommendations to improve the company's cybersecurity defenses ahead of its business launch.

### Skills Learned
- Web Security: Finding and exploiting web app vulnerabilities like SQL injection and XSS.
- Linux Security: Scanning and exploiting weaknesses on Linux servers.
- Windows Security: Testing and exploiting vulnerabilities on Windows systems.
- Network Scanning: Using Nmap to find hosts and open ports.
- Vulnerability Scanning: Using Nessus to identify security issues.
- Exploitation Tools: Using Metasploit to exploit vulnerabilities.
- Password Cracking: Cracking passwords with tools like John the Ripper.
- Privilege Escalation: Gaining higher-level access on compromised machines.
- Lateral Movement: Navigating the network after initial access.
- Report Writing: Documenting findings and suggesting fixes.

### Tools Used
- Kali Linux: Used as the primary operating system for conducting penetration tests.
- Nmap: For network scanning and discovering hosts and open ports.
- Nessus: For vulnerability scanning and assessment of security issues.
- Metasploit: For exploiting identified vulnerabilities and conducting penetration tests.
- MSFconsole: The command-line interface for the Metasploit framework.
- John the Ripper: For cracking passwords and retrieving credentials.
- Burp Suite: For testing web applications and finding vulnerabilities.
- BloodHound: For active reconnaissance on Windows networks.
- Curl: For transferring data with URLs and making HTTP requests.

## Walkthrough
Assuming the role of a penetration tester hired by Rekall Corporation, I was tasked with identifying vulnerabilities across their technical infrastructure in preparation for the company’s upcoming business launch. The project was divided into three key parts, each focusing on different aspects of Rekall's system: their web application, Linux servers, and Windows servers. The three parts are interconnected, as vulnerabilities discovered in each could impact the overall security posture of the company.

Part 1: Attacking the Web Application
I began by targeting Rekall's newly developed web application, which is central to their virtual reality business. The goal was to find vulnerabilities that could potentially expose sensitive user data or allow unauthorized access to the platform. Using various offensive security techniques, I uncovered multiple vulnerabilities hidden as “flags” across the application, which helped me identify weaknesses in the application's security mechanisms. Exploiting these vulnerabilities provided insights into how external attackers might manipulate the application.

Part 2: Attacking the Linux Servers
Building on the web application assessment, I next focused on Rekall’s Linux servers. These servers are crucial for managing the company’s backend operations. Here, I used tools like Nessus and Nmap to scan for misconfigurations and weaknesses in the Linux operating systems. During this phase, I discovered and exploited vulnerabilities, leading to further insights into how Rekall’s infrastructure could be compromised through lateral movement from the web application to the server environment.

Part 3: Attacking the Windows Computers
The final phase involved assessing Rekall’s Windows infrastructure. Using the Kali Linux machine as the attack platform, I identified vulnerabilities in the Windows servers that could be exploited for further network infiltration. As with the previous phases, I located "flags" that signified successful exploitation of the system. These Windows-based vulnerabilities, such as weak password policies or outdated software, represented potential risks to the company’s overall network security.

By addressing vulnerabilities across the web application, Linux servers, and Windows servers, this project provided a comprehensive understanding of Rekall's security posture, highlighting the importance of securing all elements of a company’s technical infrastructure to prevent exploitation and potential breaches.




