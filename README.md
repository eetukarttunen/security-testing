## My research
[Eetu Karttunen - Web applications and their security testing](https://erepo.uef.fi/handle/123456789/32926?locale-attribute=en)

## Rooted machines

### **Administrator**
- **Description**: Not yet public due to being active machine in the Hack The Box.
- **OS**: Windows 
- **Tools Used**: Nmap, Bash, crackmapexec, netexec, rpcclient, bloodhound, pywhisker, certipy, ftp, targetedGerberos, impacket, Evil-WinRM 
- **Certificate of rooting**: https://www.hackthebox.com/achievement/machine/1605342/634

### **Sightless**
- **Description**: Not yet public due to being active machine in the Hack The Box.
- **OS**: Linux 
- **Tools Used**: Nmap, Bash, Chisel
- **Certificate of rooting**: https://www.hackthebox.com/achievement/machine/1605342/624

### **Instant**
- **Description**:  Not yet public due to being active machine in the Hack The Box.
- **OS**: Linux
- **Tools Used**: Burp Suite, Curl, Nmap, ffuf, Bash
- **Certificate of rooting**: https://www.hackthebox.com/achievement/machine/1605342/630

### **Chemistry**
- **Description**:  Not yet public due to being active machine in the Hack The Box.
- **OS**: Linux
- **Tools Used**: Nmap, ffuf, Bash
- **Certificate of rooting**: https://www.hackthebox.com/achievement/machine/1605342/631

### **Sea**
- **Description**:  Not yet public due to being active machine in the Hack The Box.
- **OS**: Linux
- **Tools Used**: Nmap, ffuf, Bash
- **Certificate of rooting**: https://www.hackthebox.com/achievement/machine/1605342/620

### **Cicada**
- **Description**:  Not yet public due to being active machine in the Hack The Box.
- **OS**: Windows
- **Tools Used**: Nmap, ffuf, Bash
- **Certificate of rooting**: https://www.hackthebox.com/achievement/machine/1605342/627

### **GreenHorn**
- **Description**:  Not yet public due to being active machine in the Hack The Box.
- **OS**: Linux
- **Tools Used**: Nmap, ffuf, Bash
- **Certificate of rooting**: https://www.hackthebox.com/achievement/machine/1605342/617

### **Editorial**
- **Description**:  Not yet public due to being active machine in the Hack The Box.
- **OS**: Linux
- **Tools Used**: Nmap, ffuf, Bash
- **Certificate of rooting**: https://www.hackthebox.com/achievement/machine/1605342/608

### **PermX**
- **Description**:  The "PermX" is a Linux machine featuring a learning management system vulnerable to unrestricted file uploads via CVE-2023-4220. This vulnerability is leveraged to gain a foothold on the machine. Enumerating the machine reveals credentials that lead to SSH access. A `sudo` misconfiguration is then exploited to gain a `root` shell.
- **OS**: Linux
- **Tools Used**: Nmap, ffuf, Bash, curl
- **Certificate of rooting**: https://www.hackthebox.com/achievement/machine/1605342/613

### **BoardLight**
- **Description**: The "Boardlight" is a Linux machine that features a `Dolibarr` CRM instance vulnerable to CVE-2023-30253. This vulnerability is leveraged to gain access as `www-data`. After enumerating and dumping the web configuration file contents, plaintext credentials lead to `SSH` access to the machine. Enumerating the system, a `SUID` binary related to `enlightenment` is identified which is vulnerable to privilege escalation via CVE-2022-37706and can be abused to leverage a root shell.
- **OS**: Linux
- **Tools Used**: Nmap, ffuf, Bash
- **Certificate of rooting**: https://www.hackthebox.com/achievement/machine/1605342/603

### **TwoMillion**
- **Description**: The "TwoMillion" -machine features an old version of the HackTheBox platform that includes the old hackable invite code. After hacking the invite code an account can be created on the platform. The account can be used to enumerate various API endpoints, one of which can be used to elevate the user to an Administrator. With administrative access the user can perform a command injection in the admin VPN generation endpoint thus gaining a system shell. An .env file is found to contain database credentials and owed to password re-use the attackers can login as user admin on the box. The system kernel is found to be outdated and CVE-2023-0386 can be used to gain a root shell.
- **OS**: Linux
- **Tools Used**: Nmap, Netcat, Bash, Curl, de4js
- **Certificate of rooting**: https://www.hackthebox.com/achievement/machine/1605342/547
