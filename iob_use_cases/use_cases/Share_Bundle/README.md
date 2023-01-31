# Behavior bundle sharing use case

This use case is for a CTI producer or broker that wishes to share a created STIX bundle via a Trusted Automated eXchange of Intelligence Information (TAXII) server.

## Sequence diagram
The sequence of events is represented in the following diagram:

<img src="/iob_use_cases/images/Share_Bundle_sequence.png" width=600>

The sequence diagram shows the use case steps between the following entities:
- A CTI user who wishes to share the bundle (CTI_Updater)
- A TAXII server that shares STIX bundles (TAXII_Server)
- A workstation for formatting and creating STIX objects (STIX_WS)

## BPMN Workflow

The [sharing bundle](ShareBundle.bpmn) use case  is also provided in Business Process Modeling Notation (BPMN). The following image provides a visualization of the BPMN workflow:

<img src="/iob_use_cases/images/ShareBundle.png" width=1000> 

