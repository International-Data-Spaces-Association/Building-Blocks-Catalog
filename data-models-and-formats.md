# Data Models and Formats

## Definition
<div align="justify">This building block establishes a common format for data model specifications and serialization  of data in data exchange payloads. Combined with the Data Exchange APIs building block, this ensures full interoperability among participants.</div>

## Role and Scope
It facilitates a common format for data model specifications and representation of data.

## Features 
<details>
  <summary><strong>DSBA - CTO architecture coherence</strong></summary>
  
- Standardized  data format for exchange of messages
- Common data Models agreed among participants
- Provide data Models
- Describe data format
</details>

<details>
  <summary><strong>i3-Market Project</strong></summary>
  
- Creation and registration of the data offering description
</details>

## Components and Technologies
<details>
  <summary><strong>i3-Market Project</strong></summary>
  
- Semantic Engine
- Semantic Model (OCASUS)
- i3-Market SDK-Generator
- Distributed storage, decentralized storage
- SDK-core; SDK-RI
</details>

<details>
  <summary><strong>Smart Connected Supplier Network</strong></summary>
  
  - Use of the Universal Business Language (UBL)
  - ERP system.
</details>

<details>
  <summary><strong>Datavillage</strong></summary>
  
  - Behavioral data mappers: components that map any behavioral data into the schema.org ontology are provided.
</details>

<details>
  <summary><strong>Platoon Project</strong></summary>
  
  - Vocabulary Provider
  - Data Usage App
  - DAPS
  - Semantic Data Models for energy
</details>

<details>
  <summary><strong>H2020 InterConnect</strong></summary>
  
  - Based on InterConnect's reference architecture, we have developed a pair of components: the Knowledge Engine and the Generic Adapter (part of InterConnect's Semantic Interoperability Framework), accounting for the "Data Exchange APIs" building block. 
  - Our methodology relies in the use of graph dissemination for discovery and data exchange. 
  - InterConnect relies on SAREF (ontology) as our main building block account for the "Data Models & Formats).
</details>

