# Metadata and Discovery Protocol
## Definition
<div align="justify"> This building block incorporates publishing and discovery mechanisms for data resources and services, making use of common descriptions of resources, services, and participants. Such descriptions can be both domain-agnostic and domain-specific. They should be enabled by semantic-web technologies and include linked data principles. </div> 

## Role and Scope
<div allign="justify">Enables publication of offerings centred around data resources and services, making use of common descriptions of resources, services, and participants.</div>

## Features 
<details>
  <summary><strong>DSBA - CTO architecture coherence </strong></summary>
  
- Data Asset description
- Reuse of standards
- Standard metadata vocabulary for characterization of data resources
- Discovery service based on standard metadata vocabulary

</details>

## Components and Technologies  
<details>
  <summary><strong>i3-Market Project</strong></summary>
  
- Smart Contract Manager
- Auditable Accounting
- Offering registration
- Semantic mapping
- Vocabulary management
- Offering Discovery
- Semantic orchestrator
  
For more detailed information visit the [source's webpage.](http://open-source.i3-market.eu/technical-information/i3-market-architecture/)
  
</details>

<details>
  <summary><strong>TNO</strong></summary>
  
  - IDS Connector (including Access/Usage Control)
  - IDS Data Apps (and APIs)
  - IDS Broker
  - IDS DAPS
  - IDS Clearing House.

  In process of developing:
  - Vocabulary Hub
  - App Store
  - Federated Catalogue
  - Federated Identity Management. 
</details>

<details>
  <summary><strong>iSHARE Foundation</strong></summary>
  
  - <div align="justify"><a href="https://ishare.eu/ishare-satellite-explained/">iSHARE Satellite</a> federated participant registration service is providing a basic level of discovery for data spaces to discover participants in and across data spaces.</div>

</details>

<details>
  <summary><strong> EJP Soil / Isric world soil information / soil-x</strong></summary>
  
  - Metadata discovery: geonetwork and geonode
  - Data exchange api’s: pygeoapi, geoserver and mapserver
  - Data harmonization: hale and wosis (tailored)
  - Codelist registry: re3gistry and skosmos

</details>

<details>
  <summary><strong>H2020 InterConnect</strong></summary>
  
- In the InterConnect Semantic Interoperability Framework (SIF) the core component, the Knowledge Engine, unlocks the discovery and exchange of semantically modelled data.
</details>

<details>
  <summary><strong>SmashHit project</strong></summary>
  
Context Sensitivity Solution (CSS), comprising of the following sub-components:
  - Context monitoring & extraction: 
         - provides the main functionality for ingesting data from other smashHit components into the CSS, 
         - monitor and structure those data according to the predefined smashHit ontology model, and 
         - finally extract the contextual information from it.
  - CSS interfaces: 
         - provides REST API functionalities for communication with external modules, 
        - data ingestion as for the CSS extraction result provision

  </details>

## Technical Reference Implementation
<details>
  <summary><strong>Design Principles Position Paper</strong></summary>
  <div align="justify">A data space participant analyses the terms and conditions linked to a given data resource and acquires the corresponding access/usage rights in line with these terms and conditions.</div>
  
</details>

<details>
  <summary><strong>DASLOGIS - Dutch Data Spaces for Logistics</strong></summary>
  <div align="justify">The DASLOGIS project aims to develop a Dutch Logistics Data Space (DLDS): a digital virtual environment or ecosystem that enables the finding and controlled sharing of (potentially) sensitive data. It offers flexibility, extensibility, and personalization to support: sharing transaction data for operational optimization, sharing (big) data for data for data analysis, and supply chain data sharing for real-time visibility. DLDS will be based on the generic and internationally standardized IDS reference architecture model.</div>
  
</details>

<details>
  <summary><strong>iSHARE Foundation</strong></summary>
  
  - <div align="justify">The ledger node is available as a ready package to implement, and also as a service by multiple providers. It also allows data spaces to start today. 
  - Through the validation of the process of the governance organisations, parties can onboard participants in the bigger network. </div>

</details>

<details>
  <summary><strong>H2020 InterConnect</strong></summary>
  
- Since this is a custom tool, we applied interConnect's reference architecture, providing a tool that enables matching of data representations in order to activate data exchange. 
- The possibility to activate data exchange based on reasoning is currently on the road map. This feature will rely on metadata from the services. This can also be used to navigate a search space composed by the services and provided semantic descriptions.  
</details>

## Business Use Cases Implementation
<details>
  <summary><strong>DASLOGIS - Dutch Data Spaces for Logistics | iSHARE</strong></summary>
  
<div align="justify">To adapt to changing market dynamics, organizations are collaborating more than ever in increasingly complex and agile supply chains, requiring a flexible exchange of many (often commercially sensitive) datasets with a variety of stakeholders. Organizations in logistics are currently developing and implementing digitization strategies to adapt and prepare to extract value from these opportunities. This project builds on the work and analysis of the needs, approach, positioning and roadmap for a Dutch logistics data space in the published white paper on the logistics infrastructure for data sharing.</div>
  
</details>

<details>
  <summary><strong>EJP Soil / Isric world soil information / soil-x</strong></summary>
  
  - <div align="justify">Build a global soil dataset from regional sources. The global dataset is referenced in many domains from carbon stock, soil fertility to nature conservation.</div>
  - Support for governments in implementing solutions to share soil data following standards for wide adoption.

</details>

<details>
  <summary><strong>SmashHit project-x</strong></summary>
Solving Consumer Consent & Data Security for Connected Car and Smart City
Connected Car/Insurance Business Case:
This Business Case is focused on the use of connected car data in the insurance sector. 
The use of such data has been restricted so far because of two main reasons:
      1. Lack of trust by consumers regarding the use of their data.
      2. Complexity for the consumer to provide the consent required under GDPR.

To respond to this, this Business Case aims for a simpler and automated consent process and a process where the consumer is in full control of their consent. They can manage it, withdraw it, change it themselves at any time. 
This Business Case also addresses the privacy aspects of consent and ensuring GDPR compliance. By making the consent process simpler, secure, and GDPR compliant, it is believed that a larger number of consumers would adopt the use of connected car data for use in risk calculations by their insurer. 
The current structures and consent schemes in place today require a consumer to give their consent to multiple organisations separately, which has already proven to be an unrealistic approach in working with consumers. Within smashHit, LexisNexis and Volkswagen use, among others, the Context Sensitivity Solution with the aim to automate and simplify the consent process whilst ensuring transparency and clear accountability for consumers when buying connected car insurance.

  </details>
  
## Best practices identification and recommendations
<details>
  <summary><strong>TNO</strong></summary>
  
  - It's recommended that end-users don't develop the IDS components by themselves. Instead, they can use the services offered by IT integrators.
</details>

<details>
  <summary><strong>iSHARE Foundation</strong></summary>
  
  - There are at least two levels of discovery:
    - Starting from participants: that's where the iSHARE ledger provides the pointers to data offering of participants.
    - Starting from data offering: that's where market place components provide this for data spaces.

</details>

<details>
  <summary><strong>EJP Soil / Isric world soil information / soil-x</strong></summary>
  
  - Use standards where possible:
    - for data exchange (ogcapi, odata, sparql)
    - for metadata discovery (oaipmh, csw, opensearch)
    - for data models (inspire, soilml , glosis, schema.org)
    - for metadata content (dcat, iso19115, schema.org, datacite) 
  - Extend common codelists

</details>

<details>
  <summary><strong>H2020 InterConnect</strong></summary>
  
- Make sure the metadata includes references to the type of data that is produced and/or consumed by a service. This rich metadata makes the data sharing more flexible by for example enabling automatic semantic service composition using a reasoner. This increases the reuse potential for data and makes future related use case easier to implement.
</details>


## Gap or what is missing?
<details>
  <summary><strong>TNO</strong></summary>
  
  - Components related to federation of data spaces are still under active R&D and require more attention.
  - Governance and legal building blocks are still not completely defined. 
</details>

<details>
  <summary><strong>EJP Soil / Isric world soil information / soil-x</strong></summary>
  
  - Traceability is not a very common building block.
</details>

<details>
  <summary><strong>H2020 InterConnect</strong></summary>
  
- <div align="justify">The Knowledge Engine uses <a href="https://www.w3.org/TR/sparql11-query/#BasicGraphPatterns">Basic Graph Patterns</a> to describe the type of data that is being produced and/or consumed. These graph patterns are derived from the domain ontology, but they need some improvements. First of all, deriving them can be difficult. Tools to support this process are necessary to increase the adoption. Second of all, their expressive power can be increased. Note that the Knowledge Engine is research software and therefore not production-ready with respect to stability, scalability, security.</div>
</details>

## TRL

## Comments

## Additional Information
<details>
  <summary><strong>iSHARE Foundation</strong></summary>
  Further details on the details that are use for discovery in the <a href="https://ishare.eu/data-of-parties-in-ishare-network/">operational API's</a>.

</details>
