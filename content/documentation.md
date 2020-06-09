---
layout: home
---

### API Documentation

API Documentation for the HDCM, HIP and HIU are available from the source code repositories. 
- [Health Data Consent Manager (HDCM) APIs](https://github.com/ProjectEKA/projecteka.github.io/blob/master/contracts/cm-v1.yaml)
- [Gateway APIs](https://github.com/ProjectEKA/projecteka.github.io/blob/master/contracts/gateway-v1.yaml)
- [Bridge APIs](https://github.com/ProjectEKA/projecteka.github.io/blob/master/contracts/bridge-v1.yml)


The documentations are maintained in OpenAPI Specification (OAS), commonly known as swagger API documentation format. To view the documentation on the browser, you may follow the following steps. 
- Install Swagger Viewer Chrome plugin: add this [extension](https://chrome.google.com/webstore/detail/swagger-viewer/nfmkaonpdmaglhjjlggfhlndofdldfag). Once installed, you may open the above API links, and click the swagger button on the toolbar/addressbar of the browser, usually located on top right. 


Many of the contracts have errors and meta codes. Which are documented [here](./codes.html)


Health Information is exchanged via FHIR bundles. [FHIR](https://www.hl7.org/fhir/index.html) is a standard for health care data exchange, published by HL7. The intent of using FHIR is towards standardization of schema, i.e machine readable, rather than addressing or enforcing semantic standards for interoperabilty. See [here](./fhirepresentation.html) for health data representation in FHIR in the reference implementation stack.  

