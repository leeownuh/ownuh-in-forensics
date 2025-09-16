# 🕵️ Ownuh in Forensics

A growing collection of **Python-based digital forensics tools**, built for learning, research, and practical investigations.  
This project is designed to bridge **academic research** and **real-world forensic needs**, with modular tools that each solve a specific gap in existing forensic workflows.  

---

## 📌 Features
- 🔐 File Hash & Integrity Reporter — maintain evidence chain of custody
- 🌐 Browser Artifact Collector — parse history, cookies, and downloads
- 💾 USB Artifact Extractor — detect external storage activity from registry logs
- 📋 Clipboard & Recent Files Extractor — find insider threat traces
- 📝 Log Triage Tool — quickly filter suspicious system logs
- 🖼️ Metadata Integrity Checker — detect tampered EXIF & timestamps
- 🧠 Steganography Detector (future) — identify hidden data in images

Each tool is standalone but can be combined into a **forensic triage suite**.

---

## 📂 Repository Structure
- `tools/` → Individual forensic tools
- `docs/` → Documentation, usage guides, diagrams
- `requirements.txt` → Python dependencies

---

## 🚀 Quick Start
```bash
# Clone repository
git clone https://github.com/yourusername/digital-forensics-toolkit.git
cd digital-forensics-toolkit

# Install dependencies
pip install -r requirements.txt

# Run a sample tool
python tools/hash_integrity_reporter/hash_reporter.py evidence/test_file.txt
