# Metadata and Discovery Protocol
## Definition
<div align="justify"> This building block incorporates publishing and discovery mechanisms for data resources and services, making use of common descriptions of resources, services, and participants. Such descriptions can be both domain-agnostic and domain-specific. They should be enabled by semantic-web technologies and include linkeddata principles. </div> 

## Role and Scope
<div allign="justify">Enables publication of offerings centred around data resources and services, making use of common descriptions of resources, services, and participants.</div>

## Features 
<details>
  <summary><strong>DSBA - CTO architecture coherence [DRAFT. NOT APPROVED]</strong></summary>
  
- Data Asset description
- Reuse of standards
- Standard metadata vocabulary for characterization of data resources
- Discovery service based on standard metadata vocabulary

</details>

## Components and Technologies
<details>
  <summary><strong>DSBA - CTO architecture coherence [DRAFT. NOT APPROVED]</strong></summary>
  
- FIWARE: 
  - [TM Forum APIs specifications](https://projects.tmforum.org/wiki/display/API/Open+API+Table) (in the product description) or in CKAN in the dataset description
  - [W3C DCAT v2](https://www.w3.org/TR/vocab-dcat-2/)
  - [DCAT-AP](https://joinup.ec.europa.eu/collection/semantic-interoperability-community-semic/solution/dcat-application-profile-data-portals-europe) ([DCAT-AP 1.1](https://joinup.ec.europa.eu/collection/semantic-interoperability-community-semic/solution/dcat-application-profile-data-portals-europe/release/11) → [DCAT-AP 2.0.0](https://joinup.ec.europa.eu/collection/semantic-interoperability-community-semic/solution/dcat-application-profile-data-portals-europe/release/200))
  - FIWARE [Idra](https://github.com/OPSILab/Idra) component, supporting federation with most popular data publication platforms (CKAN, SOCRATA, DKAN, etc)
- IDSA: 
  - [IDS Informodel](https://w3id.org/idsa/core)
  - [ids](https://w3id.org/idsa/core)
  - [idsm](https://w3id.org/idsa/metamodel)
  - [code](https://w3id.org/idsa/code)
  - [dcam](http://purl.org/dc/dcam)
  - [ns](http://creativecommons.org/n)
  - [owl](http://www.w3.org/2002/07/owl)
  - [freq](http://purl.org/cld/freq)
  - [xsd](http://www.w3.org/2001/XMLSchema)
  - [schema-org](https://schema.org)
  - [skos](http://www.w3.org/2004/02/skos/core)
  - [rdfs](http://www.w3.org/2000/01/rdf-schema)
  - [rfc3986](https://tools.ietf.org/html/rfc3986)
  - [shacl](http://www.w3.org/ns/shacl)
  - [docs](https://postgis.net/docs)
  - [rfc7519](https://tools.ietf.org/html/rfc7519)
  - [dcterms](http://purl.org/dc/terms)
  - [wgs84](http://www.w3.org/2003/01/geo/wgs84_pos)
  - [holdings](https://www.loc.gov/marc/holdings)
  - [dcat](http://www.w3.org/ns/dcat)
  - [locn](http://www.w3.org/ns/locn)
  - [vann](http://purl.org/vocab/vann)
  - [foaf](http://xmlns.com/foaf/0.1)
  - [geonames](http://www.geonames.org/ontology)
  - [spec-md](https://github.com/cloudevents/spec/blob/master/spec.md)
  - [void](http://rdfs.org/ns/void)
  - [org](http://www.w3.org/ns/org)
  - [resource](http://dbpedia.org/resource)
  - [resource](http://purl.org/vocommons/voaf)
  - [url](https://www.gnu.org/software/emacs/manual/html_node/url)
  - [geosparql](http://www.opengis.net/ont/geosparql)
  - [rdf](http://www.w3.org/1999/02/22-rdf-syntax-ns)
  - [time](http://www.w3.org/2006/time)
  - [odrl](http://www.w3.org/ns/odrl/2)

</details>
  
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

## TRL

## Comments

## Additional Information
<details>
  <summary><strong>iSHARE Foundation</strong></summary>
  Further details on the details that are use for discovery in the <a href="https://ishare.eu/data-of-parties-in-ishare-network/">operational API's</a>.

</details>
