🕵️‍♂️ From Sysadmin to DFIR Specialist

This repository documents my 6-month practical journey from working as a system administrator in cybersecurity to becoming a Digital Forensics & Incident Response (DFIR) specialist.The goal: move beyond log monitoring and into evidence-based investigation and technical storytelling.

🎯 Objective

To build solid, hands-on skills in:

Memory forensics (RAM dumps)

Disk and artifact analysis

Network traffic reconstruction (PCAP, Zeek)

Malware behavior and persistence investigation

Incident reconstruction and timeline creation

📂 Structure

.
├── month-1/               # Fundamentals & Zeek traffic analysis
├── month-2/               # Static & behavioral malware analysis
├── month-3/               # Memory forensics & log correlation
├── month-4/               # Malware execution & persistence
├── month-5/               # Incident simulation & attack reconstruction
├── month-6/               # Portfolio finalization & career planning
└── docs/                  # Shared notes, templates, reports

🧪 Learning Materials Used

📘 Practical Malware Analysis – Sikorski & Honig

📘 The Practice of Network Security Monitoring – Richard Bejtlich

📘 The Art of Memory Forensics – Ligh et al.

🧠 Labs from TryHackMe, DFIR.training, malware-traffic-analysis.net

🧰 Tools: Zeek, Volatility, PEStudio, Ghidra, Procmon, Detect It Easy, FLARE VM, Cuckoo Sandbox

🗓️ 6-Month Training Plan

📅 Month 1 – Fundamentals & Network Traffic Analysis

Goal: Build investigation mindset and understand forensic workflows.

Study:

Practical Malware Analysis – Chapters 1–4 (static analysis)

The Practice of Network Security Monitoring – Zeek intro

Labs:

TryHackMe: "Intro to Malware Analysis", "Zeek"

PCAPs from malware-traffic-analysis.net analyzed with Zeek

✅ Deliverable:

GitHub write-up: Zeek PCAP analysis + notes

📅 Month 2 – Static & Behavioral Malware Analysis

Goal: Understand suspicious executables and their behavior.

Study:

Practical Malware Analysis – Chapters 5–10

"Windows Internals for RE" – OpenSecurityTraining.net

Labs:

Set up FLARE VM

Use PEStudio, Detect It Easy, Procmon, Regshot

Analyze 2 malware samples (sandboxed)

✅ Deliverable:

Malware behavior sheet: characteristics, persistence, indicators

📅 Month 3 – Memory Forensics & Log Correlation

Goal: Combine memory analysis with traffic/log analysis.

Study:

Volatility Framework docs

DFIR blogs (Andrea Fortuna, local case studies)

Labs:

RAM image from dfir.training

Volatility modules: pslist, netscan, malfind, dlllist

Cross-reference with Zeek or Wireshark

✅ Deliverable:

GitHub post: "IR case study: RAM + PCAP + timeline"

📅 Month 4 – Malware Execution & Persistence Mapping

Goal: Analyze and document real malware activity.

Study:

MITRE ATT&CK techniques: persistence, execution, C2

MalwareAnalysisForHedgehogs on YouTube

Labs:

Analyze 3 malware samples with Any.Run or Cuckoo

Observe: file writes, registry changes, process behavior, C2 traffic

✅ Deliverable:

Full technical report: infection chain + persistence + network activity

📅 Month 5 – Incident Simulation & Storytelling

Goal: Reconstruct full attack flow from artifacts.

Study:

Reports from Mandiant, The DFIR Report

Labs:

Simulate an attack with PCAP + Windows logs + Zeek

Build a timeline: initial access → persistence → exfiltration

✅ Deliverable:

Incident post-mortem: full PDF + visual timeline

📅 Month 6 – Portfolio & Next Steps

Goal: Package work, showcase skills, choose path forward.

Activities:

Organize GitHub structure: forensics/, incident-reports/, RAM-analysis/

Evaluate:

Master's programs (La Sapienza, Polimi, EU-based)

Certifications: eMAP, GCFA, GREM

Write DFIR-focused CV + LinkedIn

✅ Deliverable:

Full GitHub portfolio + CV ready + training/education decision

✍️ Why this project?

I believe technical forensics isn't about just parsing logs — it's about reconstructing narratives.This repo is my investigative lab, where I learn to turn traces into timelines, indicators into insights, and raw data into technical stories worth telling.

📌 Career Focus

Digital Forensics Specialist

Incident Responder (IR)

Threat Hunter with a forensic mindset

🚧 Work in progress

This project is ongoing and will be updated continuously with reports, case studies, and practical exercises. Stay tuned!

