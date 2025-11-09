# 🧩 Lab Title

> **Category:** (e.g., Network Forensics / Log Analysis / Detection Engineering)  
> **Platform:** (BTLO / TryHackMe / Self-Hosted / Other)  
> **Date Completed:** YYYY-MM-DD  
> **Difficulty:** 🟩 Beginner | 🟨 Intermediate | 🟥 Advanced  

---

## 🎯 Objective

Briefly describe the **main goal** of the lab.  
What skills or concepts were being practiced?

> Example:  
> Analyze HTTP traffic in a PCAP to identify malicious beaconing and understand data exfiltration patterns.

---

## ⚙️ Tools & Environment

List the tools, scripts, or datasets used during the exercise.

| Tool | Purpose |
|------|----------|
| Wireshark | Packet inspection |
| Zeek | Log extraction |
| Sigma | Rule creation |
| PowerShell | Log filtering & automation |

---

## 🧠 Methodology

Step-by-step description of your **approach and reasoning** — not exact answers or flags.  
Focus on **how** you analyzed, correlated, or detected suspicious activity.

> Example:  
> 1. Imported PCAP into Wireshark and applied filters for `dns` and `http`.  
> 2. Identified periodic requests to an external IP.  
> 3. Validated C2 pattern with Zeek logs and pivoted to host-level artifacts.

---

## 🧩 Key Findings

Summarize what you discovered or confirmed during the lab.

- Suspicious communication pattern identified between internal host and unknown IP.  
- Detection opportunity for periodic beaconing via Sigma rule.  
- PowerShell script created to extract timeline of relevant events.

---

## 🧰 Custom Scripts or Rules

If applicable, include or link to any custom **scripts, rules, or automation** you built.

> Example:  
> - [pslog-timeline.ps1](../scripts/pslog-timeline.ps1) — Extracts event log timeline for specific host  
> - [sigma_http_beacon.yml](../detections/sigma_http_beacon.yml) — Sigma rule for outbound periodic HTTP traffic  

---

## 📚 Lessons Learned

Reflect briefly on what you improved or learned technically or methodologically.

> Example:  
> Improved my understanding of Zeek log correlation and Sigma rule testing within a simulated SOC workflow.

---

## 🛡️ Ethical Notice

> ⚠️ This write-up is for **educational purposes only**.  
> It does **not** include proprietary material, solutions, or active challenge content.  
> Focus is on methodology and learning — not disclosure of lab answers.

---
