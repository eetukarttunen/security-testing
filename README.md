## My research
[Eetu Karttunen - Web applications and their security testing]("https://erepo.uef.fi/handle/123456789/32926?locale-attribute=en")
## Rooted machines
### **TwoMillion**
- **Description**: The Machine features an old version of the HackTheBox platform that includes the old hackable invite code. After hacking the invite code an account can be created on the platform. The account can be used to enumerate various API endpoints, one of which can be used to elevate the user to an Administrator. With administrative access the user can perform a command injection in the admin VPN generation endpoint thus gaining a system shell. An .env file is found to contain database credentials and owed to password re-use the attackers can login as user admin on the box. The system kernel is found to be outdated and CVE-2023-0386 can be used to gain a root shell.
- **OS**: Linux
- **Tools Used**: Nmap, Netcat, Bash, Curl, de4js
- **Certificate of rooting**: https://www.hackthebox.com/achievement/machine/1605342/547
