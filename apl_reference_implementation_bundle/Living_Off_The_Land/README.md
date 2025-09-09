# Living off the Land IOB Bundle

This repository contains documentation and a Structured Threat Information eXpression (STIX) 2.1 bundle representing **Indicators of Behavior (IOBs)** for adversary tradecraft that leverages *Living off the Land (LOTL)* techniques. The work was prepared by the Johns Hopkins University Applied Physics Laboratory (JHU/APL) under sponsorship from the Cybersecurity and Infrastructure Security Agency (CISA).

The materials are intended to support operational defenders by providing machine-readable behavior representations, detection rules, and correlation logic that elevate weak signals into actionable alerts.

---

## Contents

- **Living_off_the_Land_IOB_Bundle_Overview.pdf**  
  A report describing the threat narrative, behaviors, detections, and correlation logic for LOTL activities. Includes guidance for applying the bundle in analyst workflows and automated systems.

- **STIX Bundle (JSON)**  
  A complete behavior set expressed in STIX 2.1 with Open Cybersecurity Alliance (OCA) extensions.  
  - Defines behaviors (e.g., LSASS dumping, PowerView usage, NTDS extraction, event log deletion, WinRS execution).  
  - Provides Sigma-based detection rules.  
  - Includes correlation playbooks in **CACAO JSON** and **BPMN** formats.

## Disclaimer

The views and conclusions contained in this document are those of the author and should not be interpreted as necessarily representing the official policies, either expressed or implied, of the U.S. Department of Homeland Security / Cybersecurity and Infrastructure Security Agency.

The bundle developed by APL is for the demonstration of the adversary behavior concept and is not “turn key” and is not safe for deployment without being tailored to production infrastructure. These files are not being delivered as software and are not appropriate for direct use on any production networks. APL assumes no liability for the direct use of these files and they are provided strictly as a reference implementation. 

NO WARRANTY, NO LIABILITY. THIS MATERIAL IS PROVIDED “AS IS.” APL MAKES NO REPRESENTATION OR WARRANTY WITH RESPECT TO THE PERFORMANCE OF THE MATERIALS, INCLUDING
THEIR SAFETY, EFFECTIVENESS, OR COMMERCIAL VIABILITY, AND DISCLAIMS ALL WARRANTIES IN THE MATERIAL, WHETHER EXPRESS OR IMPLIED, INCLUDING (BUT NOT LIMITED TO) ANY AND ALL IMPLIED WARRANTIES OF PERFORMANCE, MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NON-INFRINGEMENT OF INTELLECTUAL PROPERTY OR OTHER THIRD PARTY RIGHTS. ANY USER OF THE MATERIAL ASSUMES THE ENTIRE RISK AND LIABILITY FOR USING THE MATERIAL. IN NO EVENT SHALL APL BE LIABLE TO ANY USER OF THE MATERIAL FOR ANY ACTUAL, INDIRECT, CONSEQUENTIAL, SPECIAL OR OTHER DAMAGES ARISING FROM THE USE OF, OR INABILITY TO USE, THE MATERIAL, INCLUDING, BUT NOT LIMITED TO, ANY DAMAGES FOR LOST PROFITS.