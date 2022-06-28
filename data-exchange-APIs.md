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
  <summary><strong>DSBA - CTO architecture coherence</strong></summary>
  
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
  <summary><strong>DSBA - CTO architecture coherence</strong></summary>
  
- [ETSI NGSI-LD API spec](https://www.etsi.org/deliver/etsi_gs/CIM/001_099/009/01.04.02_60/gs_CIM009v010402p.pdf)
- DCAT-AP
- [Context Broker](https://github.com/FIWARE/catalogue#core-context-broker-components)
- IDS-Handshake
- [OpenAPI](http://market40.eu/wp-content/uploads/MARKET4.0-OC1-winners-2nd-Webinar-OpenAPI-Data-Open.pdf)
- EDC
- Ocean Protocol
  
</details>

<details>
  <summary><strong>i3-Market Project</strong></summary>
  
- DCAT-AP
  
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
  <summary><strong>DSBA - CTO architecture coherence</strong></summary>
  
[OpenApi data app](http://market40.eu/wp-content/uploads/MARKET4.0-OC1-winners-2nd-Webinar-OpenAPI-Data-Open.pdf)
</details>

## Business Use Cases Implementation

<details>
  <summary><strong>Design Principles Position Paper</strong></summary>
  
- Domain Data Standard: In manufacturing data spaces, a combination of different standards is used to describe the syntax and semantics of data transactions (e.g. ISO 10303, Asset Administration Shell, eCl@ss).
  
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

## Gap or what is missing?

## TRL

## Comments

## Additional Information
