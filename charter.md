# Indicators of Behavior (IoB) Sub-Project Charter

## 1. Project Name

Open Cybersecurity Alliance Indicators of Behavior Sub-Project

## 2. Abstract
The OCA Indicators of Behavior Sub-Project is comprised of global like-minded cybersecurity vendors, end users, thought leaders and individuals who are interested in creating a standardized approach for representing cyber threat actor behaviors in a shareable format to augment the world’s capability in detecting and responding to cyber threats in a broader capacity than what is currently possible with Indicators of Compromise. It is a forum where products from all vendors, researchers, and software publishers can freely exchange information, insights, and reference implementations via commonly developed code and tooling, using mutually agreed upon technologies, data standards, and procedures.

## 3. Purpose and Scope 
The reality of the current cyber threat landscape is daunting. Attacks are becoming more frequent, more impactful, and more sophisticated. CTI sharing communities and activities have evolved from efforts within government, to establish more government-wide situational awareness and now to sharing between government, critical infrastructure owners/operators, and commercial cybersecurity service providers to support mitigation of these shared cyber threats.  However, sharing traditional indicators of compromise (IOCs) is no longer effective against an ever increasingly sophisticated adversary.  It is imperative that we continue to evolve and mature as a global community to maintain a competitive advantage over our adversaries. 

To that end the OCA IoB Sub-Project was established to bring key stakeholders in the CTI community together to collectively focus on patterns of behavior associated with malicious cyber activity.  By understanding “normal” and possibly malicious behaviors or patterns of activity in our networks we can develop innovative solutions that enable us to share behavior sets (aka sets of adversarial behaviors) amongst the CTI community.   These behavior sets and associated detection strategies will lead to more proactive detection, more effective mitigations and, through timely and actionable sharing,  more prevention.

## 4. Societal Benefits 
End user organizations consistently face challenges with the integration of CTI in direct network defense operations. This is often due to the primary actionable shared data being Common Vulnerability Enumerations (CVEs) and Indicators of Compromise (IoCs). While it is critical to ensure CVEs are mitigated and active IoCs are blocked, these actions by their very nature force a reactive posture to an ever increasing cyber threat. Larger organizations with robust threat hunting teams are able to interpret insights from CTI into more proactive actions but the transfer of this knowledge and capability is not widespread to all organizations and currently is not occurring at machine speed while the cyber threat advances in speed and scale.

By creating machine-readable IoB objects and reference implementation code to easily integrate representations of adversary behaviors, the IoB Working Group can provide rapid detection and response capabilities that can be readily accessible to all organizations and provide standardization amongst the vendor community who can help provide capability to smaller organizationsthat may not have the resources for advanced threat hunting teams. The overarching theme is to foster collaboration across and between organizations. 

## 5. Relationship to Other Projects 
Structured Threat Information eXpression (STIX) - The IoB Sub-Project will make usage of the STIX 2.1 CTI for representation of IoB data in machine readable format. It will also use STIX 2 format for any consumption or federation of cyber threat intelligence for operations purposes. Other use cases involving STIX 2 and TAXII 2 may also be implemented in projects in the future. More information is available at [https://oasis-open.github.io/cti-documentation/](https://oasis-open.github.io/cti-documentation/).

Collaborative Automated Course of Action Operations (CACAO) – For objects that may help organizations respond to threat behaviors via automated workflows, the IoB Sub-Project will ensure that shared workflows are compliant with the CACAO standard as it is developed.  More information on CACAO is available at 
[https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=cacao](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=cacao).

The IoB Sub-Project will develop hunting analytics using existing open standard languages such as Sigma, Kestrel, etc. 

## 6. Repositories and Licenses 
The project expects to launch with one repository for development of the initial code. The repository will be under the CC BY 4.0 open-source license for non-code contributions and the Apache License v2.0 for code contributions. 

## 7. Initial Contributions from Existing Work
Behavior sharing concept from the Integrated Adaptive Cyber Defense (IACD) Community 
* Whitepaper: [https://www.iacdautomate.org/s/Machine-Readable-Behavior-Objects-for-Cyber-Defense.pdf](https://www.iacdautomate.org/s/Machine-Readable-Behavior-Objects-for-Cyber-Defense.pdf)
* Conceptual Video: [https://youtu.be/z-QT0pIZ4Dc](https://youtu.be/z-QT0pIZ4Dc)
* Experimental Proof of Concept Demo: [https://youtu.be/_eCXtB7bWUk](https://youtu.be/_eCXtB7bWUk) 

## 8. Contributors
Initial technical contributors are expected to include:
* Daryl Diebold (IBM) – daryldiebold@ibm.com
* Charles Frick (JHU/APL) – Charles.Frick@jhuapl.edu
* Paula Lewandoski (JHU/APL) – Paula.Lewandoski@jhuapl.edu
* Maggie MacAlpine (Cybereason) – Maggie.macalpine@cybereason.com 
* Jason Keirstead (IBM) - Jason.Keirstead@ca.ibm.com

