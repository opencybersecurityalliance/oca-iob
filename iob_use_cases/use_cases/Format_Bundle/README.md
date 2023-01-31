# Behavior bundle formatting use case

This use case is for a CTI broker that wishes to format received STIX bundles for a threat intelligence portal and share the information with a community of recipients. 

## Sequence diagram
The sequence of events is represented in the following diagram:

<img src="/iob_use_cases/images/Format_Behavior_Bundle_sequence.png" width=600>

The sequence diagram shows the use case steps between the following entities:
- A CTI broker that wishes to format the CTI within the bundle for an intelligence platform (CTI_Broker)
- The broker's CTI portal/platform (Broker_Platform)
- A TAXII client for pulling STIX bundles (TAXII_Client)
- A workstation for formatting and creating STIX objects (STIX_WS)
- A TAXII server for sharing STIX bundles (TAXII_Server)

## BPMN Workflow

The [format bundle](FormatBundle.bpmn) use case  is also provided in Business Process Modeling Notation (BPMN). The following image provides a visualization of the BPMN workflow:

<img src="/iob_use_cases/images/FormatBundle.png" width=1000> 

