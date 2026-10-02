# Home SOC Lab Deployment

As my journey into the cybersecurity field continues, I have chosen my path to become a **Security Operations Center (SOC) Analyst**. I am deeply interested in analyzing and detecting threats across networks and systems. 

To gain hands-on experience, I have been building a virtualized SOC lab in a home environment using VirtualBox. This repository documents the architecture and setup process.

<img width="1688" height="945" alt="Screenshot (2)" src="https://github.com/user-attachments/assets/f58067c3-139e-4908-8406-3b4f635bd3f7" />


## Lab Architecture & Steps

### 1. pfSense Firewall & Network Setup
* **Platform:** Oracle VM VirtualBox
* **Software:** pfSense
* **Details:** Deployed a virtual machine running pfSense to act as the core firewall and router. Created an isolated internal network and configured IP addresses for the local LAN.

> <img width="715" height="400" alt="Screenshot (3)" src="https://github.com/user-attachments/assets/19d966d3-a212-4c16-b047-7e653ba66844" />


---

### 2. Active Directory & Windows Server 2022
* **Platform:** Oracle VM VirtualBox
* **Software:** Windows Server 2022
* **Details:** Deployed a second virtual machine to serve as the domain controller, establishing the Active Directory domain environment for the lab.

> <img width="1824" height="947" alt="Screenshot (4)" src="https://github.com/user-attachments/assets/e50bae97-b394-4451-bdb1-8681933ae25c" />


---

### 3. Workstation Integration & Lab Finalization
* **Platform:** Oracle VM VirtualBox
* **Software:** Windows 10 / Windows 11
* **Details:** Deployed a client workstation virtual machine, successfully joining it to the internal pfSense network and the Active Directory domain.

> <img width="1580" height="758" alt="Screenshot (5)" src="https://github.com/user-attachments/assets/6214f021-3b60-4a5c-bce8-5a48faab897b" />


