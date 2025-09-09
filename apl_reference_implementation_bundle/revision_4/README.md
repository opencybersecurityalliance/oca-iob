# Revision 4 Adversary Behavior STIX Bundle

## Overview
This is the revision 4 STIX bundle and documentation of the Johns Hopkins University Applied Physics Laboratory (APL) research for representing cyber adversary behavior in a Structured Threat Information eXchange (STIX) 2.1 bundle. This research was conducted for the Cybersecurity and Infrastructure Security Agency (CISA). 

## Disclaimer

The views and conclusions contained in this document are those of the author and should not be interpreted as necessarily representing the official policies, either expressed or implied, of the U.S. Department of Homeland Security / Cybersecurity and Infrastructure Security Agency.

## Changelog

- Standardized all object identifiers to lowercase UUID format for consistency and parser compatibility
- Updated playbooks supporting advanced correlation and scoring logic, in both CACAO and BPMN formats
- Removed deprecated fields: data_sources (from x-oca-detection) 
- Added descriptions to all detections
- Restructured relationships to improve chaining of behavior sequences and strengthen correlation logic
- Improved Sigma rules for clarity and integration across SIEM platforms
- Updated extension definitions to support enhanced metadata and scoring capabilities
- Cleaned up redundant or outdated objects from Revision 3 to streamline the reference bundle



The bundle developed by APL is for the demonstration of the adversary behavior concept and is not “turn key” and is not safe for deployment without being tailored to production infrastructure. These files are not being delivered as software and are not appropriate for direct use on any production networks. APL assumes no liability for the direct use of these files and they are provided strictly as a reference implementation. 

NO WARRANTY, NO LIABILITY. THIS MATERIAL IS PROVIDED “AS IS.” APL MAKES NO REPRESENTATION OR WARRANTY WITH RESPECT TO THE PERFORMANCE OF THE MATERIALS, INCLUDING
THEIR SAFETY, EFFECTIVENESS, OR COMMERCIAL VIABILITY, AND DISCLAIMS ALL WARRANTIES IN THE MATERIAL, WHETHER EXPRESS OR IMPLIED, INCLUDING (BUT NOT LIMITED TO) ANY AND ALL IMPLIED WARRANTIES OF PERFORMANCE, MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NON-INFRINGEMENT OF INTELLECTUAL PROPERTY OR OTHER THIRD PARTY RIGHTS. ANY USER OF THE MATERIAL ASSUMES THE ENTIRE RISK AND LIABILITY FOR USING THE MATERIAL. IN NO EVENT SHALL APL BE LIABLE TO ANY USER OF THE MATERIAL FOR ANY ACTUAL, INDIRECT, CONSEQUENTIAL, SPECIAL OR OTHER DAMAGES ARISING FROM THE USE OF, OR INABILITY TO USE, THE MATERIAL, INCLUDING, BUT NOT LIMITED TO, ANY DAMAGES FOR LOST PROFITS.