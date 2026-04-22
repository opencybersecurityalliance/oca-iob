# Indicators of Behavior (IOB) Operational Pilot – Artifacts

This repository contains artifacts from the **Indicators of Behavior (IOB) Operational Pilot** conducted by the Johns Hopkins University Applied Physics Laboratory (JHU/APL) in partnership with CISA, the Open Cybersecurity Alliance (OCA), and the HudsonAlpha Institute for Biotechnology.

The pilot evaluated how behavior-based cyber threat intelligence—expressed as IOBs in STIX format—can be integrated into a production Security Operations Center (SOC) to improve detection accuracy and reduce analyst workload.

---

## Repository Contents

### 1. Pilot Summary Report
- **File:** `hapilot_report_tlp_clear.pdf`
- Provides a full description of the pilot, including:
  - Architecture and system design
  - Detection and correlation methodology
  - Operational deployment and execution
  - Performance results and findings

---

### 2. STIX IOB Bundle – Use Case 1 (Data Theft)
- Represents a multi-stage data exfiltration scenario
- Focuses on network-observable behaviors such as:
  - Internal reconnaissance (e.g., PowerView)
  - Lateral movement (SSH)
  - Data exfiltration to cloud storage (e.g., S3)

Includes:
- Behavioral indicators
- Detection analytics (e.g., Sigma-based logic)
- Correlation workflows

---

### 3. STIX IOB Bundle – Use Case 2 (Data Integrity Compromise)
- Represents adversary activity targeting **integrity of genomic data**
- Includes behaviors such as:
  - External persistence mechanisms
  - Remote access (VNC-based lateral movement)
  - Malicious script execution (PowerShell)

Demonstrates extension of IOBs to endpoint and lab-focused scenarios.

---

## Key Concepts

**Indicators of Behavior (IOBs)** extend beyond traditional Indicators of Compromise (IOCs) by modeling *how adversaries operate*, rather than focusing on isolated artifacts like IPs or file hashes.

Each IOB bundle includes:
- Behavioral definitions aligned to MITRE ATT&CK
- Detection logic
- Correlation playbooks
- STIX 2.1 representations for interoperability

---

## Key Results from the Pilot

- Detection and correlation executed within ~5 minutes of final adversary behavior
- Zero false positives during the operational period
- Thousands of benign events automatically suppressed
- Only fully correlated behavior sequences generated alerts

---

## Intended Use

This repository is intended for:
- Security engineers and SOC analysts
- Cyber threat intelligence practitioners
- Organizations evaluating behavior-based detection
- Researchers and contributors to OCA IOB development

---

## Notes

- All content is released as **TLP: CLEAR**
- STIX bundles are provided as example implementations and may require adaptation
- Scenarios are based on realistic adversary behaviors in biotechnology environments

---
## Disclaimer

The views and conclusions contained in this document are those of the author and should not be interpreted as necessarily representing the official policies, either expressed or implied, of the U.S. Department of Homeland Security / Cybersecurity and Infrastructure Security Agency.

The bundle developed by APL is for the demonstration of the adversary behavior concept and is not “turn key” and is not safe for deployment without being tailored to production infrastructure. These files are not being delivered as software and are not appropriate for direct use on any production networks. APL assumes no liability for the direct use of these files and they are provided strictly as a reference implementation. 

NO WARRANTY, NO LIABILITY. THIS MATERIAL IS PROVIDED “AS IS.” APL MAKES NO REPRESENTATION OR WARRANTY WITH RESPECT TO THE PERFORMANCE OF THE MATERIALS, INCLUDING
THEIR SAFETY, EFFECTIVENESS, OR COMMERCIAL VIABILITY, AND DISCLAIMS ALL WARRANTIES IN THE MATERIAL, WHETHER EXPRESS OR IMPLIED, INCLUDING (BUT NOT LIMITED TO) ANY AND ALL IMPLIED WARRANTIES OF PERFORMANCE, MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NON-INFRINGEMENT OF INTELLECTUAL PROPERTY OR OTHER THIRD PARTY RIGHTS. ANY USER OF THE MATERIAL ASSUMES THE ENTIRE RISK AND LIABILITY FOR USING THE MATERIAL. IN NO EVENT SHALL APL BE LIABLE TO ANY USER OF THE MATERIAL FOR ANY ACTUAL, INDIRECT, CONSEQUENTIAL, SPECIAL OR OTHER DAMAGES ARISING FROM THE USE OF, OR INABILITY TO USE, THE MATERIAL, INCLUDING, BUT NOT LIMITED TO, ANY DAMAGES FOR LOST PROFITS.