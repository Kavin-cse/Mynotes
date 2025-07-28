 # Day 01
  Introduction to GitHub.
# Day 02
  Download VirtualBox and Kali Linux from it's official websites.
  
  Step 1 : Download VirtualBox.
    
  VirtualBox Official Website:https://www.virtualbox.org
    
  Goto Download → Click on Windows hosts.  (the download will Begin)
    <img width="1919" height="1079" alt="Screenshot 2025-07-20 224107" src="https://github.com/user-attachments/assets/816de49c-4b12-4b34-ad21-51aa985e34fa" />
    After Downloading the file,Click on the file and install the Virtual Machine.
  
  Step 2 : Download Kali Linux. 
    Kali Linux Official Website:https://www.kali.org

   Click on Download → Click Virtual Machines → Click on VirtualBox in the Recommended Session.  (it will download in Compressed Archive Folder)
    <img width="1919" height="1079" alt="Screenshot 2025-07-20 224029" src="https://github.com/user-attachments/assets/19befb0a-2a34-41ec-b6a8-aeefa768e47b" />
  
  Step 3 : Download 7-ZIP Application for unzipping Compressed file without changing it's Signature.
    
  Download using the link:https://www.7-zip.org
  
  Step 4 : Unzip the Compressed Kali File. 
    
Right Click the Zip file → Click on 7-Zip → Click on Extract All or Extract Here.
  
  Step 5 : Open the Folder and Click KaliLinux VirtualBox Machine Definition File.
  <img width="859" height="216" alt="Screenshot 2025-07-20 231845" src="https://github.com/user-attachments/assets/3f3f87b1-3190-4f15-aeb1-250bec37136e" />
  
  Step 6 : Click Start to Boot Kali Linux and Wait for a while.
  <img width="1919" height="1079" alt="Screenshot 2025-07-20 232207" src="https://github.com/user-attachments/assets/0814cd75-1ddc-4ac8-a8db-668f239a914e" />
    Enter the Default Username:kali and Password:kali.
    
Kali Linux Booted Successfully!!!.
  
  ### Some Usual Applications in Kali Linux like,
   + Nmap (network scanning).

   + Wireshark (packet analysis).

   + Metasploit (exploitation).

   + Burp Suite (web testing). 

   + John the Ripper (password cracking).
# Day 03
### Kali Linux Commends
| Commands       | Uses                                      |
| -------------- | ----------------------------------------- |
| cd             | Changes the current directory             |
| ls             | Lists files and directories               |
| mkdir          | Creates a new directory                   |
| rmdir          | Removes an empty directory                |
| pwd            | Prints the current working directory path |
| clear          | Clears the terminal screen                |
| exit           | Logs out from terminal                    |
| ifconfig       | View network interface details            |
| sudo su        | Enters into root directory                |
### Difference between ls -l and ls -lh.
| Command  | File Size Display            | Use When You Need To    |
| -------- | ---------------------------- | ----------------------- |
| ls -l    | Bytes (raw numbers)          | See exact size in bytes |
| ls -lh   | Human-readable (e.g. 2K, 1M) | Understand size quickly |
---
### Introduction to Windows Hacking.
# Day 04
# VirtualBox Network Adapters for Kali Linux
<img width="500" height="290" alt="Screenshot 2025-07-28 180103" src="https://github.com/user-attachments/assets/9b891f20-afe8-4b59-925d-97329683d0d8"  />

## 1. NAT (Network Address Translation)
- Default adapter, provides internet through host
- VM gets IP from VirtualBox DHCP (10.0.2.x)
- One-way access (VM to internet only)

## 2. NAT Network

- Like NAT but VMs can communicate with each other
- Shared network between VMs
- Internet access through host

## 3. Bridged Adapter
- VM appears as physical device on network
- Gets IP from router DHCP
- Full network access, best for pentesting

## 4. Internal Network
- VMs communicate only with each other
- No internet or host access
- Completely isolated environment

## 5. Host-only Adapter
- Network between host and VMs only
- Host virtual adapter (192.168.56.1)
- No internet unless combined with another adapter

## 6. Generic Driver
- For advanced scenarios (UDP tunnels, VDE)
- Rarely used

## 7. Not Attached
- Adapter installed but disconnected
- No network connectivity

## Common Kali Configurations
- **Bridged**: Real network testing
- **NAT + Host-only**: Internet + host access
- **Internal**: Isolated lab environments
### Static IP Address

A **static IP address** is a fixed IP address that is manually assigned to a device or network interface. It does **not change** over time. This address remains constant until it is manually changed by a network administrator.

