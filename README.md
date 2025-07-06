# DSA-FINAL-PROJECT-CAPSTONE
# 🕵️‍♂️ Android Forensic Investigation in a Virtual Forensic Lab
# 📌 Project Title
# Building a Virtual Cybersecurity Laboratory and Conducting Android Forensic Investigations
## 📝 Description
This project demonstrates how to set up a virtual forensic laboratory and perform an Android forensic investigation. The investigation involves simulating data extraction, analysis, and reporting on an Android image device using autopsy.
### 🎯 Objectives
•	To create a virtual forensic lab using virtual machines such as Kali Linux, Windows 10 ISO and Pfsense.
•	To perform a structured Android forensic investigation on autopsy.
•	To collect, extract, analyze, and report digital evidence from an Android environment.
## 🛠Used Tools and Technologies
•	Kali Linux – for forensic tools and analysis
•	Autopsy – for data analysis
•	PFsense   _ firewall (filtering incoming and outgoing traffic
•	Windows 10
•	Windows 10 ISO
•	Android Virtual Device (AVD)  – for simulating Android environments
•	FTK Imager – for disk imaging

## 🏗️ Forensic Lab Setup
1.	Installed VirtualBox and created VMs for:
•	Kali Linux (Analyst workstation)
•	Windows 10 ISO
2.	Configured shared folders and ADB bridge between host and Android VM.
3.	Verified lab environment for capturing data and logs.
## 🔍 Android Forensic Investigation Process
### Step 1: Evidence Acquisition
•	Used autopsy to extract data from internal storage.
•	Captured a logical image using autopsy and stored it in the forensic workstation.
### Step 2: Data Analysis
•	Opened extracted files and images in Autopsy.
•	Analyzed:
•	Communication
•	Messages (SMS)
•	Installed apps and usage
•	Browser history
•	Media files
•	Images
•	Call Logs
•	Searched for traces of suspicious activities (e.g., deleted messages, app data remnants).
### Step 3: Documentation and Reporting
•	All actions and findings were documented.
•	Created a forensic report summarizing:
•	The environment
•	Methodology
•	Tools used
•	Key findings
•	Screenshots
•	Timeline of user activity
# 📁 Folder Structure
CopyEdit
.
├── README.md
├── /Reports
│   └── Android_Forensic_Report.pdf
├── /Evidence
│   └── extracted_data/
├── /Scripts
│   └── adb_extraction.sh
# ✅ Outcomes
•	A fully functioning virtual forensic lab.
•	Acquired and analyzed Android data for digital evidence.
•	Produced a formal forensic report adhering to chain-of-custody standards.
 
________________________________________


