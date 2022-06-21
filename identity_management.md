# Identity Management (IM)

## Definition
<div align="justify">The IM building block allows identification, authentication, and authorisation of stakeholders operating in a data space. It ensures that organisations, individuals, machines, and other actors are provided with acknowledged identities, and that those identities can be authenticated and verified, including additional information provisioning1, to be used by authorisation mechanisms to enable access and usage control. The IM building block can be implemented on the basis of readily available IM platforms that cover parts of the required functionality.</div>

## Role and Scope
<div allign="justify">Provides authentication and authorisation of data space participants.</div>

## Features 1
**[TODO:] ASK FOR A DEFINITION OF FEATURES 1** 
<details>
  <summary><strong>DSBA - CTO architecture coherence</strong></summary>
  
- Identification
- Authentication
- Authorization policy description language
- Authorization framework	
</details>

## Components and Technologies 1
<details>
  <summary><strong>Design Principles Position Paper</strong></summary>
  
<div align="justify">Examples of open-source solutions are the KeyCloak infrastructure, the Apache Syncope IM platform52, the open-source IM platform of the Shibboleth Consortium53, or the FIWARE IM framework54. It would be particularly important to integrate the IM building block with the eID building block of the Connecting Europe Facility (CEF)55 supporting electronic identification of users across Europe.</div></br>

Creation of federated and trusted identities in data spaces can be supported by European regulations such as EIDAS.

</details>

<details>
  <summary><strong>DSBA - CTO architecture coherence</strong></summary>
  
  
  **[TODO:] ASK FOR A DEFINITION OF LEVELS**
  
#### Level 1: Participant (organization, trusted party)
- eIDAS
- X.509
- VC/VP (planned)
- OpeniD/OAuth2 + iSHARE Satellite (current)
- Verifiable Data Registry (planned)
- OAuth2
- Participant Information Service as extension to Meta Data Broker
- OpenID Connect
- DID
- XACML variant by iSHARE (current)
- TBD (planned)
- XACML (recommended)
- XACML
- PEP-PDP-PAP

#### Level 2: Container or application execution environment.
(e.g. Connector)
- X.509
- DAT signed DAPS to coexist with VC/VP (planned)
- DAT signed DAPS (Oauth2 based),to coexist with VC/VP (planned)
- IDS ODRL-based to be reconciled with TBD (planned)
- ODRL (For usage control)
- Evolution of IDS Connector
- ODRL based
- PEP-PDP-PIP-PAP

#### Level 3: Application context/Users (individuals)
- User + password (current)
- VC/VP (planned)
- OpenID/OAuth2 (current)
- Verifiable Data Registry (planned)
- XACML variant by iSHARE (current)
- TBD (planned)
- ODRL (For usage control, applications), user behavior can be implemented regarding use case and environment.
- XACML
- PEP-PDP-PAP

</details>

<details>
  <summary><strong>i3-Market Project</strong></summary>
  
User-centric Authentication.
- W3C Verifiable 
- Credentials Data Model 1.0
- W3C Decentralized Identifiers (DIDs) v1.0
  
</details>

## Features 2
**[TODO:] ASK FOR A DEFINITION OF FEATURES 2** 
<details>
  <summary><strong>DSBA - CTO architecture coherence</strong></summary>
  
- Digital Identities and Authentication
- Digital Identities
- Authorization
- Identification & Authentication of Organisations, individuals, machines, etc.
- Authorization framework	

</details>
  
## Components and Technologies 2
<details>
  <summary><strong>DSBA - CTO architecture coherence</strong></summary>
  
#### Level 1: Participant (organization, trusted party)
- W3C
- Verifiable Credentials
- X.509
- PKI
- CA

#### Level 2: Participant Information Service
- JWT

#### Level 3: Application context/Users (individuals)
- Keyrock IDM, which supports SSO [OpenID Connect](https://openid.net/connect/)/[OAuth2](https://oauth.net/2/), 2-FactorAuth and LDAP federation (currently)
- DID/VC/VP integration into i4Trust architecture for BC assisted authorization (under design, [architecture](https://github.com/hesusruiz/PrivacyCredentials/blob/main/docs/architecture/privacy-architecture.md))

<img src="images/Identity_Management_Components2.png" width="640" align="center"> </br>
  
</details>

## Technical Reference Implementation
<details>
  <summary><strong>Design Principles Position Paper</strong></summary>
  
<div allign="justify">A user within an organisation registered with a data space provides his/her log-in credentials to the IM module in order to gain access to the data of the data space in line with his/her role in the organisation.</div>
</details>

## Business Use Cases Implementation
<details>
  <summary><strong>Catena X</strong></summary>
<div allign="justify"></div>

</details>
  
## Best practices identification and recommendations
<details>
  <summary><strong>i3-Market Project</strong></summary>
  
<div allign="justify">W3C Verifiable Credentials specification provides a standard way to express credentials on the Web being cryptographically secure, privacy respecting, and machine-verifiable.</div>
  
</details>

## Gap or what is missing?

## TRL

## Comments

## Additional Information
