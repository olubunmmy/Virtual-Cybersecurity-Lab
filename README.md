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
  - Verified system virtualization support 
  -  Enabled virtualization in UEFI  

 - **Download Tools**:
  - [Oracle VirtualBox](https://www.virtualbox.org/)
  - [Ubuntu ISO](https://ubuntu.com/download/desktop)
  - [Kali Linux ISO](https://www.kali.org/get-kali/)
  - [Autopsy](https://www.sleuthkit.org/autopsy/)
  - [Wireshark](https://www.wireshark.org/)
  - [Metasploitable2 VM](https://sourceforge.net/projects/metasploitable/)

---

#### 2. Installed Oracle VirtualBox and Extension Pack
 
- Installed VirtualBox on host system.
- Installed the Extension Pack for USB and RDP support.
- Launched VirtualBox and confirm it's running.

  
#### 3. Created Virtual Machines

#####  Ubuntu (Forensics Host)

- **Settings**:
  - RAM: 4096MB
  - Disk: 40GB dynamically allocated
  - Network: Host-Only Adapter

- **Installation**:
  - Booted with Ubuntu ISO.
  - Completed OS setup and installed updates.
    
    
#####  Kali Linux (Attacker Machine)

- RAM: 4096MB
- Disk: 30GB
- Network: Host-Only Adapter
- Tools: nmap 

#####  Metasploitable2 or DVWA (Target Machine)

- RAM: 2048MB
- Disk: Pre-configured image
- Network: Same Host-Only Adapter to allow local traffic

---




#### 4. Network Configuration  
- Created internal or host-only network  
- Assigned static IPs to each VM  
- Verified connectivity using ping

#### 5. Installing Tools  
 Preparing the Virtual Machines

- Ubuntu was used as the main analysis and investigation computer.
- Kali Linux served as the computer to explore and simulate risky behavior.
- Metasploitable2/DVWA acted as the target computer for safe testing scenarios.

---

### 6.Using Wireshark for Monitoring

- **Wireshark** was installed on Ubuntu to watch and record digital activities.
- Activities between the virtual machines were safely observed and reviewed.
- This helped in understanding how computers communicate and what normal or suspicious activity looks like.

---

### 7. Using Autopsy for Investigation

- **Autopsy**, a tool for digital forensics, was used to open and examine data from one of the virtual computers.
- Practiced looking at deleted files, browsing activity, and system behavior.
- This helped build skills for analyzing incidents and tracing activity on a computer.

---

### 8. Practicing Scenarios

- Simulated a basic scenario where one virtual computer interacts with another in a suspicious way.
- Observed the activity with **Wireshark** and documented what was seen.
- Used **Autopsy** to investigate and confirm what had happened by looking into stored data.

---

### 9. Documentation and Reporting

- Notes, screenshots, and sample reports were created throughout the setup.
- A summary was prepared to reflect what was learned.
- All steps were documented for future use and sharing in a portfolio.

---



#### Testing and Simulation  
- Performed reconnaissance on target  
- Conducted forensic analysis  
- Captured network traffic for analysis  
- Documented all procedures and results



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

## Conlusion
- Created and configured a secure virtual lab  
- Demonstrated tool usage and testing methodology    
- Gained foundational cybersecurity experience


