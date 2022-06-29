# Building-Blocks-Catalog
This is the repository to list the building blocks developed in OPEN DEI project.

## Introduction to Building Blocks
<div align="justify">The different building blocks can be specified and developed independently of each other.  When doing so, existing norms, standards, and best practices should be used to ensure  cohesion of building blocks. Each data space solution can integrate multiple building blocks, as long as they are in line with data space reference architectures (e.g., the IDS Reference Architecture Model49). The building blocks presented in this chapter are core elements of any data space. As such, they can be considered sector-agnostic. Nevertheless, they can be used in sector-specific scenarios (see e.g. seaport scenarios). Data space stakeholders may also define additional building blocks to support innovative features and functions. For instance, data space architects may introduce building blocks that enable novel types of data space architectures combining centralised and decentralised approaches. Likewise, business stakeholders may introduce building blocks that enable novel forms of smart contracts to be agreed upon by participants of a data space, thereby facilitating business model innovations. Hence, the building blocks presented in this chapter are not exhaustive, but rather indicative of the elements of a data space. In general, each building block consists of reusable, generic components (i.e. which can be used across domains and industries) and more specific components (i.e. to meet requirements and regulations that are specific for certain industries, domains, or even concrete use cases). This allows individual participants to join different data spaces, use data in multiple contexts and scenarios, and be part of multiple data value chains.</div>

## Taxonomy of Building Blocks	
The taxonomy of building blocks constituting a data space will benefit various stakeholders:
- **Data space architects and integrators** will be provided with a structured way for identifying the components required for their specific architecture.
- **Building block developers** will be a given a clear description on how their components can fit into the specific architecture of a data space.
- **Business managers** will be able to identify business model candidates for data sharing and exchange (including data monetisation) in the context of a specific data space.
- **Data space policy managers** will have access to building blocks that can be used to specify and enforce data space related policies (e.g., data access policies, privacy control policies).

## Interoperability Building Blocks
<div align="justify">These building blocks should be deployed by all data providers and data consumers participating in a data space. This way, each data provider can be sure that any data published can be technically consumed by any data consumer entitled to do so, while each data consumer can be sure they are able to technically access and use any data made available by any data provider selected. The following building blocks belong to this category:</div>

- [Data Models and Formats](./data-models-and-formats.md)
- [Data Exchange APIs](./data-exchange-APIs.md)
- [Data Provenance and Traceability](./provenance_and_traceability.md)

## Data sovereignty and trust Building Blocks
<div align="justify">Data sovereignty and trust Building Blocks regaining control over their data, and as data becomes portable between providers on a  user-controlled consent basis. Users can switch between providers without losing their data  and vendor lock-in will become a phenomenon of the past. For participants in data spaces, data sovereignty means two things:</div></br>

1. Benefit from enhanced possibilities to view, process, manage, and secure their data.
2. Stay in control over their data when making it accessible to other parties.

<div align="justify">These building blocks includes the data ownership policies that requires agile and standardised ICT capabilities when such agreements are to be negotiated dynamically. We need to establish a semantic interoperability of policiesand behavioural interoperability of policies.</div>

The building blocks that provides data sovereignty and trust are:
- [Identity Management (IM)](./identity_management.md)
- [Access and Usage Control/Policies](./access_and_usage_control.md)
- [Trusted Exchange](./trusted_exchange.md)

## Data Value Building Blocks
These building blocks cover essential aspects to handle data as an economic asset: 
- [Metadata and Discovery Protocol](./metadata_and_discovery_protocol.md)
- [Data Access/Usage Accounting](./data_usage_accounting.md)
- [Publication and Marketplace Services](./publication_and_marketplace_services.md)


## Governance Building Blocks
<div align="justify">The building blocks subsumed under this category refer to business, operational and organisational agreements among data spaces participants. These agreements are enforced through legal frameworks participants have to adhere to, or via technical building blocks:</div>

- [Business](./business.md) agreements comprise sercive leval agreement (SLA), data usage and access control policies as well as specified standards.
- [Organisational/operational building blocks](./organisational_and_operational.md)
- [Continuity model](./continuity_model.md)

## The importance of using building blocks
<div align="justify">Several companies have already reported their thoughts, improvements and results when using building blocks: </div></br>

<details>
  <summary><strong>Smart Connected Supplier Network</strong></summary>
  
  - It enables small manufacturing companies to join the digitalization process without the need of hiring IT professionals.
  - A rise of 20% of the overall productivity.
  - The transaction costs of the supply chain are reduced.
  
  Visit [SCSN webpage](https://smart-connected.nl/en) for more information.
</details>
<details>
  <summary><strong>ADVANEO Data Marketplace</strong></summary>
  
  - The data marketplace has been developed as a decentralized portal, all relevant and possibly sensitive raw data always remain with the data provider and only is transferred directly to the buyer in the event of a purchase.
  - It gives the opportunity of monetizing data.
  - Open data can be used to open up new perspectives and lift your data project to the next level.
  
  Visit [ADVANEO DMP webpage](https://www.advaneo-datamarketplace.de/en/#) for more information.
</details>
<details>
  <summary><strong>Vastuu</strong></summary>
  
  - Drives Europe’s data economy
  - Next-level adoption and co-creation of value with commercial scenarios 
  - Fosters neutrality, standards and common language to avoid risks and enhance trust
  - Helps establish the community and ecosystem to foster future innovation
  - Secure data lowers the threshold for different organisations to share their knowledge and expertise.
  
</details>

## General use cases
<div align="justify">Building blocks are usually combined with others, giving as a result a complete product or service. Amongst other qualities, data sovereignity and interoperability tend to be a powerful asset which makes the difference with other initiatives of the sector.</div></br>

<details>
  <summary><strong>Smart parking - Volkswagen | Fiware Foundation | Wobcom</strong></summary>
  <div align="justify">Smart Parking is a digital solution to improve parking in a city, reduce air pollution and support local businesses. Drivers in a city are navigated to the nearest available parking space. They can register their preferred shopping profiles, and these anonymised profiles are matched with shops near the parking spaces. Matching shop offers are returned with hash codes for the possible offers. If the driver shops at that particular shop, their parking fee is paid by the shop.</div>
</details>

<details>
  <summary><strong>ASSESLEEP - EUHubs4Data | Bitbrain</strong></summary>
  <div align="justify">It consists of a highly accurate sleep monitoring device that can comfortably record sleep at your home. A comprehensive sleep dataset will be created using using <a href="https://euhubs4data.eu/experiments/assesleep/">Bitbrain</a>'s new technology, incorporating a multitude of physiological and environmental sensors. Based on data collected in controlled and uncontrolled environments, robust AI-powered sleep analysis algorithms with medical-grade accuracy will be implemented.</div>
  
</details>

<details>
  <summary><strong>iGreenPort - i4Trust</strong></summary>
  <div align="justify">The objective of the  <a href="https://i4trust.org/experiments/igreenport/">iGreenPort</a> experiment consists of the monitoring of sea water quality in different areas of a port. In essence, different datasets (geoposition data on water quality, AIS navigation real-time data, etc..) will be shared in iGreenPort data space to create several data packages at different levels of the ‘data value chain’ to be utilised by iGreenPort partners and external entities, particularly authorities with environmental competencies in ports, their suppliers, and research groups in the field.</div>
