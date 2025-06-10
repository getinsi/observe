# 🛰️ GetInSI Observe – Free Edition

**GetInSI Observe** is a lightweight forensic tool for network and syslog analysis, tailored for IT/OT and SOC environments.

---

### 🚀 Features

- Parse syslog lines (`%ASA-4-106023`, etc.)
- Enrich logs with severity, description, recommendation
- Upload configuration files (.cfg) to extract:
  - Routes
  - Interfaces
  - Device overview
- Visual dashboard: upload, results, export to CSV
- Runs fully offline – no Python required

---

### 📦 Download & Install

👉 [Download the latest installer](https://github.com/getinsi/observe/releases/latest)

🧭 After install:
- App launches at `http://127.0.0.1:8000`
- Upload logs at `/upload`
- See parsed results at `/results`
- Upload configs to see `/overview`, `/routes`, `/interfaces`

---

### 🧠 Built With

- Python + FastAPI
- SQLite local DB
- Jinja2 for UI
- PyInstaller packaging
- Inno Setup for deployment

---

### 📬 Contact

📧 Email: [getinsitools@gmail.com](mailto:getinsitools@gmail.com)  
🌐 Website: [getinsi.com](https://getinsi.com)
