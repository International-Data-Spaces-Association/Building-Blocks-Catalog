# Data Exchange APIs

## Definition
<div align="justify"> This building block facilitates the sharing and exchange of data (i.e., data provision and data 
  consumption/use) between data space participants. An example of a data interoperability building block is the ‘Context Broker’ 
  of the Connecting Europe Facility (CEF),  which is recommended by the European Commission for sharing right-time (near real-time) data 
  among multiple organisations.</div> 

## Role and Scope
<div allign="justify">Facilitates data sharing and exchange between data space participants, ensuring semantic interoperability of 
  data and data sources.</div>

## Features 
<details>
  <summary><strong>DSBA - CTO architecture coherence [DRAFT. NOT APPROVED]</strong></summary>
  
- Common API for exchange of digital twin data among participants, supporting: 
  - updates
  - queries (including geo-queries)
  - notifications
  - federation
- Extend protocols with metadata
- Handshake
- REST
- HTTP Multipart
- IDSCP (V2)
  
</details>

## Components and Technologies
<details>
  <summary><strong>i3-Market Project</strong></summary>
  
- DCAT-AP
  
</details>

<details>
  <summary><strong>EGI-ACE</strong></summary>
  
  - EGI DataHub, based on Onedata technology.
</details>

<details>
  <summary><strong>i4Trust</strong></summary>
  
  - FIWARE Context Broker technology implementing the standard ETSI NGSI-LD data exchange API.
</details>

<details>
  <summary><strong>Open Geospatial Consortium</strong></summary>
  
  - OGC APIs and OWS building blocks for spatial data exchange including Features, Things, rasters, Observations and many more. 
  - Semantic support is provided by the Vocabulary hub that is hosting OGC specific models but also some domain models, mapping between various ontologies and profiles.
</details>

<details>
  <summary><strong>IDSA Hub Finland </strong></summary>
  
  - IDS connector
  - Eclipse Milo - open source implementation of OPC UA.
</details>


## Technical Reference Implementation

<details>
  <summary><strong>Design Principles Position Paper</strong></summary>
  
<div align="justify">A smart city needs to calculate its environmental performance on the basis of a collection and aggregation of 
  information about all the sustainability projects in its urban environment. This information is shared by different stakeholders, 
  who use different formats and semantics to report CO2 emissions and other indicators. The building block enables syntactic and 
  semantic harmonization of the different data sources, as well as effective exchange of data using a common data exchange API to 
  enable the calculation of the KPIs (key performance indicators) needed.</div>
</details>

<details>
  <summary><strong>DSBA - CTO architecture coherence [DRAFT. NOT APPROVED]</strong></summary>
  
