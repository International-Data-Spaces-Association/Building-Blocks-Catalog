# System Adaptation

## Definition
<div align="justify">One of the main functions of a data space is to facilitate the transfer of data to and from participants’ systems (i.e. database systems, data-processing systems, enterprise systems [like CRM, ERP, MRP or MES systems], but also cyberphysical systems and IoT-enabled systems). Regardless of the system, there is a need for a System Adaptation building block that interfaces with the various data resources exported by the system and performs the necessary transformation of the data formats adopted for data exchange within the data space (see ‘Data Exchange APIs’ building block). To maintain confidentiality and privacy when transferring data from participants’ systems to the data space and vice versa, data encryption and anonymization may be required. Additional data and metadata may also be incorporated in order to transport relevant information required for other data space building blocks (e.g., on data accountability/traceability or usage control) to work.</div> 

## Role and Scope
<div allign="justify"></div>

## Features

## Components and Technologies
<details>
  <summary><strong>Design Principles Position Paper</strong></summary>
  
  - IoT protocols (e.g. CoAP [Constrained Application Protocol] or MQTT [Message Queuing Telemetry Transport]) can be used to interface with IoT resources.
  - Database protocols (e.g. JDBC [Java Database Connectivity] or SQL [Structured Query Language]) can be used to interface with databases.
  - API protocols (e.g. RESTful services) can be used to interface with enterprise systems and applications.
</details>

## Technical Reference Implementation
<div align="justify">A smart city connects its system to a data space to publish information on air quality. At the same time, it connects to the data space for receiving weather forecast information in order to predict evolution of air quality parameters and take appropriate action. The building block interfaces with the smart-city system to enable access to the data resource providing the air quality information and to transfer the data on weather forecasts.</div>

## Business Use Cases Implementation

## Best practices identification and recommendations

## Gap or what is missing?

## TRL

## Comments

## Additional Information
