# 🔐 Zero Trust Network Access (ZTNA) Architecture

This project presents the design and implementation of a **Zero Trust Network Access (ZTNA)** architecture as part of my final year project in Cybersecurity Engineering at EPI Digital School.

---

## 📘 Project Overview

Traditional security models rely heavily on perimeter defenses, which are increasingly ineffective against modern threats. **ZTNA** is a modern security approach based on the principle: _"Never trust, always verify."_ This architecture ensures that access to resources is granted only after strict identity verification, regardless of the user’s location.

---

## 🏗️ Architecture Components

- **Firewall Configuration (FortiGate)**  
  Configured NGFW with identity-based policies, application control, and threat protection.

- **Zero Trust Policy Enforcement**  
  Role-based access control (RBAC), device posture checking, and segmentation using Fortinet ZTNA.

- **Identity & Access Management**  
  Integrated Active Directory for centralized authentication and access control.

- **Network Segmentation**  
  Used VLANs and routing on Aruba switch to isolate critical assets.

- **Secure Remote Access**  
  FortiClient used for endpoint posture check and secure tunnel establishment.

---

## 🔧 Technologies Used

- Fortinet FortiGate (NGFW + ZTNA controller)
- FortiClient ZTNA Agent
- Microsoft Active Directory
- Aruba Switches (Layer 3)
- VLANs, DHCP, DNS
- Wireshark (Network diagnostics)
- Windows Server 2019
- Kali Linux (Security testing)

---

## 📂 Project Structure

