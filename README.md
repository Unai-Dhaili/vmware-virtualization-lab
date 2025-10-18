#  Home Lab — Virtualization with VMware

**Personal lab project simulating a real-world virtualization environment using VMware ESXi 8.0.3 and vCenter Server Appliance (VCSA).**

---

##  Overview
This project documents the deployment and configuration of a full VMware vSphere stack in a nested lab setup.  
It focuses on learning and reproducing realistic infrastructure operations — from host installation and DNS/NTP setup to the attempted deployment and troubleshooting of vCenter Server Appliance.

---

##  Lab Setup

**Host OS:** Windows 11 + VMware Workstation Pro 17  
**Nested Hypervisor:** VMware ESXi 8.0.3  

**Core Components:**
- **ESXi Host:** 192.168.119.150  
- **DNS Server:** Windows Server 2022 — 192.168.119.160  
- **vCenter Server Appliance (VCSA):** 192.168.119.170  
- **Network:** NAT (VMnet8 — 192.168.119.0/24)  
- **Time Sync:** NTP via time.google.com  
- **Storage:** Local SSD (~600 GB, thin provisioned)

---

##  Features Implemented
- ESXi installation and management network setup  
- DNS + reverse lookup configuration (lab.local)  
- NTP synchronization for host and appliances  
- vCenter Server deployment (Stage 1 successful, Stage 2 troubleshooting)  
- Analysis of logs, dependencies, and DNS/NTP issues  
- Full bilingual technical documentation with structured evidence  

---

##  Documentation

Comprehensive technical report (EN & ES) including:
- Step-by-step procedures  
- Troubleshooting logs and conclusions  
- Screenshots and configuration outputs  

 **Download (Spanish PDF):** [Proyecto Técnico(VMware).pdf](https://github.com/user-attachments/files/22987052/Proyecto.Tecnico.VMware.pdf)

 
 **Download (English PDF):** [Technical Project(VMware).pdf](https://github.com/user-attachments/files/22987056/Technical.Project.VMware.pdf)

---

##  Lessons & Takeaways
- Practical understanding of VMware vSphere architecture  
- Critical importance of DNS and NTP in enterprise environments  
- Hands-on troubleshooting of nested virtualization limits  
- Improved documentation and problem-solving workflow  

---

##  Possible Next Steps
- Retry deployment on higher-spec hardware  
- Automate setup using **PowerCLI**  
- Integrate with **Veeam Backup Project** for continuity  

---

##  Tags
`VMware` `vSphere` `ESXi` `vCenter` `SysAdmin` `Infrastructure` `Homelab` `Virtualization` `DNS` `NTP`
