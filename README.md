# Building-Blocks-Catalog

This is the repository to list the building blocks developed in OPEN DEI project.

## Introduction to Building Blocks

The different building blocks can be specified and developed independently of each other. When doing so, existing norms, standards, and best practices should be used to ensure cohesion of building blocks. Each data space solution can integrate multiple building blocks, as long as they are in line with data space reference architectures (e.g., the IDS Reference Architecture Model v4.0). The building blocks presented in this chapter are core elements of any data space. As such, they can be considered sector-agnostic. Nevertheless, they can be used in sector-specific scenarios (see e.g. seaport scenarios). Data space stakeholders may also define additional building blocks to support innovative features and functions. For instance, data space architects may introduce building blocks that enable novel types of data space architectures combining centralised and decentralised approaches. Likewise, business stakeholders may introduce building blocks that enable novel forms of smart contracts to be agreed upon by participants of a data space, thereby facilitating business model innovations. Hence, the building blocks presented in this chapter are not exhaustive, but rather indicative of the elements of a data space. In general, each building block consists of reusable, generic components (i.e. which can be used across domains and industries) and more specific components (i.e. to meet requirements and regulations that are specific for certain industries, domains, or even concrete use cases). This allows individual participants to join different data spaces, use data in multiple contexts and scenarios, and be part of multiple data value chains.

## Taxonomy of Building Blocks

The taxonomy of building blocks constituting a data space will benefit various stakeholders:

* **Data space architects and integrators** will be provided with a structured way for identifying the components required for their specific architecture.
* **Building block developers** will be a given a clear description on how their components can fit into the specific architecture of a data space.
* **Business managers** will be able to identify business model candidates for data sharing and exchange (including data monetisation) in the context of a specific data space.
* **Data space policy managers** will have access to building blocks that can be used to specify and enforce data space related policies (e.g., data access policies, privacy control policies).

## Interoperability Building Blocks

These building blocks should be deployed by all data providers and data consumers participating in a data space. This way, each data provider can be sure that any data published can be technically consumed by any data consumer entitled to do so, while each data consumer can be sure they are able to technically access and use any data made available by any data provider selected. The following building blocks belong to this category:

* [Data Models and Formats](data-models-and-formats.md)
* [Data Exchange APIs](data-exchange-APIs.md)
* [Data Provenance and Traceability](provenance\_and\_traceability.md)

## Data sovereignty and trust Building Blocks

Data sovereignty and trust Building Blocks regaining control over their data, and as data becomes portable between providers on a user-controlled consent basis. Users can switch between providers without losing their data and vendor lock-in will become a phenomenon of the past. For participants in data spaces, data sovereignty means two things:\


1. Benefit from enhanced possibilities to view, process, manage, and secure their data.
2. Stay in control over their data when making it accessible to other parties.

These building blocks include the data ownership policies that require agile and standardised ICT capabilities when such agreements are to be negotiated dynamically. We need to establish a semantic interoperability of policies and behavioural interoperability of policies.

The building blocks that provides data sovereignty and trust are:

* [Identity Management (IM)](identity\_management.md)
* [Access and Usage Control/Policies](access\_and\_usage\_control.md)
* [Trusted Exchange](trusted\_exchange.md)

## Data Value Building Blocks

These building blocks cover essential aspects to handle data as an economic asset:

* [Metadata and Discovery Protocol](metadata\_and\_discovery\_protocol.md)
* [Data Access/Usage Accounting](data\_usage\_accounting.md)
* [Publication and Marketplace Services](publication\_and\_marketplace\_services.md)

## Governance Building Blocks

The building blocks subsumed under this category refer to business, operational and organisational agreements among data spaces participants. These agreements are enforced through legal frameworks participants have to adhere to, or via technical building blocks:

* [Business](business.md) agreements comprise service level agreement (SLA), data usage and access control policies as well as specified standards.
* [Organisational/operational building blocks](organisational\_and\_operational.md)
* [Continuity model](continuity\_model.md)

## The importance of using building blocks

Several companies have already reported their thoughts, improvements and results when using building blocks:\


<details>

<summary><strong>Smart Connected Supplier Network</strong></summary>