<details>
  <summary><strong>i4Trust</strong></summary>
  
  - Smart Data Models in different domains are being developed in collaboration with other organizations following a community-driven approach.
  - General information can be found [here](https://smartdatamodels.org/).
  - The space on github where data models are being created can be found [here](https://github.com/smart-data-models).
</details>

<details>
  <summary><strong>Reservist project (VTT)</strong></summary>
  
  - Data Models for the emergency domain utilizing json schema. 
  - A user interface to edit and render the data. 
  - IDS Connectors.
</details>

## Technical Reference Implementation
<details>
  <summary><strong>i3-Market Project</strong></summary>
  
- Pricing Model
- Contract Model
- Data Schema
- Relational Data Schema
</details>
<details>
  <summary><strong>Smart Connected Supplier Network</strong></summary>
  <div align="justify">SCSN is structured according to the four-corner model. The SCSN network is a network of networks in which all service providers/brokers are connected to each other. This enables every manufacturing company to communicate with all other manufacturing companies in the SCSN network, irrespective of the service providers to which the manufacturing companies are affiliated. This is made possible by strict technical and commercial agreements between the service providers, which are managed by the independent SCSN Foundation.</div>
  
  <a href="https://smart-connected.nl/en/about-scsn/how-it-works"><img src="images/SCSN-Graphic.jpg" alt="SCSN's webpage"></a>
</details>

<details>
  <summary><strong>City Dataspace</strong></summary>
    
1. Deploy batch data to the dataspace.
2. Provide streaming data to the dataspace.
3. Create semantic models for your data.
4. Find data
5. Create exports.
  <div align="justify">To know more about each step, visit the section <a href="https://www.city-dataspace.de/18-2/">Tutorials</a> of the City Dataspace webpage</div>
  <img src="images/City_Dataspace.png">
</details>

<details>
  <summary><strong>DSWEU - Energy consumption in non-residential buildings</strong></summary>
  <div align="justify">The <a href="https://i4trust.org/experiments/energy-consumption-in-non-residential-buildings/">experiment</a> will facilitate sharing of data using the standard NGSI-LD API to create digital twins. To develop more ambitious CO2-reduction projects for non-residential buildings, requires complete and up-to-date data on the measured energy consumption in relation to key construction features. With this data, Data Service Consumers can create digital twins of non-residential buildings, modelling the desired energy / CO2 reduction in various renovation scenarios for their clients.</div>
</details>

<details>
  <summary><strong>H2020 InterConnect</strong></summary>
  
  - InterConnect does not rely in any reference implementation of IDSA. Rather it built all the required components, that make the part of the SIF - Semantic Interoperability Framework. The SIF includes: 
    - The Knowledge Engine that handles the graph data exchange between parties.
    - The Generic Adapter that acts as a gateway to provide interoperability at digital services and devices.
    - The Service Store, acting as the repository of interoperable services (just as the "Publications and Marketplace" category for the "Data Value" building block. 
  - Most use-cases use the SIF as the key enabler to unlock interoperability that is directly geared by the use of the SAREF ontology; using it to demonstrate DSF solutions for flexibility exchange and actuation over smart appliances according to demand.
</details>

<details>
  <summary><strong>Open Geospatial Consortium</strong></summary>
  
<div align="justify">OGC suite are technical level interoperability standards, both abstract and encodings. They can contain transport, encodings and data models. Combining these based on the specification is a challenging and error-prone process. In addition, generic standards often require extensions (e.g. specific additional structures) and profiles (subsets and compilations). Ultimate interface or data model definition shall be maximally reusing existing data models, support translations between others, while preserving the semantics and provenance of data.</div></br>

<div align="justify">To enable semantic representations that will enable both logical and ontological model matching, the OGC Definition Server was developed. It is maintaining OGC standards ontologies models and some domain-specific ones that bridge to the abstract secifications models.</div>
  
</details>


<details>
  <summary><strong>i4Trust</strong></summary>
  
  - 800+ data models, covering a vocabulary of 18.000+ terms have already been defined on [GitHub](https://github.com/smart-data-models), following a community-driven approach. Models/vocabularies are growing fast.

  - [Portfolio](https://i4trust.org/experiments/) of pioneer use cases relying on the i4Trust framework and using smart data models in combination with NGSI-LD as basis for the data exchange.
</details>

<details>
  <summary><strong>Platoon Project</strong></summary>
  
  - Use W3C stacks and reflect multiple use cases for the energy value chain.
  - Have different reference impletemantions with different technological framework. 
  - Complete pipeline from heterogeneous data sources to semantic data / Knowledge graph that support data driven services (e.g. ML for forecasting ...)
</details>

## Business Use Cases Implementation
<details>
  <summary><strong>Design Principles Position Paper</strong></summary>
<div align="justify">The Smart Agrifood domain needs a common representation of agronomic data (e.g. crops, senso data from the field, multispectral imagery from UAVs, geolocation data, fertilisation logs, …). This common data model shall be used for all data exchanged between software components.</div>
</details>

<details>
  <summary><strong>i3-Market Project</strong></summary>
<div align="justify">"Data offering" allows to describe the capabilities and interfaces of an i3-MARKET data asset from a provider perspective and how this information can be used for discovery and access purpose but at the same time provides information towards the commercial use of the data asset.</div>
</details>

<details>
  <summary><strong>Smart Connected Supplier Network</strong></summary>
<div align="justify">The need of sharing data is crucial in low volume industry, like semiconductor industry. Nowadays, every industry adopts different standards and understandings of the same information, which provokes that a lot of work has to be done manually and it is not digitized. Furthermore, manual actions have a huge impact in the final price and they require extra effort. By using data standards and IDS components, the process is digitized, some errors are avoided and the effort is minimized. Besides, it enables the small manufacturing companies to join the digitalization process. Until now, they were sometimes excluded due to the high cost of hiring IT professionals (they have less budget).</div>
</details>

<details>
  <summary><strong>City Dataspace</strong></summary>
  <div align="justify">The City Dataspace focuses on the challenge of increasing and enabling the usability of Smart City relevant Open and Urban data using the example of mobility and geodata across municipal boundaries. It relies on the established semantic technologies, combined with new innovative concepts to simplify the use of the required technologies. This interoperability should enable app developers to develop an app once and roll it out to a large number of municipalities using the City Dataspace. Conversely, the City Dataspace enables municipalities to participate in existing apps just by making their data available.</div>
</details>

<details>
  <summary><strong>DSWEU - Energy consumption in non-residential buildings</strong></summary>
  <div align="justify">The idea is to test & showcasing the Dataspace Measured Energy Consumption in Non-Residential Buildings. To optimise the cost-effectiveness of CO2-reduction projects, non-residential building-owners need to share relevant data more easily but safely with their project partners.</div>
</details>

<details>
  <summary><strong>Wind and Solar Assets modeling - EDF</strong></summary>
  <div align="justify">The wind and solar description model is the digital backbone to federate all the businesses and its ecosystem around one single source of truth from “DESIGN, MODIFICATION to others REFRESHMENT”. Being able to share the same abstract representation of data for the wind and solar domain would allow a better understanding of the associated operations (asset management, RCA, Structural Analysis, Visual Inspection, monitoring ...) and an obvious improvement of the processes that mobilize the processing of this information.</div>
</details>

<details>
  <summary><strong>Platoon Project</strong></summary>
  
  <div align="justify">It aims to digitalise the energy sector, enabling thus higher levels of operational excellence with the adoption of disrupting technologies. PLATOON will deploy distributed edge processing and data analytics technologies for optimized real-time energy system management in a simple way for the energy domain expert. Moreover, it will contribute to increased renewable energy consumption, smart grids management, increased energy efficiency and optimised energy asset management.</div>
</details>

<details>
  <summary><strong>H2020 InterConnect</strong></summary>
  <div align="justify">The solutions developed within the scope of InterConnect will allow a digitalisation of homes, buildings and electric grids based on an Internet of Things (IoT) architecture. By including digital technologies (Artificial Intelligence, Blockchain, Cloud and Big Data) based on open standards, such as SAREF, it will guarantee the interoperability between equipment, systems and privacy/cybersecurity of user data.</div>
</details>

<details>
  <summary><strong>SmashHit Project</strong></summary>
  
  - An organization (A) asking a data owner for consent to receive and process data from their connected car, which an OEM organization (B) must facilitate.
In this setup, organization A would need to use the consent manager to fill a template with the terms of this consent such as the purpose of the consent, actors involved (A and B), or personal data to be processed. After this first step, A can start asking their customers for consent as defined in the template and ask the consent manager to process the response. The consent manager automatically handles the certification, signature, and safe keeping of this consent, while also notifying the rest of the actors affected (in this case B, the OEM), so that they can enforce the consent given by the data owner.
- The data owner is also automatically registered in the manager, so that they can review and revoke any given consent at any point in time directly from the consent manager itself.
  
  ![image](https://user-images.githubusercontent.com/95075534/194383186-9d367439-d150-49f5-85ef-1522ac6456e4.png)
            Scenario: consent creation

</details>

## Best practices identification and recommendations

<details>
  <summary><strong>Datavillage</strong></summary>
  
  - Use simple and basic ontology to start with and extend with specific ontology when required. 
  - In a user centric data space, use a user centric data model
</details>

<details>
  <summary><strong>Platoon Project</strong></summary>
  
  - Ability to provide separate information if required.
  - Development of a complete methodology for building models that will be reused in coming EU energy data spaces (OMEGAX and Enershare - HORIZON-CL5-2021-D3-01-01) as well DATAMITE (HORIZON-CL4-2022-DATA-01-04) for Data valorization.
</details>

<details>
  <summary><strong>Open Geospatial Consortium</strong></summary>
  
  - There is also key governance aspect that needs to be handled and preserved to sustain usefulness and completeness. 
  - Governance needs to be supported by some technical tools and policies.
  
</details>

<details>
  <summary><strong>i4Trust</strong></summary>
  
  - Publication of common data models free of royalties is essential.
  - A community and implementation (driven approach) is key.
  - Within the Smart Data Models initiative the proposed data models require a project, therefore a real business case behind.
</details>

## Gap or what is missing?
<details>
  <summary><strong>Platoon Project</strong></summary>
  
  - Vocabulary provider
  - Link with other IDS components (e.g. Broker)
  - Extend the SDMs to other Cross sector Use cases. 
  - Align with other SDM that were not detected during the assesment.
</details>


<details>
  <summary><strong>H2020 InterConnect</strong></summary>
  
  - Our approach was to gear data exchange in a full semantic approach relying not only in graph representations of data and ontology engineering to build the needed graphs. If there is intention to follow this approach in the near future, tools will be required to automate, assist and validate the data representations, as this is yet not a common feature for industry to have. InterConnect has developed some of this tools, may be considered in the ecosystem.
</details>

<details>
  <summary><strong>Open Geospatial Consortium</strong></summary>
  
  - Formal definitions are not always easy to adapt, which is not the gap cannot be filled on the adopter's side, but the thresholds if high.
  - The governance administration is internal, while it is not clear if it could be better aligned to the Access & Usage Policies building block.
  - Implementation of the Data Usage and Accounting, and Publication & Marketplace Solutions could be helpful.
  - Provenance and traceability support is not stable.
  
</details>

<details>
  <summary><strong>i4Trust</strong></summary>
  
  - Definition of data models / vocabularies is a task that requires constant attention.
</details>

## TRL

## Comments
<details>
  <summary><strong>Smart Connected Supplier Network</strong></summary>
  
  Results:
  - Cross-factory communication is facilitated.
  - By ensuring supply chain transparency and interoperability, the overall productivity has improvement of 20%.
  - The transaction costs of the supply chain are reduced.
</details>

<details>
  <summary><strong>Platoon Project</strong></summary>
  
  - App concept in IDS has several limitations that should be overcome.
  - PLATOON SDMs will be considered for Common data models for Energy, Home, Mobility @ EU LEVEL
</details>

## Additional Information

<details>
  <summary><strong>Platoon Project</strong></summary>
  
  - More info can be found [here](https://platoon-project.eu/)
</details>

<details>
  <summary><strong>H2020 InterConnect</strong></summary>
  
  - [Use Cases, Business Models and Services](https://interconnectproject.eu/wp-content/uploads/2022/02/InterConnect_WP1_D1.1_v2.2.pdf)
  - [Mapping between use cases and large-scale pilots](https://interconnectproject.eu/wp-content/uploads/2021/02/D1.2-Mapping-between-use-cases-and-large-scale-pilots_DraftVersion.pdf)
  
  ![InterConnect Use Cases](/images/Interconnect_Additional_info.png)
</details>

<details>
  <summary><strong>i4Trust</strong></summary>
  
  - Smart Data Models initiative [website](https://smartdatamodels.org/)
  - Smart Data Models initiative on [GitHub](https://github.com/smart-data-models)
</details>
