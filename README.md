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

  #### 2.  Download Tools
  - [Oracle VirtualBox](https://www.virtualbox.org/)
  - [Ubuntu ISO](https://ubuntu.com/download/desktop)
  - [Kali Linux ISO](https://www.kali.org/get-kali/)
  - [Autopsy](https://www.sleuthkit.org/autopsy/)
  - [Wireshark](https://www.wireshark.org/)
  - [Metasploitable2 VM](https://sourceforge.net/projects/metasploitable/)

---

#### 3. Installed Oracle VirtualBox and Extension Pack
 
- Installed VirtualBox on host system.
- Installed the Extension Pack for USB and RDP support.
- Launched VirtualBox and confirm it's running.

  
#### 4. Created Virtual Machines

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

---
#### 5. Installing Tools on Ubuntu
To support hands-on analysis and simulation in the cybersecurity lab, essential tools such as Wireshark and Autopsy were installed on an Ubuntu virtual machine. These tools were selected for their relevance in network traffic analysis and digital forensics, respectively.


#### 6. Testing and Simulation  

##### Using Wireshark for Monitoring

- **Wireshark** was installed on Ubuntu to watch and record digital activities.
- Activities between the virtual machines were safely observed and reviewed.
- This helped in understanding how computers communicate and what normal or suspicious activity looks like.

##### Using Autopsy for Investigation

- **Autopsy**, a tool for digital forensics, was used to open and examine data from one of the virtual computers.
- Practiced looking at deleted files, browsing activity, and system behavior.
- This helped build skills for analyzing incidents and tracing activity on a computer.

---

### Screenshots  
Insert screenshot of virtual machines running  
Insert screenshot of successful ping between systems  
Insert screenshot of scan results  
Insert screenshot of traffic captured

##  Documentation and Reporting

Throughout the setup of the cybersecurity lab, thorough documentation was maintained to ensure clarity, consistency, and future reference. Notes, screenshots, and sample reports were created at each stage of the process, capturing tool installation, configurations, and analysis outcomes.

A summary was also prepared to reflect key lessons learned, highlight technical challenges, and outline the skills acquired. All steps were documented in a structured format and organized using **GitHub** as the central platform for version control and presentation.

This documentation supports both personal development and portfolio readiness, demonstrating practical skills and an organized approach to cybersecurity lab 




##  **Conclusion**

Setting up a functional cybersecurity lab provided a solid foundation for exploring key cybersecurity concepts, tools, and practices in a controlled, practical environment. This project successfully established a fully operational virtual lab using open-source and freely available tools such as **Ubuntu Virtual Machine, Wireshark, and Autopsy**, enabling hands-on experience with various aspects of threat detection, digital forensics, and network monitoring.

The lab setup replicated a real-world cybersecurity environment, offering a safe space to test vulnerabilities, analyze malicious activities, and develop incident response techniques without affecting live systems. Through this setup, essential skills were developed, including:

* **Network traffic analysis** using Wireshark
* **Digital forensics investigation** with Autopsy
* **Virtual machine configuration** and OS hardening using Ubuntu
* **Understanding security layers** and system behavior under attack scenarios

Beyond technical skills, the project enhanced critical thinking, attention to detail, and structured reporting—core attributes in any cybersecurity or GRC (Governance, Risk, and Compliance) role.

This lab will continue to serve as a personal training ground for advanced simulations, future certifications, and specialized tracks such as SOC analysis, GRC auditing, or ethical hacking. It demonstrates not only theoretical knowledge but also the practical capability to deploy, manage, and utilize cybersecurity tools effectively.





