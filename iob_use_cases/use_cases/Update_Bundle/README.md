# Behavior bundle update use case

This use case is for a CTI producer that wishes to update the information within an existing bundle of behavior information.

## Sequence diagram
The sequence of events is represented in the following diagram:

<img src="/iob_use_cases/images/Update_Bundle_sequence.png" width=600>

The sequence diagram shows the use case steps between the following entities:
- A CTI user who updates the information (CTI_Updater)
- A CTI Workstation (CTI_WS)
- A TAXII client that pulls STIX bundles (TAXII_Client)
- A TAXII server that shares STIX bundles (TAXII_Server)
- A workstation for formatting and creating STIX objects (STIX_WS)

## BPMN Workflow

The [update bundle](Update%20Bundle.bpmn) use case  is also provided in Business Process Modeling Notation (BPMN). The following image provides a visualization of the BPMN workflow:

<img src="/iob_use_cases/images/UpdateBundle.png" width=1000> 

