# Provenance and traceability

## Definition
<div align="justify">This building block provides the means for tracing and tracking in the process of data provision and data consumption/use. It thereby provides the basis for a number of important functions, from identification of the lineage of data to audit-proof logging of transactions. It also enables implementation of a wide range of tracking use cases at application level, such as tracking of products or material flows in a supply chain.</div> 

## Role and Scope
<div allign="justify">Enables traceability of provenance, access, and usage of data shared and exchanged in a data space</div>

## Features 
<details>
  <summary><strong>DSBA - CTO architecture coherence [DRAFT. NOT APPROVED]</strong></summary>
  
- Audit-proof logging of data exchange transactions
- Data Provenance Tracking
  
</details>

## Components and Technologies
<details>
  <summary><strong>DSBA - CTO architecture coherence [DRAFT. NOT APPROVED]</strong></summary>
  
- Integration with multiple DLTs using [FIWARE Canis Major](https://github.com/fiware/CanisMajor) component
- [Infrastructural Sovereignty over Agreement and Transaction Data, figure 3 and 4](https://ris.utwente.nl/ws/portalfiles/portal/182217093/Infrastructural_Sovereignty_over_Agreement_and_Transaction_Data_.pdf)
  
  <img src="images/Provenance_Figure3.png" width="640" align="center"></br>
  
  <img src="images/Provenance_Figure4.png" width="640" align="center"></br>
  
</details>

<details>
  <summary><strong>SmashHit project</strong></summary>
- Encryption module with digital signature, hashing function, web framework, unique identifier generator, watermarking, fingerprinting.
- Data use traceability component module.
</details>

## Technical Reference Implementation
<details>
  <summary><strong>Design Principles Position Paper</strong></summary>
  
<div align="justify">In the scope of a circular supply chain, there is need for providing end-to-end traceability of the status and conditions of key circular entities, like products or materials. The building block allows authorised participants to query on the status of specific products and materials, and to receive detailed information about their status and location in the circular chain.</div>
  
</details>

<details>
  <summary><strong>SmashHit project</strong></summary>
- Data use traceability component module has two purposes: (1st) to trace data flows by fingerprinting/watermarking, and (2nd) the identification of data leakages. The module addresses the need of Data Providers,  OEMs and Data Processors to get a solution which enables the identification of data leakages or misuses. Basis for this component are data fingerprinting and watermark technologies that shall enable the identification of the last data source within the smashHit ecosystem. The fingerprint or watermark will provide answers about where the leaked or misused data was located or forwarded the last time which will avoid the blaming of guiltless participants in a consent chain.
  ![image](https://user-images.githubusercontent.com/95075534/194502726-97de469e-24e0-444d-81f3-85053cac9516.png)
Figure 1. Application of smashHit’s Data Use Traceability Component
</details>

## Business Use Cases Implementation

<details>
  <summary><strong>SmashHit project</strong></summary>
 - A Data Provider get the authorization from the Data Owner to use and transfer the data to a specific list of Data Processors/Processing entities. The data is transferred from the Data Provider to different data Processors or among Data Processors. From the transfer logs, the Data Owner can view the different transactions, thus providing the transparency of data sharing.

Another use case is that a data is transferred from a Data Provider to several Processing entities which show their interest to the data. From the transfer logs and general information about Processing entities, it is possible to analyse categories of businesses interested to a specific kind of data, and perform targeted advertising to other Processing entities.
</details>

## Best practices identification and recommendations

<details>
  <summary><strong>SmashHit project</strong></summary>
While transferring data, the Data Provider and the Data Processor should make sure that the transfer respect the consent signed with the data Owner (authorized processing entities, expiration date of consent, ...). The receiving company of the data, before using that data, should make sure (using hashing, watermarking or fingerprinting technologies) that it hasn’t been tempered by a third party.
</details>

## Gap or what is missing?
<details>
  <summary><strong>SmashHit project</strong></summary>
There is no gap in our implementation, however it could be extended to perform further data analysis.
</details>

## TRL

## Comments

## Additional Information
<details>
  <summary><strong>SmashHit project</strong></summary>
https://smashhit.eu/enabling-data-use-traceability-with-smashhit/
Implementations of data analysis methods, that could be applied on any kind of data and also transfer logs, are under development and could be found here: https://github.com/D-Stiv/smashHitUBO 
 </details>
