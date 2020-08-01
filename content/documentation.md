---
layout: home
---

### API Documentation

API standards for the following entities/systems are listed below. 
- [Health Data Consent Manager (HDCM) APIs](https://github.com/ProjectEKA/projecteka.github.io/blob/master/contracts/cm.yaml)
- [Gateway APIs](https://github.com/ProjectEKA/projecteka.github.io/blob/master/contracts/gateway.yaml)
- [Bridge APIs](https://github.com/ProjectEKA/projecteka.github.io/blob/master/contracts/bridge.yaml)

If you are serving the role of a Health Repository and only are interested in the HIP or HIU relevant APIs, please refer to the following links.
- [HIP APIs](https://github.com/ProjectEKA/projecteka.github.io/blob/master/contracts/hip.yaml)
- [HIU APIs](https://github.com/ProjectEKA/projecteka.github.io/blob/master/contracts/hiu.yaml)

The above APIs are essentially duplicates of the Gateway and Bridge specs, but put together as to make it clear to which set of APIs a HIP or HIU should implement to participate in the network.

Majority of the APIs follow HTTPs Async pattern, meaning that for an API call, there is a reciprocal callback API to the requester is made. They follow a pattern of ***/on-&lt;action&gt;***. 

The documentations are maintained in OpenAPI Specification (OAS), commonly known as swagger API documentation format. To view the documentation on the browser, you may follow the following steps. 
- Install Swagger Viewer Chrome plugin: add this [extension](https://chrome.google.com/webstore/detail/swagger-viewer/nfmkaonpdmaglhjjlggfhlndofdldfag). Once installed, you may open the above API links, and click the swagger button on the toolbar/addressbar of the browser, usually located on top right. 

##### Error and Meta Codes documentation 
Many of the contracts have errors and meta codes.
Please refer to the WIKI for details on [Error Codes](https://github.com/ProjectEKA/projecteka.github.io/wiki/API-Error-Codes) and [Meta/Concept Codes](https://github.com/ProjectEKA/projecteka.github.io/wiki/Meta-Codes)

##### Data formats 
Health Information is exchanged via FHIR bundles. [FHIR](https://www.hl7.org/fhir/index.html) is a standard for health care data exchange, published by HL7. The intent of using FHIR is towards standardization of schema, i.e machine readable, rather than addressing or enforcing semantic standards for interoperabilty. 

* See a brief note [here](./fhirepresentation.html) for health data representation in FHIR in the reference implementation stack.  
* For detailed guide to packaging data in FHIR format following the PHR envelope, refer to [WIKI](https://github.com/ProjectEKA/projecteka.github.io/wiki/Introduction-to-FHIR-as-data-formats)


##### Internal app/system specific APIs, downstream APIS
API Documentation for the HDCM, HIP and HIU are available from the source code repositories. 