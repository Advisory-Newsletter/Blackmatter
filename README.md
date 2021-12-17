# Blackmatter-Ransomware
Related IOC, Mitigation steps, and reference links

Common Vulnerabilities and Exposures (CVE) : CVE-2021-21985, CVE-2021-37973 

IOCs(Indicators of compromise)

PAYLOADS: 
6a7b7147fea63d77368c73cef205eb75d16ef209a246b05698358a28fd16e502 
d4645d2c29505cf10d1b201826c777b62cbf9d752cb1008bef1192e0dd545a82 

SHA256 Hashes :
072158f5588440e6c94cb419ae06a27cf584afe3b0cb09c28eff0b4662c15486 
20742987e6f743814b25e214f8b2cd43111e2f60a8856a6cca87cafd85422f41 
22d7d67c3af10b1a37f277ebabe2d1eb4fd25afbd6437d4377400e148bcc08d6 
2c323453e959257c7aa86dc180bb3aaaa5c5ec06fa4e72b632d9e4b817052009 
2e50eb85f6e271001e69c5733af95c34728893145766066c5ff8708dcc0e43b2 
4be85e2083b64838fb66b92195a250228a721cdb5ae91817ea97b37aa53f4a2b 
5da8d2e1b36be0d661d276ea6523760dbe3fa4f3fdb7e32b144812ce50c483fa 
668a4a2300f36c9df0f7307cc614be3297f036fa312a424765cdb2c169187fe6 
6d4712df42ad0982041ef0e2e109ab5718b43830f2966bd9207a7fac3af883db 
706f3eec328e91ff7f66c8f0a2fb9b556325c153a329a2062dc85879c540839d 
7f6dd0ca03f04b64024e86a72a6d7cfab6abccc2173b85896fc4b431990a5984 
9cf9441554ac727f9d191ad9de1dc101867ffe5264699cafcf2734a4b89d5d6a 
b0e929e35c47a60f65e4420389cad46190c26e8cfaabe922efd73747b682776a 
c6e2ef30a86baa670590bd21acf5b91822117e0cbe6060060bc5fe0182dace99 
e4a2260bcba8059207fdcc2d59841a8c4ddbe39b6b835feef671bceb95cd232d 
eaac447d6ae733210a07b1f79e97eda017a442e721d8fafe618e2c789b18234b 
eafce6e79a087b26475260afe43f337e7168056616b3e073832891bf18c299c1 
f32604fba766c946b429cf7e152273794ebba9935999986b7e137ca46cd165fc 
  
MITIGATION
—	Disable the storage of clear text passwords in LSASS memory.
—	Consider disabling or limiting New Technology Local Area Network Manager (NTLM) and WDigest Authentication.
—	Implement Credential Guard for Windows 10 and Server 2016.
—	Disable command-line and scripting activities and permissions. Privilege escalation and lateral movement often depend on software utilities that run from the command line.
—	Implement and enforce backup and restoration policies and procedures. Doing backups right is not as easy as some may think. Make sure they are recent, cannot be altered or deleted, and cover the entire organization’s data infrastructure.
—	Minimize the Active Directory (AD) attack surface to reduce malicious ticket-granting activity. Ticket Granting services can be used to obtain hashed credentials that attackers attempt to crack or use in pass-the-hash methods.

Reference link

1	https://www.mandiant.com/resources/cryptography-blackmatter-ransomware

2	https://www.bing.com/search?q=BlackMatter%3A+New+Data+Exfiltration+Tool+Used+in+Attacks+%7C+Symantec+Blogs+(security.com)&cvid=b84f6db973af48d2bb8d6c062a40ff06&aqs=edge..69i57j69i58.1306j0j1&FORM=ANAB01&PC=U531

3	https://www.darkreading.com/threat-intelligence/who-is-blackmatter-researchers-piece-together-new-threat-group 

4	https://www.cisa.gov/uscert/ncas/alerts/aa21-291a 

5	https://www.securityweek.com/us-government-issues-urgent-warning-blackmatter-ransomware?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+securityweek+%28SecurityWeek+RSS+Feed%29 

6	https://threatpost.com/blackmatter-ransomware-dark/175955/ 

7	https://www.securityweek.com/blackmatter-ransomware-gang-announces-shutdown?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+securityweek+%28SecurityWeek+RSS+Feed%29 

8	https://www.cpomagazine.com/cyber-security/us-federal-agencies-issue-a-joint-cybersecurity-advisory-over-blackmatter-ransomware-targeting-critical-infrastructure-entities-and-food-organizations 

9	https://www.mandiant.com/resources/cryptography-blackmatter-ransomware 

10	https://www.securitymagazine.com/articles/95744-blackmatter-and-haron-ransomware-groups-emerge-after-darkside-and-revil-disappear 
