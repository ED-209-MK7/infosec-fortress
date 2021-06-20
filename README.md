# infosec-fortress
A python script to turn Ubuntu Desktop in a one stop security platform. The InfoSec Fortress installs the packages,tools, and resources to make Ubuntu 20.04 capable of both offensive and defensive security work.

## Requirements:

+ Written for Ubuntu 20.04. It should be easily modifiable for other versions and distributions.
+ python3
+ git
+ root privileges
+ Approx. 22 Gigs of free space

`sudo apt install python3`

## Steps to run

1. Review the script. No changes needed to get started.
2. (optional) Check list of packages, add, or take away etc.
3. Clone this repository `git clone https://github.com/ED-209-MK7/infosec-fortress.git`
4. Run the script as sudo/root. `sudo python3 ./infosec-fortress/build-fortress.py`
5. (semi-optional) Go make a sandwhich. It takes a long time.
6. Be Prepared to answer some prompts along the way (not many)

This script will make /opt/infosec-fortress. This directory will contain build logs and an update script.

### What Goes into the Fortress?

1. REMnux Reverse Engineering platform
2. SIFT Incident Response Platform
3. Metasploit Framework
4. Kali's Wordlists plus more
5. Kali's Collection of Webshells
6. Kali's Windows Binaries/Resources
7. The latest bloodhound
8. Enum4Linux and Enum4linux-ng

### Notable tools
DFIR Tools
* Log2Timeline (Plaso)
* RegRipper
* msg converter

RE Tools
* Ghidra (Pronounced Ghee-druh (like geek wihtout the k + druh))
* radare2
* binwalk
* look and feel of REMnux (CLI Color Highlighting for filetype)

Security Assessment (PenTest Tools)
* Metasploit Framework
* Burp Suite
* Zap
* nmap
* masscan
* Hashcat
* John
* Hydra
* Medusa
* smbclient /rpcclient
* sqlmap
* netcat-traditional

Other
* VS Code
* Powershell Core

And more...

### To-Do's
* Add a dir containing pre-made host enumeration scripts
* add DPAT (domain password auditing tool)?
* SRUM Dump.py (does it work on Ubuntu?)
* Responder symlink
* add secretsdump.py (might be there already)
* add bettercap
* add Empyre? or similar
* add spider foot community edition
* add Recon-NG
* add Maltego
* test Erik Zimmermans tools in wine
* add a folder in /usr/share/? packed with SANS Posters