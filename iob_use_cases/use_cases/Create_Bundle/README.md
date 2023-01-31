# Behavior bundle creation use case

This use case is for a Cyber Threat Intelligence (CTI) producer that wishes to create a STIX bundle following our [reference implementation](https://github.com/opencybersecurityalliance/oca-iob/tree/main/apl_reference_implementation_bundle/revision_1). 

## Sequence diagram
The sequence of events is represented in the following diagram:

<img src="/images/Create_Bundle_sequence.png" width=600>

The sequence diagram shows the use case steps between the following entities:
- A CTI Producer (CTI_Producer)
- A CTI Workstation (CTI_WS)
- A Security Information and Event Management platform (SIEM)
- A Security Orchestration, Automation and Response platform (SOAR)
- A workstation for formatting and creating STIX objects (STIX_WS)

## BPMN Workflow

The [create bundle](CreateBundle.bpmn) use case  is also provided in Business Process Modeling Notation (BPMN). The following image provides a visualization of the BPMN workflow:

<img src="/images/CreateBundle.png" width=1000> 

