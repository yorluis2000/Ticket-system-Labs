# 🎫 Ticket System Labs

Welcome to my IT Support ticketing labs repository. This project showcases my hands-on experience in triaging, diagnosing, and resolving enterprise helpdesk tickets using an evidence-based troubleshooting approach.

## 📹 Lab Demonstration Video
*(Upload your video file to the repository and replace this link, or simply drag-and-drop the video directly into the GitHub editor)*


https://github.com/user-attachments/assets/cc1b533f-627c-458b-b263-8da689c78c75



## 🛠️ Core Competencies Demonstrated
*   **Ticket Triage:** Assessing business impact, reading the evidence chain, and identifying root causes.
*   **System Troubleshooting:** Resolving BSOD crash loops (e.g., `SYSTEM_SERVICE_EXCEPTION`) and driver faults using Safe Mode, Event Viewer, and Device Manager.
*   **Non-Destructive Repair:** Prioritizing data preservation and minimizing downtime by reversing specific triggers rather than relying on heavy-handed OS reinstalls.

## 🚀 Featured Scenario: The Update That Broke Payroll
*   **The Issue:** A critical payroll workstation (PAY-01) became trapped in a BSOD crash loop following an overnight update.
*   **The Fix:** Analyzed the stop code to identify `ldgrflt.sys` as the culprit. Booted into Safe Mode to bypass the crash loop, then successfully rolled back the LedgerPay filter driver from `4.2.0.11` to the stable `4.1.9.80` version.
*   **The Result:** System stability restored and payroll data preserved with zero business capabilities sacrificed.
