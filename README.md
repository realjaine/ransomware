# 🛡️ Ransomware Detection System (Python)

> CDAC Noida – Cyber Gyan Virtual Internship Program
> Domain: Cybersecurity (Ransomware Detection)

---

## 👨‍💻 Author

**Tanmay Jain**
Project Trainee (Jan–Feb 2025)

---

## 🏢 Organization

**CDAC Noida**

---

## 📌 Project Overview

Ransomware has evolved into one of the most dangerous cybersecurity threats, capable of encrypting critical data and disrupting entire systems.

This project focuses on:

* Implementing a **controlled ransomware proof-of-concept (PoC)**
* Developing a **multi-layered detection system**

The system combines:

* Signature-based detection
* Behavioral analysis
* Anomaly detection

---

## 🎯 Objectives

* Understand ransomware behavior and lifecycle
* Develop a safe ransomware simulation
* Detect ransomware using multiple techniques
* Analyze Indicators of Compromise (IoCs)

---

## ⚠️ Disclaimer

This project is developed strictly for **educational and research purposes** inside a controlled environment.

---

## 🧠 Problem Statement

Modern ransomware:

* Uses **polymorphic code**
* Exploits legitimate tools (PowerShell, vssadmin)
* Evades traditional antivirus systems

This project aims to bridge the gap between:
➡️ Understanding ransomware
➡️ Building effective detection systems

---

## ⚙️ System Workflow

![Workflow](docs/workflow.png)

---

## 🧩 Detection Techniques

### 🔹 1. Signature-Based Detection

* Uses known malware patterns
* Implemented using **YARA rules**

---

### 🔹 2. Behavioral Analysis

* Monitors:

  * File changes
  * Process activity
  * Registry modifications
* Tools used: **Wazuh**

---

### 🔹 3. Anomaly Detection

* Machine Learning based detection
* Algorithm: **Isolation Forest (Scikit-learn)**
* Detects abnormal system behavior

---

## 🛠️ Tools & Technologies

### 💻 Development

* Python
* PyInstaller

### 🔐 Encryption

* AES-256 (file encryption)
* RSA-2048 (key exchange)

### 🔍 Analysis Tools

* Wireshark
* VirusTotal
* IDA Pro

### 🧠 Detection

* YARA
* Wazuh
* Scikit-learn

### 🧪 Environment

* VMware (isolated lab)
* pfSense firewall

---

## 📂 Project Structure

```bash id="7z8p8n"
📦 ransomware-detection-system
 ┣ 📂 src
 ┃ ┣ ransomware_simulator.py
 ┃ ┣ detector_behavior.py
 ┃ ┣ detector_signature.py
 ┃ ┣ anomaly_model.py
 ┣ 📂 rules
 ┃ ┗ ransomware_rules.yar
 ┣ 📂 docs
 ┃ ┗ workflow.png
 ┣ 📂 data
 ┃ ┗ sample_files/
 ┗ README.md
```

---

## 🚀 Implementation

### 🔹 Ransomware Simulation

* Encrypts sample files using AES
* Generates ransom note
* Runs only in sandbox environment

---

### 🔹 Detection System

#### Behavioral:

* Tracks unusual file modifications
* Detects rapid encryption patterns

#### Signature:

* Matches known ransomware signatures

#### Anomaly:

* Trained on normal system behavior
* Flags deviations

---

## 🚨 Indicators of Compromise (IoC)

* Rapid file encryption
* File renaming patterns
* High CPU usage
* Suspicious outbound traffic

---

## 📊 Results

* Successfully detected ransomware behavior
* Reduced detection delay using multi-layer approach
* Improved detection accuracy

---

## 🔮 Future Improvements

* Deep learning-based detection
* Real-time endpoint protection
* Cloud-based threat intelligence
* Automated response system

---

## 📚 References

* NIST Cryptography Standards (AES, RSA)
* YARA Documentation
* Wazuh Documentation
* MITRE ATT&CK Framework

---

## 🙌 Acknowledgement

I would like to thank the **CDAC Noida team** and Cyber Gyan Internship Program for their guidance and support.

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
