# Behavior bundle receiving use case

This use case is for a CTI broker or consumer that wishes to receive a STIX bundle from a TAXII server via a TAXII client.

## Sequence diagram
The sequence of events is represented in the following diagram:

<img src="/images/Receive_Bundle_sequence.png" width=600>

The sequence diagram shows the use case steps between the following entities:
- A CTI consumer who wishes to receive the bundle (CTI_Consumer)
- A CTI Workstation (CTI_WS)
- A Threat Intelligence Platform used by the consumer (TIP)
- A TAXII client that pulls STIX bundles (TAXII_Client)

## BPMN Workflow

The [receive bundle](ReceiveBundle.bpmn) use case  is also provided in Business Process Modeling Notation (BPMN). The following image provides a visualization of the BPMN workflow:

<img src="/images/ReceiveBundle.png" width=1000> 

