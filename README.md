<h1 align="center">🏨 Hotel Management Network Design Using Cisco Packet Tracer</h1>
<p align="center"> Secure Network • VLANs • ACL • DHCP • WPA3 • Firewall • CPS Security </p>

<p align="center">
  <img src="Screenshots/Screenshot 2026-01-31 005714.png" alt="Hotel Management Network Design" width="800">
</p>



<h2>📌 Project Overview</h2>

This project focuses on designing a secure and scalable network for a Hotel Management System using Cisco Packet Tracer.
The network is built using VLANs, routers, switches, wireless access points, servers, CCTV systems, and cyber-security tools.

The design ensures:

✔ Secure guest & staff connectivity

✔ Separation of hotel management systems from guest traffic

✔ Network protection using encryption, ACLs, firewalls & authentication

✔ Reliable, high-performance communication across all hotel departments

<h2>🎯 Objectives</h2>

• Implement a Hotel Management Network using Cisco Packet Tracer

• Configure VLANs for traffic segmentation

• Deploy DHCP, Wi-Fi, Router-on-a-stick, Firewall & ACLs

• Analyze CPS (Cyber Physical System) security vulnerabilities

•Apply mitigation techniques (WPA3, TLS, 802.1X, VPN, ACL rules)

• Ensure network confidentiality, integrity, and availability

<h2>🏢 Network Architecture</h2>

The network includes the following hotel areas:

• 🛎 Reception

• 🏢 Manager Office

• 🛜 Guest Wi-Fi Area

• 🧑‍💼 Staff Floor

• 📶 Wireless Access Points

• 🔐 Server Room

• 🎥 CCTV Surveillance

• 🎤 Conference/Meeting Halls

<h2>🔌 VLAN Configuration</h2>

| VLAN ID | Department / Purpose    |
| ------- | ----------------------- |
| **10**  | Guest Network           |
| **20**  | Staff Network           |
| **30**  | Management / Admin      |
| **40**  | CCTV & Security Devices |

This ensures separate, secure communication and prevents guests from accessing sensitive hotel systems.

<h2>🌐 IP Addressing & Services</h2>

| Service               | Description                   |
| --------------------- | ----------------------------- |
| **DHCP**              | Assigns IPs to all VLANs      |
| **DNS**               | Domain name resolution        |
| **Router-on-a-stick** | Inter-VLAN routing            |
| **WPA2/WPA3 Wi-Fi**   | Secure wireless communication |
| **Firewall**          | Protects network perimeter    |
| **NAT**               | Enables internet access       |

<h2>🛡 Security Measures</h2>

✔ Encryption

• WPA2 / WPA3 wireless security

• TLS / SSL for encrypted communication

✔ Authentication

• RADIUS server

• 802.1X port-based authentication

✔ Access Control Lists (ACLs)

• Prevent Guest VLAN → Admin VLAN

• Allow only authorized staff to access servers

✔ Firewall Security

• Blocks unauthorized inbound/outbound traffic

• Protects internal hotel CPS components

✔ Network Hardening

• SSH for secure device configuration

• SNMPv3 for encrypted monitoring

• MAC filtering on routers/switches

<h2>⚠️ Threats & Vulnerabilities Analysis</h2>

| Threat                  | Description                             |
| ----------------------- | --------------------------------------- |
| **Unauthorized Access** | Guests trying to access admin systems   |
| **MITM Attack**         | Traffic interception risk               |
| **Weak Wi-Fi Setup**    | Vulnerable to password cracking         |
| **DDoS Attacks**        | Overloading hotel servers               |
| **Replay Attacks**      | Reusing previous packets to gain access |

<h2>🛠 Solutions & Mitigation</h2>

• VLAN segmentation

• ACL-based traffic control

• WPA2/WPA3 encryption

• IDS/IPS for network monitoring

• TLS-based encrypted communication

• Implementing VPN for remote access

• Secure routing & firewall policies

<h2>📉 CIA Triad Compliance</h2>

| CIA Principle       | Implementation                                       |
| ------------------- | ---------------------------------------------------- |
| **Confidentiality** | VLANs, ACLs, WPA3, TLS                               |
| **Integrity**       | ACLs, SSL/TLS, hashing                               |
| **Availability**    | Redundant links, stable routing, firewall protection |

<h2>🧪 Testing & Validation</h2>

• Ping test across VLANs

• DHCP IP allocation test

• ACL verification test

• Wi-Fi security test

• Firewall rule validation

• User experience & performance testing

<h2>📂 Folder Structure (Recommended)</h2>

```
Hotel_Management_Network_Design_Using_Cisco_Packet_Tracer/
│
├── Screenshots/
├── .gitattributes
├── Project File.pkt
├── Project Reort.pdf
├── README.md
└── ppt.pptx
```
<h2>📸 Screenshots</h2>

## 📸 Network Topology & Configuration Screenshots


<p align="center">
  <img src="Screenshots/Screenshot%202025-12-07%20105305.png" width="750">
</p>

---


<p align="center">
  <img src="Screenshots/Screenshot%202025-12-07%20105316.png" width="750">
</p>

---

<h2>🏁 Conclusion</h2>

This project successfully demonstrates how to design a secure, scalable, and efficient Hotel Management Network using Cisco Packet Tracer.
It follows proper CPS security practices, network segmentation, and encrypted communication methods.

The network is:

✔ Secure

✔ Reliable

✔ Segmented

✔ Optimized for hotel operations


<h2>👤 Developed By</h2>

```
Rushikesh Sable

📧 rushikeshsable9850@gmail.com
```
