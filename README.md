# Open Cybersecurity Alliance Indicators of Behavior (IOB) Research

## Overview
This repository contains code and reference implementations developed under various collaborations with the Open Cybersecurity Alliance Indicator of Behavior Sub-Project.

An overview of the Sub-Project is available [here](https://github.com/opencybersecurityalliance/oca-iob/blob/main/Presentations/IOB%20WG%20Overview.pdf)

The IOB WG charter is available [here](https://github.com/opencybersecurityalliance/oca-iob/blob/main/charter.md).

Documentation for STIX 2.1 complaint IOB objects including the relevant schema is available in the OCA STIX extensions repository [here](https://github.com/opencybersecurityalliance/stix-extensions/tree/main/contexts/indicator-of-behavior).

A fork of the STIX Modeler that supports the creation and visualization of IOB STIX objects is available [here](https://github.com/JHUAPL/STIXMODELER_UI).

## Join US
You can join the IOB sub-project by joining our [slack channel](https://join.slack.com/t/open-cybersecurity/shared_invite/zt-19pliofsm-L7eSSB8yzABM2Pls1nS12w).

## How IOB compares to traditional Indicators of Compromise (IOC), Indicators of Attack (IOA), and Indicators of Exposure (IOE)

Indicators of Compromise (IOC), Indicators of Attack (IOA), Indicators of Behavior (IOB), and Indicators of Exposure (IOE) provide complementary approaches to cybersecurity defense.

IOCs identify artifacts or evidence associated with malicious activity or compromise. IOAs identify activity patterns associated with adversary tactics, techniques, and procedures. IOEs characterize assets, vulnerabilities, and potential attack paths that create opportunities for compromise.

IOBs extend the behavioral approach by describing repeatable sequences of adversarial activity observed across multiple attack families. Rather than focusing exclusively on individual observations, IOBs connect behavioral sequences with detection analytics, correlation workflows, and response workflows.

The distinction between IOA and IOB is particularly important. An IOA can identify a suspicious or malicious activity pattern, while an IOB provides a mechanism for recognizing sequences of behavior and connecting those observations to defensive action.

These approaches are complementary rather than mutually exclusive. Together, they support identifying exposure, recognizing attacks, understanding adversarial behavior, and investigating compromise.

## Code of Conduct
This Sub-Project follows the OASIS Code of Conduct.

## Acknowledgements
The IOB Sub-Project wishes to thank Dr. Vasileios Mavroeidis and his teams at University of Oslo / Cyentific AS for their technical discussions on best practices to represent CACAO playbooks within STIX.
