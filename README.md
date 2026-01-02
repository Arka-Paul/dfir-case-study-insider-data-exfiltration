# DFIR Case Study – Insider Data Exfiltration (Simulated)

## Overview

This repository presents a **simulated Digital Forensics and Incident Response (DFIR) case study** focused on an insider-driven data exfiltration incident within a corporate Windows environment. The project demonstrates the **full DFIR lifecycle**, including evidence generation, forensic acquisition, integrity verification, artefact analysis, timeline reconstruction, and professional reporting.

All evidence was deliberately created in a **controlled Windows virtual machine** to simulate realistic insider activity. The system was then forensically acquired and analysed using industry-standard tools and methodology. The case has been **sanitised and reframed for portfolio purposes**; all identifiers, sensitive operational details, and academic markers have been removed or redacted.

---

## Investigation Objectives

- Simulate realistic insider threat behaviour within a Windows environment  
- Perform forensic acquisition using recognised forensic imaging standards  
- Analyse artefacts across application, operating system, and file system layers  
- Reconstruct a multi-phase incident timeline (**Reconnaissance, Record, Aftermath**)  
- Correlate technical findings with evidential reasoning and legal considerations  
- Demonstrate DFIR reporting suitable for corporate, consulting, and investigative roles  

---

## Case Summary

The case examines unauthorised extraction of sensitive data from a secure internal server by a privileged insider. The investigation identifies evidence of deliberate preparation through research into encryption and concealment techniques, followed by bulk data extraction and subsequent layered anti-forensic behaviour.

Recovered artefacts demonstrate:

- Pre-offence reconnaissance and capability development  
- Encryption and secure storage of exfiltrated data  
- Credential concealment via encoding and steganography  
- File-system and registry artefacts confirming user interaction  
- Post-incident attempts to obscure activity and remove traces  

Attribution is limited by shared administrative access, reflecting **realistic investigative constraints** commonly encountered in insider threat cases.

---

## Evidence Creation & Acquisition Methodology

To ensure realism and forensic validity, evidence was generated and acquired as follows:

- A **Windows 10 virtual machine** was configured to simulate a corporate workstation  
- Insider-related activities (research, data handling, concealment, and deletion) were intentionally performed within the VM to generate artefacts  
- The virtual machine disk was forensically acquired using **FTK Imager**  
- The system was imaged in **E01 format**, following forensic best practices  
- Cryptographic hash values were generated and verified to ensure **image integrity**  
- All analysis was conducted on the forensic image in **read-only mode**

The original E01 evidence file is **not distributed** as part of this repository, consistent with professional DFIR evidence-handling standards. Instead, derived artefacts, screenshots, and analysis outputs are provided.

---

## Environment

- **Operating System:** Windows 10 (22H2)  
- **File System:** NTFS  
- **Evidence Format:** Forensic disk image (E01)  
- **Acquisition Tool:** FTK Imager  
- **Analysis Mode:** Read-only forensic examination  

---

## Tools Used

- Autopsy  
- FTK Imager  
- HxD Hex Editor  
- CyberChef  
- VeraCrypt  
- Wireshark  

---

## Artefact Analysis Approach

The investigation identified and analysed **22 digital artefacts**, categorised and correlated across three incident phases:

### Reconnaissance / Research
Artefacts indicating preparatory research into encryption, data hiding, anonymisation, and monetisation techniques.

### Record (Execution)
Artefacts directly associated with unauthorised data extraction and encrypted storage of sensitive material.

### Result / Aftermath
Post-incident concealment, credential hiding, obfuscation, registry activity, and indications of financial motive and anti-forensic behaviour.

Artefact analysis incorporated:

- Registry artefacts (MRU, LNK, Shellbags)  
- File-system artefacts (deleted files, unallocated space)  
- Encrypted containers  
- Encoded text and steganographic media  

A structured **artefact register** is included to support traceability and evidential reasoning.

---

## Key Findings (Summary)

- Evidence supports **unauthorised data extraction by a privileged insider**  
- Multi-layered concealment techniques were identified, including:
  - Encryption  
  - Steganography  
  - File extension and header manipulation  
  - OS-level hidden attributes  
- Registry and file-system artefacts confirm **interactive user activity**  
- Partial wiping activity indicates **anti-forensic intent**  
- Shared credentials constrain definitive attribution, illustrating realistic DFIR limitations  

---

## Deliverables Included

- **Redacted DFIR Case Report** (PDF)  
- **Artefact Register** detailing analysed artefacts  
- **Selected Screenshots** demonstrating acquisition and analysis methodology  
- **Methodology Notes** outlining evidence creation, imaging, and analysis workflow  

---

## Professional Context

This repository is intended to demonstrate:

- DFIR methodology and discipline  
- Evidence handling and integrity awareness  
- Technical analysis and reporting skills  
- Readiness for **graduate / junior DFIR, SOC, or cyber security roles**

It reflects how a DFIR analyst documents and reasons about evidence, **not how an offence is committed**.

---

## Disclaimer

This is a **simulated DFIR case study** created for academic training and professional portfolio purposes.  
All personal identifiers, IP addresses, credentials, and sensitive operational details have been **anonymised or redacted**.  
The original forensic image is intentionally not shared in accordance with professional evidence-handling practices.  
No real victim data is included.

---

## Author

**Arka Paul**  
Graduate Cyber Security & DFIR Candidate  
GitHub: https://github.com/Arka-Paul
