# Advanced Samba File Server Implementation with Multi Division Access Control

This project implements an enterprise-grade Samba-based file server on Ubuntu Server 22.04 LTS, tailored for organizations with multiple divisions. Designed with a single-server architecture, it includes a full suite of features such as file sharing, user authentication, group-based access control, printer sharing, and advanced security hardening.

---

## Project Goals

- Deploy a centralized Samba file server with single-server architecture
- Enable role-based multi-division access control (IT, HR, Finance, Management)
- Implement granular file and printer permissions per division
- Enforce strong security controls using SSL/TLS and auditing
- Provide monitoring and support automated server backups
- Build and test the infrastructure in a virtualized environment

---

## Key Achievements

- ✅ Robust single-server Samba configuration
- ✅ Multi-division user management and authentication
- ✅ Granular file access permissions per department
- ✅ Printer sharing with group-based access control
- ✅ Security hardening using OpenSSL, TLS, and audit logging
- ✅ Comprehensive monitoring and automated backup strategy

---

## Technical Specifications

### 1️⃣ Hardware Requirements

| Component         | Specification                        |
|------------------|----------------------------------------|
| Host Machine      | Laptop or PC with minimum 8GB RAM     |
| CPU               | Quad-Core Processor with Virtualization |
| Storage           | At least 100GB of free disk space     |
| Network           | Built-in NIC + USB printer (optional) |

### 2️⃣ Software Environment

- 💻 **Hypervisor:** Oracle VirtualBox 7.0+
- 🖥️ **Server OS:** Ubuntu Server 22.04 LTS
- 📂 **Services:** Samba 4.15+, CUPS (for printer sharing)
- 🔐 **Security:** OpenSSL, fail2ban, UFW firewall
- 🔧 **Monitoring & Backup:** cron, rsync, syslog/journalctl

---

## 🏢 Organizational Structure & User Groups
Company Organization:
![Company Organization](https://github.com/user-attachments/assets/8076368a-0e27-446b-9123-99b3f3ecc056)


Users are organized in Linux user groups based on their department, with corresponding directory-level access controls (ACL).

---

🛡️ Network & Security Architecture
## ![Network   Security Architecture](https://github.com/user-attachments/assets/75b1b13c-1998-46d3-9b51-05919da50a8d)

Feel free to fork this repository, submit pull requests, or suggest improvements via issues. All contributions are welcome and appreciated!

---

## Contact

Project developed by:
**Viqram Ananta Wataf**

---

Built for secure collaboration 🚀
