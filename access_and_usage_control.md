# Access and usage control
## Definition
<div align="justify">This building block guarantees enforcement of data access and usage policies defined as part of the terms and conditions established when data resources or services are published (see ‘Publication and Services Marketplace’ building block below) or negotiated between providers and consumers. A data provider typically implements data access control mechanisms to prevent misuse of resources, while data usage control mechanisms are typically implemented on the data consumer side to prevent misuse of data. In complex data value chains, both mechanisms are combined by prosumers. Access control and usage control rely on identification and authentication.</div> 

## Role and Scope
<div allign="justify">Enforces different data access and usage policies that ensure trustworthiness of data sharing and exchange between participants.</div>

## Features 
### DSBA - CTO architecture coherence
- Access Control
- Usage Control
- Policy rules definition language
- Enforcement of policy rules
- Policy administration and management
- Definition of credentials / roles
- Usage Control for data sovereignty

## Components and Technologies
### DSBA - CTO architecture coherence
- Policy Enforcement based on XACML, extend with PXP for Usage Policy Enforcement. 
- IDSA: ODRL, XACML-oriented framework (PEP-PDP-PIP-PDP), Custom PAP
- FIWARE: XACML-like (iSHARE  delegation evidence data model, JSON port of XACML) implemented in Keyrock, XACML-based PEP-PDP-PAM framework, API Umbrella is iSHARE-compliant (github, Tutorials), XACML-based implemented in Keyrock (with AuthZForce component (ReadTheDocs), DID.

### i3-Market Project
- Blockchain Framework
- HW Wallet
- Explicit-User consent

## Technical Reference Implementation
### Design Principles Position Paper
<div allign="justify">Enforcing Data Protection Regulations in Health Care Applications. When a company is processing patient records for the sake of accounting an billing as a service to doctors and insurances, it is thus in the interest of the company to ensure that it complies to those regulations.</div>

## Business Use Cases Implementation

## Best practices identification and recommendations

## Gap or what is missing?

## TRL

## Comments

## Additional Information
