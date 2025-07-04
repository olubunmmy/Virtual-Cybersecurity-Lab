# Project Title :Virtual-Cybersecurity-Lab Setup


## Project Overview  
This project documents the step-by-step methodology used to create a fully functional virtual cybersecurity lab using **Oracle VirtualBox**. The lab environment includes tools such as **Wireshark** for packet analysis, **Ubuntu** as the forensic host machine, and **Autopsy** for digital forensics investigations.

This setup is designed for learning, practicing, and demonstrating cybersecurity skills in a controlled and ethical environment.

---


## Objectives  
- Simulate a cybersecurity environment for training  
- Create an isolated virtual lab for cybersecurity testing and analysis.
- Use **Wireshark** to capture and analyze network traffic.
- Perform forensic analysis with **Autopsy** on Ubuntu.
- Practice safe, repeatable security scenarios without impacting the host system.

---

## Tools and Environment  
| Tool           | Purpose                               |
|----------------|----------------------------------------|
| Oracle VirtualBox | Hypervisor to run virtual machines |
| Ubuntu (ISO)   | Base OS for forensic and analysis tools |
| Kali Linux     | Offensive security testing VM          |
| Autopsy        | Digital forensics GUI tool             |
| Wireshark      | Network packet analyzer                |
| DVWA / Metasploitable2 | Vulnerable targets for testing |

### Lab Setup Methodology

#### 1.  Pre-Lab Setup
- Verified system virtualization support  Host System Requirements**:
  - Minimum 8GB RAM (16GB recommended)
  - 100GB free disk space
  - VT-x/AMD-V enabled in BIOS
  - Verified system virtualization support 
- Enabled virtualization in UEFI  
- Installed virtualization software

#### 2. Creating Virtual Machines  
- Created VM for penetration testing  
- Created VM for target system  
- Configured system resources for each machine

#### 3. Network Configuration  
- Created internal or host-only network  
- Assigned static IPs to each VM  
- Verified connectivity using ping

#### 4. Installing Tools  
- Installed port scanning and vulnerability tools  
- Installed traffic analyzers and interception proxies  
- Set up web-based vulnerable applications

#### 5. Testing and Simulation  
- Performed reconnaissance on target  
- Conducted controlled web attacks  
- Captured network traffic for analysis  
- Documented all procedures and results

### Network Diagram  
Insert a labeled diagram showing all virtual machines and their IPs

### Screenshots  
Insert screenshot of virtual machines running  
Insert screenshot of successful ping between systems  
Insert screenshot of scan results  
Insert screenshot of traffic captured

### Project Folder Structure  
virtual-cyber-lab  
├── Screenshots  
├── Configs  
├── README.md  
├── lab-journal.md  
├── tools-reference.md  
├── network-diagram.png

## Outcomes  
- Created and configured a secure virtual lab  
- Demonstrated tool usage and testing methodology    
- Gained foundational cybersecurity experience

## References  
Include manuals, documentation, and websites consulted during setup
