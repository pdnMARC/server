# 🚀 Department of Electrical and Electronic Engineering  
## Computing Infrastructure & Research Servers  
**University of Peradeniya, Sri Lanka**

> _A centralized, well-maintained reference for departmental high-performance computing resources._  
> _Designed for clarity, professionalism, and ease of use._

---

## 📌 About This Repository

This repository documents the computing servers owned, operated, and maintained by the **Department of Electrical and Electronic Engineering (EEE)** at the University of Peradeniya.

It acts as the **single source of truth** for:
- Server access information  
- Hardware and software specifications  
- Operational policies and best practices  
- Administrative and maintenance references  

**Intended audience:**  
Authorized researchers, postgraduate students, faculty members, and system administrators.

---

## 🖥️ COVID-AI Server

**Server Identifier:** COVID-AI Server  
**Category:** High-Performance Compute (HPC)  
**Primary Role:** AI / ML training, large-scale data processing, and experimental research  

**Hosting Research Group:** AI4COVID Research Group  
**Project Website:** https://covid.eng.pdn.ac.lk/  
**Funding Agency:** International Development Research Centre (IDRC)  
**Grant Number:** 109586-001  

The COVID-AI Server is a **shared departmental asset** dedicated to advancing AI-driven research and interdisciplinary collaboration.

---

## 📊 Live Resource Monitoring

System health and utilization metrics (GPU, CPU, memory) are publicly visualized via the departmental monitoring portal:

https://cepdnaclk.github.io/maintenance/reports/server-gpu-util/plots/ee/

Users are strongly encouraged to review utilization trends before launching compute-intensive jobs.

---

## 🗂️ Repository Layout

```
.
├── admin/   → Administrative procedures, runbooks, and maintenance notes
├── faq/     → User-facing FAQs and common troubleshooting steps
└── specs/   → Detailed hardware & software specifications
```

⚠️ **Security Notice:**  
Credentials, private keys, tokens, or sensitive data must never be committed to this repository.

---

## 🔐 Internal Records (Restricted)

The following documents are maintained separately and are accessible **only to authorized personnel**:

- **Management & Change Logs**  
  https://docs.google.com/document/d/1KQQvQHTXUsq2LICX7oSW2EAkTSEX2J9v79jG0pilQVE/edit?usp=sharing

- **User Account Registry**  
  https://docs.google.com/spreadsheets/d/1Rxvh1ioRFD-KXgWE4U1UdCPTqiQuW3UcW3CTedKsLwk/edit#gid=0

Requests for access must be formally directed to the system administrators.

---

## 🔗 Server Access & Connectivity

Access is granted **only after formal approval**. All connections are logged and monitored.

### 🌍 External Access
- **Public IP:** 192.248.40.131  
- **SSH Port:** 25692  

### 🏫 Internal Access (Faculty Network)
- **Hostname:** ai4covid.ee.pdn.ac.lk  

### 🔑 Connection Examples

```bash
# External login
ssh -p 25692 <username>@192.248.40.131

# Internal login (faculty Wi-Fi)
ssh <username>@ai4covid.ee.pdn.ac.lk

# Secure file transfer
scp -P 25692 dataset.tar.gz <username>@192.248.40.131:~/
```

For large data transfers, `rsync` is recommended.

---

## 🛠️ Administration & Support

Server administration and maintenance are handled by designated departmental personnel.

For:
- Access requests  
- Technical issues  
- Maintenance coordination  

Please refer to documentation under `admin/` or contact the administrators via official departmental channels.

Planned maintenance windows will be announced in advance whenever feasible.

---

## 🧾 Change Tracking

All significant configuration updates, policy changes, and maintenance activities must:
- Be recorded in the management logs  
- Be reflected in this repository where applicable  

Example:
```
2026-01-31  Initial formal README published
2026-02-08  Added monitoring and access policy refinements
```

---

© Department of Electrical and Electronic Engineering  
University of Peradeniya, Sri Lanka  
_Official departmental computing documentation_
