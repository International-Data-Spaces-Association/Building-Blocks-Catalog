# Access and usage control
## Definition
<div align="justify">This building block guarantees enforcement of data access and usage policies defined as part of the terms and conditions established when data resources or services are published (see ‘Publication and Services Marketplace’ building block below) or negotiated between providers and consumers. A data provider typically implements data access control mechanisms to prevent misuse of resources, while data usage control mechanisms are typically implemented on the data consumer side to prevent misuse of data. In complex data value chains, both mechanisms are combined by prosumers. Access control and usage control rely on identification and authentication.</div> </br>

<details>
  <summary><strong>DSBA - CTO architecture coherence: Definition of concepts</strong></summary>
  
  - [Access Control](https://www.techopedia.com/definition/5831/access-control)
  
    <div align="justify">Access control is a way of limiting access to a system or to physical or virtual resources. In computing, access control is a process by which users are granted access and certain privileges to systems, resources or information.In access control systems, users must present credentials before they can be granted access. In physical systems, these credentials may come in many forms, but credentials that can't be transferred provide the most security. </div>
  
  - [Usage Control](https://www.igi-global.com/dictionary/hardware-approach-trusted-access-usage/31145)
  
    <div align="justify">Usage Control complements access control with contextual predicates, conditioning the activation of a given privilege, and obligations, i.e., mandatory actions associated to the exercise of a privilege.</div>
  
  - PIP/Directory Service
  
    <div align="justify">Where does the information come from to evaluate the rules from the policies and where to provide it. (Scope, roles, attributes).</div>
    <img src="images/Access_and_Usage_PIP.png" width="640" align="center"></br>
</details>

## Role and Scope
<div allign="justify">Enforces different data access and usage policies that ensure trustworthiness of data sharing and exchange between participants.</div>

## Features 
<details>
  <summary><strong>DSBA - CTO architecture coherence</strong></summary>
 
- Access Control
- Usage Control
- Policy rules definition language
- Enforcement of policy rules
- Policy administration and management
- Definition of credentials / roles
- Usage Control for data sovereignty
  
</details>

## Components and Technologies
<details>
  <summary><strong>DSBA - CTO architecture coherence</strong></summary>
  
- Policy Enforcement based on XACML, extend with PXP for Usage Policy Enforcement.
  
  Policies for Access Control and Usage Control should be managed in a similar way and should base on the same policy language. Therefore, the execution environments of both parties (data provider and data consumer) have to include some relevant components:
  
    - PAP Policy Administration Point: User interface to administer policies.
    - PDP Policy Decision Point: Evaluation of policies depending on context information.
    - PEP Policy Enforcement Point: Modification of data based on evaluation of PDP.
    - PIP Policy Information Point: Adding relevant context information (e.g. Scope, roles, attributes) to decide on policies, in distributed scenarios, e.g. Data Usage Policies, this could be a distributed /federated approach.
      <details>
        <summary>Detailed information about the PIP</summary>
        The policy information point might provide identity and authentication related data for (a) organizations, (b) Application execution environments and (3) individuals (Level 1, Level 2, Level 3). And additional attributes that are required for policy decisions on the object (data or service) and environment attributes. See figure below (source: NIST  Special  Publication  800-162,Guide  to  Attribute  Based  Access Control  (ABAC)  Definition and Considerations):
        <img src="images/Access_and_Usage_Details_PIP.png" width="640" align="center"></br>
      </details>
  
    - PMP Policy Management Point: Provisioning of actual policies.
    - PXP Policy Execution Point: Execution of activities from the policies _after_ data exchange and Enforcement of policies in PEP.
  
  <img src="images/Access_and_Usage_Policy_Enforcement_based_on_XACML.png" width="640" align="center"></br>
  
- IDSA: ODRL, XACML-oriented framework (PEP-PDP-PIP-PDP), Custom PAP
- FIWARE: XACML-like (iSHARE  [delegation evidence data model](https://dev.ishareworks.org/delegation/delegation-evidence.html), JSON port of XACML) implemented in Keyrock, XACML-based PEP-PDP-PAM framework, API Umbrella is iSHARE-compliant ([github](https://github.com/i4Trust/building-blocks#integrating-building-blocks-for-the-creation-of-i4trust-data-spaces), [Tutorials](https://github.com/i4Trust/tutorials)), XACML-based implemented in Keyrock (with AuthZForce component ([ReadTheDocs](https://authzforce-ce-fiware.readthedocs.io/en/latest/)), DID/VC/VP, FIWARE TRUE Connector component based on the MyData Framework ([github](https://github.com/Engineering-Research-and-Development/fiware-true-connector)).
  
</details>

<details>
  <summary><strong>i3-Market Project</strong></summary>
  
- Blockchain Framework
- HW Wallet
- Explicit-User consent
- Backplane API

<img src="images/Access_i3_Market.png" width="640" align="center"></br>

</details>

<details>
  <summary><strong>Resilience and Sustainability Data Space - ADVANEO</strong></summary>
  
  - IDSA and GAIA-X standards
  - ADVANEO's Trusted Data Hub
  - IDS Components: broker, connector, clearing house and app provider
</details>

<details>
  <summary><strong>Intelligent Washing Machine - Haier | Fraunhofer ISST</strong></summary>
 
  - COSMOPlat
  - IDS connector 
  - RFID sensor
</details>
  
## Technical Reference Implementation
<details>
  <summary><strong>Design Principles Position Paper</strong></summary>
  <div align="justify">Enforcing Data Protection Regulations in Health Care Applications. When a company is processing patient records for the sake of accounting an billing as a service to doctors and insurances, it is thus in the interest of the company to ensure that it complies to those regulations.</div>
  
</details>

<details>
  <summary><strong>Intelligent Washing Machine - Haier | Fraunhofer ISST</strong></summary>
  <div align="justify">Through sensors within washing machines laundry data can be collected, which enables companies to offer their consumers a better utilization of washing machines with additional services. This data is sent to COSMOPlat for optimizing washing programs through ML. The optimized washing programs are sent back to the consumers washing machines to save energy, time, and costs, as well as it reduces the carbon footprint and will lead to longer lasting garments.</div>
  
</details>

## Business Use Cases Implementation
<details>
  <summary><strong>truzzt box</strong></summary>
  <div align="justify">In the <a href="https://www.truzzt.com/en/">truzzt box</a> your documents are always available for you and you are always in control, not even truzzt has access to your personal documents. As a verified user of your truzzt box you always know who you are dealing with, you only buy from real, verified merchants and personal data will always remain encrypted and safe. Besides. The truzzt box will automatically adapt to your usage with its artificial intelligence. </div>
  
</details>

<details>
  <summary><strong>Resilience and Sustainability Dataspace - ADVANEO</strong></summary>
  <div align="justify">Companies and organizations as users of the <a href="https://www.resilience-sustainability-dataspace.eu/">Resilience and Sustainability Dataspace</a> benefit from the data-based approach of a digital infrastructure to integrate decentralized information in a protected virtual space. With this infrastructure users are either able to apply already implemented services or to develop new services supporting our users in order to gain new insights and knowledge about. In the end, this enables users to seamlessly build their own trustworthy resilience and sustainability ecosystems. </div>
  
</details>

## Best practices identification and recommendations

## Gap or what is missing?

## TRL

## Comments

## Additional Information