* Enable small manufacturing companies to join the digitalization process without the need of hiring IT professionals.
* A rise of 20% of the overall productivity.
* The transaction costs of the supply chain are reduced.

Visit [SCSN webpage](https://smart-connected.nl/en) for more information.

</details>

<details>

<summary><strong>ADVANEO Data Marketplace</strong></summary>

* The data marketplace has been developed as a decentralized portal, all relevant and possibly sensitive raw data always remain with the data provider and only is transferred directly to the buyer in the event of a purchase.
* Give the opportunity of monetizing data.
* Open data can be used to open up new perspectives and lift your data project to the next level.

Visit [ADVANEO DMP webpage](https://www.advaneo-datamarketplace.de/en/) for more information.

</details>

<details>

<summary><strong>Vastuu</strong></summary>

* Drive Europe’s data economy.
* Next-level adoption and co-creation of value with commercial scenarios.
* Foster neutrality, standards and common language to avoid risks and enhance trust.
* Help establish the community and ecosystem to foster future innovation.
* Secure data lowers the threshold for different organisations to share their knowledge and expertise.

</details>

<details>

<summary><strong>DASLOGIS - Dutch Data Spaces for Logistics</strong></summary>

* Enable the discovery and controlled sharing of (potentially) sensitive data.
* Offer flexibility, extensibility and personalisation to support data exchange in logistics.

</details>

<details>

<summary><strong>Intelligent Washing Machine - Haier | Fraunhofer ISST</strong></summary>

* Save cost, time and energy, environmental awareness.
* Offer consumers a better utilization of washing machines with additional services
* Gain data insights for product and service innovations
* By collecting consumer data companies get the possibility to gain data insights for product and service innovations.

</details>

<details>

<summary><strong>Wind and Solar Assets modeling - EDF</strong></summary>

* Opportunity to build comprehensive models, analytic frameworks and improve multiparty collaboration capabilities needed to support digital ecosystems.
* Backbone for renewables operator to ensure continuity of technical data along lifecycle.
* Real accelerator for Greenfields and brownfields assets to deliver more safely, more quickly more efficiently and with a lower Total Cost of Ownership.

</details>

<details>

<summary><strong>H2020 InterConnect</strong></summary>

* The need for the selected building blocks (Interoperability, Trust and Data Value) was natural to the project's reference architecture, hence their adoption. They are particularly important to allow the required separation of what is the interoperability plan (at the syntactic and semantical level), the data exchange plan to link interoperable peers, and the enforcement of trust (identity) for data usage. Relying on these building blocks ensures alignment, but most importantly, the capability to swap them if needed and to interface with other sectors/domains outside the one of InterConnect (Energy/IoT).

</details>

<details>

<summary><strong>Resilience Knowledge Booster</strong></summary>

* The importance of the interoperablity, semantic metadata at cross-domain served the IMPETUs project to elaborate a climate/environment data space to share information across industries and contribute to the elaboration and planning of adaptation and mitigation actions against climate change.

</details>

<details>

<summary><strong>The Looming Factory</strong></summary>

* The role of Data Spaces in the project is to craete a secure environment to transmit log data collected by IoT sensors from the shop floor to the third-parties responsible for the development of data analysis and AI applications to improve operational efficiency (e.g. predictive maintenance). The implemented and instantiated components follow the IDS Reference Architecture Model (IDS-RAM 3.0) and include IDS Connectors, an Identity Provider, a Broker and an App Store.

</details>

<details>

<summary><strong>Open Data Product Initiative</strong></summary>

[Open Data Product Specification (ODPS)](https://opendataproducts.org) is a vendor-neutral, open-source machine-readable data product metadata model. This specification is developed openly under the [Open Data Product Initiative](https://opencollective.com/odpi). The Open Data Product Specification aims for the same impact in the Data Economy as what OpenAPI specification did for the API Economy.\
The data products and data as a service solutions are spread around increasing amount of market places, tool stack for the data product design, development and management is a wild west, consumers have a hard time knowing what they are purchasing or how to compare data products to find a best possible fit in their situation.\
In short, the data economy lacks a data product standard. By working together and openly, we can increase interoperability, growth, and data reuse with help of shared specification. International standards are a vital tool in ensuring products and services are interchangeable and compatible across borders, removing barriers to trade, reducing production and supply chain costs and building confidence in business services and protecting consumers.

</details>

<details>

<summary><strong>Sitra IHAN Blueprint 2.5</strong></summary>

The IHAN data economy architecture defines the distributed and open standard-based components that allow companies, governments and individuals to share data in an easy and trusted manner with users’ consents. Focus is on IDENTITY, CONSENT and LOGGING. These three parts have been approved as a CEN/CENELEC pre-standard.

</details>

<details>

<summary><strong>Open Geospatial Consortium</strong></summary>

OGC community is building spatial-related suite of standards in multiple groups. both internally and externally it is important to ensure minimum alignment between interoperability solutions. Therefore, as the harmonisation between standards is based on the building blocks that can be composed in the IT solution, it is important to make sure component building blocks can mediate and use exchange mechanisms.

</details>

<details>

<summary><strong>PLATOON Project</strong></summary>

Provide building blocks for three pillars to support a reference Architecture for Interoperable Data (and services) Ecosystem.

1. Pilar 1 : Interoperability : Semantic Data Model for Energy
2. Pilar 2 : Trust : with IDSA (own connector) - Privacy for secure data exchange.
3. Pilar 3 : Data value : Use Analytic Toolbox that leverages previous 2 pillars and provides data driven interoperable service that can be deployed in different configuration - Cloud/Hybrid/Edge

</details>

<details>

<summary><strong>Fraunhofer IOSB</strong></summary>

Data sovereignty for manufacturing / Industry 4.0 companies in use-cases like "Collaboritive Condition Monitoring". We are using the Eclipse Dataspace Connector to connect digital twins (asset administration shell) across company borders.

</details>

## General use cases

Building blocks are usually combined with others, giving as a result a complete product or service. Amongst other qualities, data sovereignty and interoperability tend to be a powerful asset which makes the difference with other initiatives of the sector.\


<details>

<summary><strong>Smart parking - Volkswagen | Fiware Foundation | Wobcom</strong></summary>

Smart Parking is a digital solution to improve parking in a city, reduce air pollution and support local businesses. Drivers in a city are navigated to the nearest available parking space. They can register their preferred shopping profiles, and these anonymised profiles are matched with shops near the parking spaces. Matching shop offers are returned with hash codes for the possible offers. If the driver shops at that particular shop, their parking fee is paid by the shop.

</details>

<details>

<summary><strong>ASSESLEEP - EUHubs4Data | Bitbrain</strong></summary>

It consists of a highly accurate sleep monitoring device that can comfortably record sleep at your home. A comprehensive sleep dataset will be created using using [Bitbrain](https://euhubs4data.eu/experiments/assesleep/)'s new technology, incorporating a multitude of physiological and environmental sensors. Based on data collected in controlled and uncontrolled environments, robust AI-powered sleep analysis algorithms with medical-grade accuracy will be implemented.

</details>

<details>

<summary><strong>iGreenPort - i4Trust</strong></summary>

The objective of the [iGreenPort](https://i4trust.org/experiments/igreenport/) experiment consists of the monitoring of sea water quality in different areas of a port. In essence, different datasets (geoposition data on water quality, AIS navigation real-time data, etc..) will be shared in iGreenPort data space to create several data packages at different levels of the ‘data value chain’ to be utilised by iGreenPort partners and external entities, particularly authorities with environmental competencies in ports, their suppliers, and research groups in the field.

</details>

<details>

<summary><strong>MobilityData</strong></summary>

The mobility community has created several hubs for international GTFS sources over the years. There have been consistent issues with sustaining these platforms in the long term, and creating community processes so it's clear how decisions are made and how stakeholders across the mobility industry can contribute to the platform. That's the need [MobilityData](https://database.mobilitydata.org/) is working to meet with the [Mobility Database](https://github.com/MobilityData/mobility-database-catalogs), so more stakeholders can trust the longevity of this platform and it can become an increasingly valuable source for creating and improving mobility data as a community.

</details>
