# NIST Incident Response Analysis: French Ministry of Finance
## Applied Framework: NIST SP 800-61 Rev. 3

### 📋 Overview
In Q1 2026, the FICOBA registry was compromised, impacting 1.2M citizens. This case study explores how a NIST-aligned response handles a government-level data breach.

---

### 🔍 Phase 1: Detection & Analysis
The 30-day detection gap highlights a need for:
* **SIEM Correlation:** Detecting the "kill chain" in real-time.
* **DLP Implementation:** Flagging 1.2M records before they leave the network.
* **UEBA:** Monitoring for anomalous administrative behavior.

### 🛡️ Phase 2: Containment, Eradication & Recovery
My proposed 24-hour priority list:
1. **Short-term Isolation:** Severing the exfiltration path.
2. **Credential Resets:** Invalidating compromised administrative keys.
3. **Forensic Capture:** Imaging volatile memory (RAM) for nation-state attribution.

### 📈 Phase 3: Post-Incident Activity
**Lessons Learned:**
* Migration to **Zero-Trust Architecture (ZTA)** is mandatory.
* Balance public transparency with national security by withholding specific technical exploit details while offering citizen support.
* Personal Reflection
* This project was developed as part of my final semester studies at DACC/NMSU. It connects my training in CSEC-283 and preparation for the SecAI+ certification to real-world incident response scenarios.
* 