- **Usage:** Commonly used for servers, network devices, and equipment requiring permanent, consistent network communication (like web servers, mail servers, and routers).

### Dynamic IP Address

A **dynamic IP address** is automatically assigned to a device by a DHCP (Dynamic Host Configuration Protocol) server. This address can **change** each time the device connects to the network or periodically, depending on network policies.

- **Usage:** Ideal for home users, mobile devices, or large networks where devices connect/disconnect frequently.

#### Summary Table

| Properties    | Static IP                   | Dynamic IP                    |
|---------------|----------------------------|-------------------------------|
| Assignment    | Manual                     | Automatic (via DHCP)          |
| Changes?      | No—it stays constant       | Yes—can change periodically   |
| Use Cases     | Servers, printers, routers | Most workstations, home users |
| Management    | More setup/maintenance     | Easier, less admin effort     |
## Payload
In cybersecurity, a **payload** is the part of a malicious program (malware) that performs the intended harmful actions after infecting a system. The payload is distinct from the code used to deliver or spread the malware. 

For example, in a virus or trojan, the payload might:
- Steal data or passwords
- Delete or encrypt files (as in ransomware)
- Open backdoors for attackers
- Display malicious messages

Essentially, the payload is the actual "attack" or effect that a cybercriminal wants to achieve after the malware has reached its target.

## Types of Protocol
| Protocol Type            | Example Protocols                      | Primary Purpose                               |
|--------------------------|--------------------------------------|----------------------------------------------|
| **Communication Protocols** | TCP/IP, HTTP, FTP, SMTP              | Enable data transfer and communication       |
| **Transport Protocols**    | TCP, UDP                             | Manage reliable or fast data delivery         |
| **Network/Internet Layer** | IP, ICMP, ARP                       | Addressing, routing, error handling           |
| **Security Protocols**     | SSL/TLS, SSH, IPsec                  | Secure data transmission and access           |
| **Application Layer**      | DNS, DHCP, SNMP                     | Name resolution, configuration, management   |
| **Wireless/IoT Protocols**| Bluetooth, Zigbee, CAN               | Short-range device communication and automation|
## Some of Information Gathering Websites
1.Web Archive ( https://web.archive.org/ )
- Archives and displays past versions of websites, preserving internet history.
- Allows users to view how websites looked at different times.

2.HaveIBeenPwned ( https://haveibeenpwned.com/ )
 - Checks if your email or personal data was exposed in known data breaches.
 - Allows quick lookup of compromised accounts and notifies about future breaches.

3.WeakPass ( https://weakpass.com/ )
- It offers large collections of password wordlists used by security pros for penetration testing and password cracking.
- It has a tool to generate custom wordlists with variations to improve password guessing.
# 🔍 Nmap and Its Commands

Nmap (Network Mapper) is an open-source tool used for network discovery, security scanning, and auditing. It helps administrators and cybersecurity pros find devices, detect open ports, identify running services and operating systems, and assess vulnerabilities.

## 🌟 What Does Nmap Do?
- 🕵️‍♂️ **Host discovery:** Find live hosts on a network.
- 🚪 **Port scanning:** Identify open ports and services.
- 🛠️ **Service/version detection:** Discover running applications and versions.
- 💻 **OS detection:** Guess the operating system of target devices.
- ⚠️ **Vulnerability scanning:** Identify potential weaknesses using scripts and plugins.

## 📋 Common Nmap Commands

| Command Example                       | Purpose                                                      |
|---------------------------------------|--------------------------------------------------------------|
| `nmap [target]`                       | Scan a single IP or hostname for open ports.                 |
| `nmap -p 80,443 [target]`             | Scan specific ports (e.g. 80 and 443).                       |
| `nmap -p 1-1000 [target]`             | Scan a range of ports (1 to 1000).                           |
| `nmap -A [target]`                    | ⚡ Aggressive scan: OS, version detection, script scan, traceroute. |
| `nmap -sV [target]`                   | 🛠️ Detect versions of services on open ports.                 |
| `nmap -O [target]`                    | 💻 Detect operating system type.                             |
| `nmap -sS [target]`                   | 🕵️‍♂️ Stealth/SYN scan ('half-open' scan).                    |
| `nmap -Pn [target]`                   | 🚫 Scan without pinging (treat all hosts as up).              |
| `nmap -iL list.txt`                   | 📄 Scan hosts listed in a file.                              |
| `nmap -oN scan.txt [target]`          | 💾 Save output in normal format to a file.                   |
| `nmap --script http-enum [target]`    | 📝 Use NSE script to enumerate web resources.                 |


