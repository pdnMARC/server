# 🚀 EEE High-Performance Computing  
**University of Peradeniya | Department of Electrical & Electronic Engineering**  

Built for speed, collaboration, and breakthrough AI innovation.  

---

### 🔥🔥🔥 News & Updates
Stay in the loop — server status, maintenance, and repo changes announced here.

03 Feb 2026 — GitHub documentation page refreshed.

---

### 🖥️ COVID-AI Server  

**Codename:** COVID-AI  
**Type:** Elite HPC Beast  
**Mission:** Powering AI/ML training, massive datasets, and groundbreaking experiments  

**Led by:** AI4COVID Research Group  
**Project Hub:** [covid.eng.pdn.ac.lk](https://covid.eng.pdn.ac.lk/)  
**Powered by:** IDRC Grant 109586-001  

This machine is a shared weapon for pushing the boundaries of AI research. Use it wisely. 💪

---

### 📈 Real-Time Dashboard  
Live GPU, CPU, RAM stats — always know when to strike:  
🔗 [cepdnaclk.github.io/servermonitoring](https://cepdnaclk.github.io/servermonitoring/)  

**Pro tip:** Check the dashboard before queuing big jobs. Save time, stay efficient.

---

### 📁 Repo Structure  
```
.
├── admin/   → Runbooks, maintenance, admin secrets
├── faq/     → Quick fixes & common questions
└── specs/   → Full hardware + software breakdown
```

---

### ⚡ Quick Access Guide  

**Access:** Strictly approved only. Every connection is logged.  

**External (Worldwide)**  
- IP: `192.248.40.131`  
- Port: `25692`  

**Internal (Campus Network)**  
- Hostname: `ai4covid.ee.pdn.ac.lk`  

**One-liner Commands**  
```bash
# Jump in from outside
ssh -p 25692 username@192.248.40.131

# Campus login
ssh username@ai4covid.ee.pdn.ac.lk

# Throw files over
scp -P 25692 data.zip username@192.248.40.131:~/

# Big transfers? rsync is your friend
rsync -avz -e "ssh -p 25692" local_folder/ username@192.248.40.131:~/remote_folder/
```

---

### 🔒 Secure & Restricted Zones  

**Never commit secrets here.** Keys, tokens, passwords — keep them off-repo.  

**Admin-Only Vaults**  
- Change Logs & Management: [Private Doc](https://docs.google.com/document/d/1KQQvQHTXUsq2LICX7oSW2EAkTSEX2J9v79jG0pilQVE/edit?usp=sharing)  
- User Registry: [Private Sheet](https://docs.google.com/spreadsheets/d/1Rxvh1ioRFD-KXgWE4U1UdCPTqiQuW3UcW3CTedKsLwk/edit#gid=0)  

Need access? Submit a formal request to the sysadmins.

---

### 🛠️ Support & Maintenance  

Handled by the department’s elite admin crew.  
Issues, new accounts, or scheduled work → check `admin/` folder first, then hit official channels.  

Downtime? We’ll shout it out early.

---

**© 2026 Department of Electrical & Electronic Engineering**  
**University of Peradeniya, Sri Lanka**  

**Built for the future of AI research.**  
Let’s push limits. 🚀🔥

