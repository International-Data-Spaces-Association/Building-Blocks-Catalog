 # Trusted Exchange

 ## Definition
<div align="justify">This building block facilitates trusted data exchange among participants, reassuring participants in a data exchange transaction that other participants really are who they claim to be and that they comply with defined rules/agreements. This can be achieved by organisational measures (e.g. certification or verified credentials) or technical measures (e.g. remote attestation).</div> 

## Role and Scope
<div allign="justify">Facilitates trusted data exchange among participants.</div>

## Features 
### DSBA - CTO architecture coherence
- Security Profiles
- Certification
- Remote Attestation, remote integrity verification
- Trust Authority for verifying trustworthiness of participants
- European identification
- IDS Connector implementation

## Components and Technologies
### DSBA - CTO architecture coherence
- IDSA
  - Certification for Base, Trust, Trust+ profiles
  - Certification for Operational Environment and Components
  - Remote Attestation as specified in RAM for Trust and Trust+ profiles
- Gaia-X 
  - W3C VC (somehow connected to Gaia-X labels and to Gaia-X Compliance(automated compliance checks))
- FIWARE/iSHARE: 
  - iSHARE Satellite with strong contractual framework to provide multi IDP functionality Contributing a strong legal framework and is already operating
  - Keyrock, which supports eID / eIDAS
  - Implemented by FIWARE Community: FIWARE TRUE Connector (Available on Github)
  - IDSA Open Source projects

### i3-Market Project
- Tokenization

## Technical Reference Implementation
### Design Principles Position Paper
<div align="justify">"Trust is a necessary feature in any data-sharing environment, i.e. also for predictive maintenance. Unfortunately, predictive maintenance is difficult to achieve, as algorithms used are still not as effective as desired, and the quality of outcome often is not sufficient, due to a lack of reliable data. Nevertheless, integrating and leveraging data from partners – and even from competitors or companies from different sectors (OEMs, maintenance equipment producers, energy companies) – can be of great benefit for all participants.
To overcome the lack of trust currently still prevailing, data sovereignty concepts and services should be employed"</div>

## Business Use Cases Implementation

## Best practices identification and recommendations

## Gap or what is missing?

## TRL

## Comments

## Additional Information
