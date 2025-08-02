# **TLDR+ — lightning‑fast field guides for hands‑on defenders**

> **Be fast. Be accurate. Be useful.**  
> That’s what a SOC analyst (or sysadmin, or pentester) does — and that’s exactly what each TLDR+ volume trains you to be.

**TLDR+** is a lean publishing project that distills real‑world security practice into *compact, tool‑first* books.  
No endless theory. No vendor fluff. Just the commands, workflows, and mental models you need during an incident, a CTF, or a 3 a.m. on‑call shift.

This repository holds **all public assets** for the series — cheatsheets, lab files, update notes — and serves as the main hub for community feedback.  
The full e‑books are released on Amazon Kindle (links below).

---

## 📚 Current releases

| # | Title | Focus area | Amazon link |
|---|-------|------------|-------------|
| 1 | **TLDR+ SOC** | L1/L2 triage, log filtering, incident escalation | [Kindle](https://www.amazon.com/dp/B0F8W7SXJM) |
| 2 | **TLDR+ Linux** | Hardening, auditing, live forensics | [Kindle](https://www.amazon.com/dp/B0FB48198X) |
| 3 | **TLDR+ Networking** | Packet analysis, tunneling, lateral movement | [Kindle](https://www.amazon.com/dp/B0F8P83DDY) |
| 4 | **TLDR+ Cracking** | Password cracking, hashcat optimization, wordlists | [Kindle](https://www.amazon.com/dp/B0F8VT9P1J) |

Each book is **≈120 pages**, designed to be read in an evening and kept open on your second monitor while you work.

---

## 🔍 Sneak peeks

### TLDR+ SOC
A zero‑lecture crash course in Security Operations. Learn to:
* slice logs with `journalctl`, `grep`, and `jq`
* triage alerts with VirusTotal, AbuseIPDB, and MISP
* spot lateral movement, token theft, and PowerShell abuse  
Includes printable flowcharts, enrichment scripts, and “am I dealing with a false positive?” checklists.

### TLDR+ Linux
Everything you wish `man` pages told you: PAM pitfalls, kernel hardening knobs, AppArmor vs. SELinux, eBPF for live response, and disk encryption gotchas. Copy‑paste labs, instant feedback.

### TLDR+ Networking
Packets don’t lie. Master BPF filters in Wireshark/tshark, pivot traffic through SSH & WireGuard, detect covert channels, and replay attacks with the provided `.pcap` set.

### TLDR+ Cracking
From Net‑NTLMv2 to bcrypt. Understand hash families, rainbow‑table math, GPU tuning on cloud rentals, and build your own smart wordlists. Benchmarks and ready‑to‑use dictionaries included.

---

## 🚀 Quick start

```bash
git clone https://github.com/<your‑handle>/tldr-plus.git
cd tldr-plus