[OpenApi data app](http://market40.eu/wp-content/uploads/MARKET4.0-OC1-winners-2nd-Webinar-OpenAPI-Data-Open.pdf)
</details>

<details>
  <summary><strong>EGI-ACE</strong></summary>
  
  - Creation of Virtual Spaces abstracting physical file location. 
  - Exchange of data between distributed data providers and file publication and sharing.
  - Use of REST API or CDMI API.
</details>


<details>
  <summary><strong>i4Trust</strong></summary>
  
  - Several reference open source implementations of NGSI-LD can be found in the [FIWARE Catalogue](https://github.com/FIWARE/catalogue#core-context-broker-components).
  - [Portfolio](https://i4trust.org/experiments/) of pioneer use cases relying on the i4Trust framework and using NGSI-LD as basis for the data exchange.

</details>

<details>
  <summary><strong>Open Geospatial Consortium</strong></summary>
  
  <div align="justify">OGC suite are technical level interoperability standards, both abstract and encodings. They can contain transport, encodings and data models. Combining these based on the specification is a challenging and error-prone process. In addition, generic standards often require extensions (e.g. specific additional structures) and profiles (subsets and compilations). Ultimate interface or data model definition shall be maximally reusing existing data models, support translations between others, while preserving the semantics and provenance of data.</div></br>
  
  <div align="justify">To enable semantic representations that will enable both logical and ontological model matching, the OGC Definition Server was developed. It is maintaining OGC standards ontologies models and some domain-specific ones that bridge to the abstract secifications models.</div>
</details>

<details>
  <summary><strong>IDSA Hub Finland </strong></summary>
  
  - IDS connector implementation with OPC-UA support. 
  - The connector enables exchanging data retrieved from OPC-UA servers.
</details>


## Business Use Cases Implementation

<details>
  <summary><strong>Design Principles Position Paper</strong></summary>
  
- Domain Data Standard: In manufacturing data spaces, a combination of different standards is used to describe the syntax and semantics of data transactions (e.g. ISO 10303, Asset Administration Shell, eCl@ss).
  
</details>

<details>
  <summary><strong>IDS Hub Finland</strong></summary>
  
- INDEX  - Industrial Data Excellence
  We have used it in the Index project in the Smart Manufacturing use case. It enables the secure exchange of data among manufacturing machines that deploy heterogeneous interfaces and communication protocols. There is a description of the project https://www.dimecc.com/dimecc-services/index/ 
  ![image](https://user-images.githubusercontent.com/95075534/194386301-7e25c8e9-dc5c-4dc7-97e3-368d5b1640ad.png)

  </details>
  
## Best practices identification and recommendations

<details>
  <summary><strong>Design Principles Position Paper</strong></summary>
  
<div align="justify">To ensure interoperability between all data space participants, the technical measures need to be continuously maintained. This includes general agreements and domain specific models. The continuity model provides measures for change, release, and version management.</div></br>
  
- Domain Data Standard: It provides the syntax and semantics for data exchange and data sharing on different levels, in a specific sector or domain. To achieve specific goals, multiple standards can be used in combination. 

</details>

<details>
  <summary><strong>Deutsche Telekom - Data Intelligence Hub</strong></summary>
  <div align="justify">The <a href="https://dih.telekom.net/en/">Telekom - Data Intelligence Hub</a> is intended to serve as a digital connection between companies and be both a source for commercial data acquisition and open data. The platform offers users tools for analysis, acquisition, exchange and processing of data. Industry experts get the possibility to develop new business models, data-driven products or services. It is relevant for companies of all sizes and industries but also for universities, for example, that develop models for the combination of data and algorithms to attain new insights.</div>
</details>

<details>
  <summary><strong>EGI-ACE</strong></summary>
  <div align="justify">DataHub allows you to bring data close to  computing to exploit it efficiently, and to publish a dataset and make it available to a specific community, or worldwide, across federated sites.</div>
</details>

<details>
  <summary><strong>i4Trust</strong></summary>
  
  - Adoption of a common data exchange API is key to foster innovation in data spaces.
  - Common data models (defining vocabulary and semantics associated to that vocabulary) are required.

</details>

<details>
  <summary><strong>Open Geospatial Consortium</strong></summary>
  
  - There are some ontologies and models already in use, practical usage examples. 
  - There is also key governance aspect that needs to be handled and preserved to sustain usefulness and completeness. 
  - Governance needs to be supported by some technical tools and policies.
</details>

## Gap or what is missing?
<details>
  <summary><strong>EGI-ACE</strong></summary>
  
  - More standard API for data access and exchange (e.g. S3)
  - Access to relational or NoSQL DB.
</details>

<details>
  <summary><strong>i4Trust</strong></summary>
  
  - Data exchange based on streaming is required.  The ETSI NGSI-LD standard API is evolving to cover this aspect but some Context Brokers have not yet implemented all latest features of NGSI-LD.
</details>

<details>
  <summary><strong>Open Geospatial Consortium</strong></summary>
  
  - Formal definitions are not always easy to adapt, which is not the gap cannot be filled on the adopter's side, but the thresholds if high.
  - The governance administration is internal, while it is not clear if itcould be better aligned to the Access & Usage Policies building block.
  - Implementation of the Data Usage and Accounting, and Publication & Marketplace Solutions could be helpful.
  - Provenance and traceability support is not stable.
</details>


## TRL

## Comments

## Additional Information
<details>
  <summary><strong>EGI-ACE</strong></summary>
  
  - [EGI - Datahub](https://www.egi.eu/service/datahub/)
</details>


<details>
  <summary><strong>i4Trust</strong></summary>
  
  - Latest version of the [specs](https://www.etsi.org/committee/cim).
  - NGSI-LD is being adopted worldwide as a minimum interoperability mechanism for data exchange by cities. For example, in India has been adopted by the Bureau of Indian Standards.
</details>

  <details>
  <summary><strong>IDS Hub Finland</strong></summary>
  
- INDEX  - Industrial Data Excellence
  More information: https://www.famn.fi/news/smart-factory-prototype-and-other-index-program-results-published/
  </details>
