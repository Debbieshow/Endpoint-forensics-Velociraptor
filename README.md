
# 🦖 Enterprise Threat Hunting & Endpoint Forensics with Velociraptor

Applying an investigative audit mindset to Digital Forensics (DFIR) by deploying **Velociraptor** to collect Windows endpoint artifacts, hunt for Indicators of Compromise (IOCs), and uncover persistence mechanisms.

---

## 🔍 Project Overview

In financial audit, uncovering anomalies requires following transaction ledgers and validating raw evidence. This project applies that exact principle to endpoint visibility and proactive threat hunting.

A dedicated **Velociraptor** lab environment was deployed to simulate real-world forensic artifact collection across endpoints. Using **Velociraptor Query Language (VQL)**, the lab automates artifact retrieval, inspects volatile system state, and scales digital forensics across systems.

---

## 🎯 Key Objectives & Hands-On Execution

* **🖥️ Endpoint Visibility & Artifact Collection:** Queried forensic artifacts across target systems to inspect running processes, system information, and host activity.
* **🕵️ Hunting Persistence Mechanisms:** Executed targeted VQL and **Sysinternals** artifacts (such as `Autoruns`) to surface unauthorized startup items, scheduled tasks, and registry modifications.
* **🚨 Proactive Threat Hunting:** Searched endpoints for known Indicators of Compromise (IOCs), anomaly baselining, and irregular system modifications.
* **📂 Evidence Validation & Documentation:** Maintained a clean, verifiable trail of collected forensic data and structured query outputs.

---

## 🛠️ Lab Architecture & Hands-on Implementation

### 1. ⚙️ Environment Setup & Endpoint Enrollment
Configured the central Velociraptor server and enrolled the Windows client endpoint to enable centralized live forensic collection and real-time visibility.

[View Screenshot: Endpoint Enrollment and Host Overview](images/endpoint_overview.png)

---

### 2. 📊 VQL Artifact Execution & Artifact Collection
Leveraged targeted Velociraptor Query Language (VQL) modules (such as process listing and system inventory artifacts) to extract critical forensic evidence directly from the host.

[View Screenshot: VQL Artifact Execution and Process List](images/vql_collection.png)

---

### 3. 🛡️ Threat Hunting & Persistence Analysis
Conducted proactive endpoint hunts using Velociraptor's Sysinternals integration to enumerate persistence locations, verify binary signatures, and surface potential IOCs.

[View Screenshot: Threat Hunting and Persistence Results](images/threat_hunting_results.png)

---

## 🧰 Core Skills & Tools

* **🔧 Tooling:** Velociraptor, VQL (Velociraptor Query Language), Sysinternals Suite, Windows Forensics
* **🧠 Domain Expertise:** Proactive Threat Hunting, Live Endpoint Forensics, Artifact Collection, Persistence Analysis, Evidence Integrity

---

## 💡 Key Takeaways

* **Scalable Forensics:** Demonstrated how enterprise DFIR orchestration tools scale artifact collection across multiple endpoints without manual per-host pulls.
* **Rapid Visibility:** Accelerated threat hunting workflows by using centralized VQL queries to inspect volatile system state and persistence mechanisms.
* **The Audit Mindset:** Bridged rigorous financial evidence-validation standards with modern digital forensics and threat hunting.
