# Home SOC Lab Deployment

As my journey into the cybersecurity field continues, I have chosen my path to become a **Security Operations Center (SOC) Analyst**. I am deeply interested in analyzing and detecting threats across networks and systems. 

To gain hands-on experience, I have been building a virtualized SOC lab in a home environment using VirtualBox. This repository documents the architecture and setup process.

---

## Lab Architecture & Steps

### 1. pfSense Firewall & Network Setup
* **Platform:** Oracle VM VirtualBox
* **Software:** pfSense
* **Details:** Deployed a virtual machine running pfSense to act as the core firewall and router. Created an isolated internal network and configured IP addresses for the local LAN.

> *[Insert pfSense Screenshots Here]*

---

### 2. Active Directory & Windows Server 2022
* **Platform:** Oracle VM VirtualBox
* **Software:** Windows Server 2022
* **Details:** Deployed a second virtual machine to serve as the domain controller, establishing the Active Directory domain environment for the lab.

> *[Insert Active Directory / Windows Server Screenshot Here]*

---

### 3. Workstation Integration & Lab Finalization
* **Platform:** Oracle VM VirtualBox
* **Software:** Windows 10 / Windows 11
* **Details:** Deployed a client workstation virtual machine, successfully joining it to the internal pfSense network and the Active Directory domain.

> *[Insert Workstation Screenshot Here]*

---

## Next Steps
* Deploying SIEM tools (such as Microsoft Sentinel, Elastic, or Splunk).
* Configuring endpoint monitoring and log collection via Sysmon / Microsoft Defender.
* Simulating and detecting basic network attacks.
