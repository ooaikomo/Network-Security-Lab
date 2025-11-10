# 🧱 Network Security Setup

## 📘 Lab Concept
This project demonstrates the **design, configuration, and security implementation** of a small multi-department network using **Access Control Lists (ACLs)**.  
It focuses on managing communication between departments, ensuring authorized access, and preventing internal data breaches through proper network segmentation and access control.

---

## 🎯 Objective
To design and secure a structured multi-department network by:
- Implementing **ACLs** on routers to control traffic flow.  
- Allowing **authorized access** between departments while restricting unauthorized communication.  
- Enhancing **data privacy**, **network performance**, and **security posture** through traffic filtering and segmentation.

---

## 🧩 Network Overview
The network consists of three main departments:
- **Admin** — hosts the central web server for resource sharing.  
- **Sales** — allowed to communicate with Admin and access shared web resources.  
- **HR** — restricted to internet-only access for security purposes.  

All departments are connected via a **central router**, with ACLs configured to enforce communication rules between subnets.

---

## 🧠 Key Takeaways
- **Access Control Lists (ACLs)** effectively manage inter-departmental access.  
- **Traffic filtering** ensures only authorized communication occurs.  
- **Segmentation** reduces risk of internal data leaks.  
- Proper ACL configuration improves both **network security** and **efficiency**.  
- Real-world understanding of how ACLs contribute to organizational **data protection** and **network governance**.

---

## ⚙️ Tools & Technologies Used
| Category | Tools |
|-----------|--------|
| **Network Simulation** | Cisco Packet Tracer |
| **Security Configuration** | Extended Access Control Lists (ACLs) |
| **Operating Systems** | Cisco IOS (Router CLI) |
| **Testing & Verification** | Ping Tests, HTTP Access Tests, ACL & Interface Verification Commands |

---

## 📄 File Link
📂 [**View Full Project Report (Network Security.pdf)**](https://drive.google.com/file/d/1S_XBbPNwrg7p4D1i2e_36G5vPgl2aCNn/view?usp=drive_link)

---

## 🚀 Next Steps / Future Improvements
To expand and strengthen this lab in future iterations:
- 🧱 **Integrate VLANs** to enhance segmentation and reduce broadcast domains.  
- 🔐 **Implement Firewalls** for deeper packet inspection and perimeter defense.  
- 📡 **Add Intrusion Detection Systems (IDS/IPS)** to identify and mitigate threats in real-time.  
- 🧠 **Incorporate SIEM Tools** for centralized monitoring and log analysis.  
- ⚙️ **Automate Configuration Backups** and network monitoring using Python scripts.  
- 🌐 **Simulate External Threat Scenarios** to test ACL robustness under attack conditions.  

---

## 🧭 Conclusion
This project highlights how **ACLs** can strengthen network security by limiting unnecessary communication and safeguarding sensitive information.  
Through proper configuration and testing, each department’s access was aligned with its operational needs — achieving a **secure**, **efficient**, and **well-managed** network infrastructure.

---

> *“Every secure network starts with clear boundaries and controlled access.”*  
> — Oluwamuyiwa Aikomo
