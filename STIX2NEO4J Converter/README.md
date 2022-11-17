# STIX to Neo4J Uploader
This is a simple script meant to upload a STIX 2.1 JSON bundle into a NEO4J database. This script will allow any STIX 2.1 bundle to be converted to a NEO4J graph database, but it was particularly developed to help visualize the indicator of behavior reference implementation available at the [IOB WG Github Site](https://github.com/opencybersecurityalliance/documentation/tree/master/iob-wg/apl_reference_implementation_bundle/revision_1)

# Prerequisites
- A NEO4J graph database available from [NEO4J GitHub](https://github.com/neo4j)
- Python3

# Installation
In a terminal, run the following commands:
```
git clone REPOSITORY_URL
cd stix2-neo4j  
```
If using a python virtual environment, which is recommended:
```
python3 -m venv venv
source venv/bin/activate
```
To install the required libraries:
```
pip3 install -r requirements.txt
```

# Usage
From inside the stix2-neo4j folder, run:
```
python3 STIX2NEO4j.py
```

You will be prompted for the information to connect to your graph database and save the bundle.

If using the standard NEO4J install, the graph database, it will be available at http://ADDRESS_OF_YOUR_SERVER:7474

You can view your bundle with the following Cypher Query:
```
MATCH (A) WHERE A.bundlesource="YOUR_BUNDLE_NAME" RETURN A
```
# Note
If researching the IOB WG behavior bundle prototype, a grass file is included to help with visualization in the NEO4J browser.

# DISCLAIMER
This script developed by JHU/APL is for demonstration and research purposes. It is not “turn key” and is not safe for deployment without being tailored to production infrastructure. These files are not being delivered as software and are not appropriate for direct use on any # production networks. JHU/APL assumes no liability for the direct use of these files and they are provided strictly as a reference implementation.

NO WARRANTY, NO LIABILITY. THIS MATERIAL IS PROVIDED “AS IS.” JHU/APL MAKES NO REPRESENTATION OR WARRANTY WITH RESPECT TO THE PERFORMANCE OF THE MATERIALS, INCLUDING THEIR SAFETY, EFFECTIVENESS, OR COMMERCIAL VIABILITY, AND DISCLAIMS ALL WARRANTIES IN THE MATERIAL, WHETHER EXPRESS OR IMPLIED, INCLUDING (BUT NOT LIMITED TO) ANY AND ALL IMPLIED WARRANTIES OF PERFORMANCE, MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NON-INFRINGEMENT OF INTELLECTUAL PROPERTY OR OTHER THIRD PARTY RIGHTS. ANY USER OF THE MATERIAL ASSUMES THE ENTIRE RISK AND LIABILITY FOR USING THE MATERIAL. IN NO EVENT SHALL JHU/APL BE LIABLE TO ANY USER OF THE MATERIAL FOR ANY ACTUAL, INDIRECT, CONSEQUENTIAL, SPECIAL OR OTHER DAMAGES ARISING FROM THE USE OF, OR INABILITY TO USE, THE MATERIAL, INCLUDING, BUT NOT LIMITED TO, ANY DAMAGES FOR LOST PROFITS.
