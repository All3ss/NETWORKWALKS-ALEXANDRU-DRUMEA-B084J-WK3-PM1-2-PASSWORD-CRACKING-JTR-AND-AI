# NETWORKWALKS-ALEXANDRU-DRUMEA-B084J-WK3-PM1-2-PASSWORD-CRACKING
NetworkWalks Cybersecurity Internship 2026 – Week 3, Project Modules W3-PM1, W3-PM2 & Optional AI-Assisted Labs[cite: 1, 26]. Hands-on experience with password cracking, John the Ripper (JTR), NetworkWalks Dictionary Attack Lab, HexStrike AI MCP, and Claude AI-assisted workflows[cite: 1, 9, 18, 19, 21, 26].

**Performing PDF password hash extraction, dictionary & wordlist attacks, and AI-assisted security workflows in an authorized lab environment**[cite: 1, 5, 6, 7, 9, 13, 14, 22, 23, 26]

![](https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000) ![](https://img.shields.io/badge/Batch-B084J-0070C0?style=flat-square&labelColor=000000) ![](https://img.shields.io/badge/Kali%20Linux-v2026.2-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white) ![](https://img.shields.io/badge/Skill-Password%20Cracking-404040?style=flat-square&labelColor=C00000) ![](https://img.shields.io/badge/Tool-John%20the%20Ripper-238F89?style=flat-square&labelColor=000000) ![](https://img.shields.io/badge/AI%20Workflow-HexStrike%20MCP%20%2B%20Claude-C00000?style=flat-square&labelColor=000000) ![](https://img.shields.io/badge/GitHub-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white) ![](https://img.shields.io/badge/Ethical%20Hacking-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white) ![](https://img.shields.io/badge/Author-Alexandru%20Drumea-C00000?style=flat-square)[cite: 1, 16, 18, 19, 21, 24, 26]

---

## 📌 Project Overview

This project covers the complete practical deliverables of **Week 3** of my Cybersecurity & Ethical Hacking internship at NetworkWalks (Batch **B084J**)[cite: 1, 26].

The objective is to understand password protection mechanisms on encrypted PDF files, practice hash extraction and dictionary/wordlist cracking using **John the Ripper (JTR)** and the **NetworkWalks Dictionary Attack Lab**, and explore AI-assisted workflows by integrating **HexStrike AI (`v6.0.0`)** with **Claude** via **Model Context Protocol (MCP)**[cite: 1, 5, 6, 7, 9, 18, 19, 21, 25].

---

## 🎯 Objectives

The main objectives of this week's modules are to[cite: 1]:

- Extract `$pdf$...` password hashes from encrypted PDF files (`My Locked PDF1.pdf`, `My Locked PDF2.pdf`, `My Locked PDF3.pdf` / `My-Locked-PDF1..3.pdf`) and run password-cracking exercises with **John the Ripper**[cite: 1, 5, 6, 7, 8, 9].
- Execute dictionary attacks in the **NetworkWalks Password Cracker through Dictionary Attacks** lab using the built-in wordlist (`100 passwords`) and analyze password strength[cite: 1, 9, 13, 14, 15].
- Set up **HexStrike AI (`v6.0.0`)** on **Kali Linux** (`git 2.53.0`, `Python 3.13.12`) inside a Python virtual environment (`hexstrike-env`)[cite: 18, 24, 25].
- Connect the local `hexstrike-ai` MCP server (`http://localhost:8888`) to **Claude** (`Sonnet 5.5` / `Sonnet 5`) and verify server health and tool availability[cite: 16, 19, 22, 23, 25].
- Perform an AI-assisted John the Ripper workflow on `hash3.networkwalks_flag1.pdf` (`PDF format 4 / AES-128, revision 4`) using `rockyou.txt` (`9,813 passwords/sec`)[cite: 21, 22, 23].

---

## 🛡️ Scope & Authorization

All password-cracking and AI-assisted testing activities were performed strictly for educational purposes within authorized lab scope[cite: 1, 26]:
- **Target 1:** Encrypted PDF lab files from W3-PM1 (`My Locked PDF1.pdf`, `My Locked PDF2.pdf`, `My Locked PDF3.pdf`)[cite: 1, 5, 6, 7, 8].
- **Target 2:** Encrypted PDF lab files from W3-PM2 (`My-Locked-PDF1.pdf`, `My-Locked-PDF2.pdf`, `My-Locked-PDF3.pdf`) processed in the NetworkWalks Dictionary Attack Lab[cite: 1, 9, 10, 11, 12, 13, 14, 15].
- **Target 3:** Local Kali Linux VirtualBox environment (`kali-linux-2026.2-virtualbox-amd64`) and authorized lab PDF `hash3.networkwalks_flag1.pdf`[cite: 17, 18, 22, 23, 24].

⚠️ **Important:** Password cracking and security testing must always be conducted strictly within authorized scope and with explicit permission[cite: 1, 26].

---

## 🏗️ Modules Completed

| Module ID | Focus Area | Primary Tools & Artifacts |
| :--- | :--- | :--- |
| **W3-PM1** | Password Cracking with John the Ripper (JTR)[cite: 1] | `$pdf$...` hashes (`hash1..txt`, `hash2.txt`, `hash3.txt`), `HASHCRACK.png`, `FLAG 1.jpg`, `FLAG 2 .jpg`, `FLAG 3.jpg`[cite: 2, 3, 4, 5, 6, 7, 8] |
| **W3-PM2** | NetworkWalks Dictionary Attack Lab[cite: 1, 9] | NetworkWalks Dictionary Attack Lab (`100 words`), `CRACKER.jpg`, `NW PASS CRACK.jpg`, `PASSWORD BREAK .jpg`, `FLAG NW 1..3.jpg`[cite: 9, 10, 11, 12, 13, 14, 15] |
| **W3-Optional** | HexStrike AI MCP, Claude & AI-Assisted JTR[cite: 1, 16, 18, 19, 21] | Kali Linux, HexStrike AI `v6.0.0` (`port 8888`), Claude MCP, JTR `1.9.0-jumbo-1+bleeding`, `rockyou.txt`[cite: 18, 19, 20, 21, 22, 24, 25] |

---

## ⚙️ Environment Configuration

| 🧩 Component | ⚙️ Configuration |
| --- | --- |
| 🖥️ Security OS | Kali Linux (`kali-linux-2026.2-virtualbox-amd64` in VirtualBox)[cite: 18, 24] |
| 🐍 Runtime & VCS | `Python 3.13.12`, `git 2.53.0`, virtual environment `hexstrike-env`[cite: 18, 24] |
| 🤖 AI & MCP Integration | Claude (`Sonnet 5.5` / `Sonnet 5`) connected to `hexstrike_mcp.py --server http://localhost:8888`[cite: 16, 19, 22, 23] |
| 🛡️ HexStrike Server | `HexStrike AI v6.0.0` (`60 of 127 tools installed`, `8/8` essential tools operational on `127.0.0.1:8888`)[cite: 20, 25] |
| 🔓 Cracking Toolset | John the Ripper `1.9.0-jumbo-1+bleeding-aec1328d6c` (`/usr/sbin/john`), `pdf2john`, NetworkWalks Dictionary Lab[cite: 9, 21, 23] |
| 📚 Wordlists Used | NetworkWalks built-in list (`100 passwords`) and `rockyou.txt` decompressed to `/tmp/rockyou.txt`[cite: 9, 15, 22] |

---

# 🪜 Activities Performed & Technical Findings

## 1. Password Cracking with John the Ripper (W3-PM1)
- **Hash Extraction:** Extracted `$pdf$4*4*128*-1028*1*...` hashes from `My Locked PDF1.pdf` (`hash1..txt`), `My Locked PDF2.pdf` (`hash2.txt`), and `My Locked PDF3.pdf` (`hash3.txt`, also captured in `HASHCRACK.png`)[cite: 1, 5, 6, 7, 8].
- **JTR Execution:** Ran wordlist cracking against the extracted PDF hashes and verified recovered credentials with `john --show`[cite: 1].
- **Flags Captured:** Obtained `nw{cybersecurity_flag_captured_2608}` (`FLAG 1.jpg`), `nw{networkwalks_persistence_jtr_270521}` (`FLAG 2 .jpg`), and completion evidence in `FLAG 3.jpg`[cite: 2, 3, 4].

## 2. Dictionary Attacks with NetworkWalks Tools (W3-PM2)
- **Lab Workflow:** Loaded `$pdf$...` hashes into **NetworkWalks Password Cracker through Dictionary Attacks** using the built-in wordlist (`Active: built-in list, 100 words`)[cite: 9, 15].
- **Attack Progress & Matches:** Monitored password attempts and cracking rates (`Tried: 35 / 100`, `4 pw/s`, `35%` in `NW PASS CRACK.jpg` and `Tried: 91 / 100`, `9 pw/s`, `91%` in `PASSWORD BREAK .jpg`) with `[+] MATCH` hits against `My-Locked-PDF1.pdf`, `My-Locked-PDF2.pdf`, and `My-Locked-PDF3.pdf`[cite: 1, 13, 14].
- **Flags Captured:** Obtained `nw{networkwalks_flag1_jtr_270521_1}` (`FLAG NW 1.jpg`), `nw{networkwalks_persistence_jtr_270521}` (`FLAG NW 2.jpg`), and `nw{networkwalks_flag_260821_1}` (`FLAG NW 3.jpg`)[cite: 10, 11, 12].

## 3. HexStrike AI MCP, Claude & AI-Assisted JTR (W3-Optional)
- **HexStrike Setup & Server Launch:** Cloned `https://github.com/0x4m4/hexstrike-ai.git`, created `hexstrike-env`, verified `requirements.txt` (`HexStrike AI MCP Agents v6.0`), and started `python hexstrike_server.py --port 8888`[cite: 18, 20].
- **MCP Integration & Health Check:** Configured `hexstrike-ai` in Claude (`Running`) and verified server health (`version 6.0.0`, `operational`, `60 of 127 tools installed`, CPU/memory/disk usage, and telemetry)[cite: 19, 25].
- **AI-Assisted JTR Workflow:** Checked John the Ripper (`/usr/sbin/john`, `1.9.0-jumbo-1+bleeding`), computed file digests (`MD5`, `SHA-1`, `SHA-256`) and extracted the `PDF format 4 (AES-128, revision 4)` hash for `/home/kali/Desktop/hash3.networkwalks_flag1.pdf`, and cracked it in under 2 seconds against `/tmp/rockyou.txt` (`9,813 passwords/sec`) before opening the unlocked PDF[cite: 17, 21, 22, 23].

---

# 🔍 Risk Analysis Summary

| # | Risk / Finding | Potential Impact | Risk Level |
| :--- | :--- | :--- | :--- |
| **1** | Weak & predictable PDF passwords (common / keyboard-walk patterns) | Rapid offline cracking via dictionary attacks and `rockyou.txt` in seconds[cite: 1, 9, 13, 14, 22, 23] | **● High** |
| **2** | Reliance on small default wordlists vs. comprehensive wordlists | Low-complexity passwords fall even to a 100-word list, while larger wordlists speed up recovery[cite: 9, 13, 14, 22] | **● Medium** |
| **3** | Unverified tool availability & MCP command execution | Missing tools (`67/127` not installed) or unvalidated AI-triggered commands can cause failures or unintended actions[cite: 19, 21, 25] | **● Medium** |
| **4** | Exposure of sensitive hashes or recovered secrets in docs/repos | Publishing cracked passwords or sensitive credentials compromises lab hygiene[cite: 1] | **● Low** |

---

# 💡 What I Learned

Through these modules, I gained practical experience in[cite: 1]:
1. **PDF Hash Extraction & JTR:** Extracting `$pdf$...` hashes and using John the Ripper (`--wordlist`, `--show`) to test password strength on encrypted PDFs[cite: 1, 5, 6, 7, 8].
2. **Dictionary Attack Mechanics:** Understanding how wordlists test candidate passwords against a target hash and why predictable passwords fail quickly[cite: 1, 9, 13, 14].
3. **MCP & AI-Assisted Workflows:** Connecting Claude to a local HexStrike MCP server (`port 8888`) to run health checks, inspect tools, and streamline JTR execution[cite: 1, 16, 19, 20, 21, 25].
4. **Defensive Password Hygiene:** Using long, unique, high-entropy passphrases and a password manager to resist dictionary and pattern-based attacks[cite: 1, 22, 23].

---

# 👤 Author

**Alexandru Drumea**[cite: 26]  
Cybersecurity Intern | Batch **B084J**[cite: 1, 26]  

🔗 [LinkedIn Profile](https://www.linkedin.com/in/alex-drumea-7971a8155/)

---

## 📌 Project Information

**Program Name:** Cybersecurity Program at NetworkWalks[cite: 1, 26]  
**Week:** 03[cite: 1]  
**Batch:** B084J[cite: 1, 26]  
**Modules Covered:** W3-PM1, W3-PM2 & W3-Optional (HexStrike MCP + Claude + AI-Assisted JTR)[cite: 1, 16, 18, 19, 21]  
**Repository:** GitHub[cite: 1, 26]
