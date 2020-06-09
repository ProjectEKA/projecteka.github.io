---
layout: home
---
###  Health Data Representation in FHIR format for exchange

Before we start,  there are few things that need explanation! 
#### Interoperability
For any exchange and subsequent interpretation of health data, addressing interoperability is a must. Interoperability can be broadly classified in two aspects that need to be solved. 
-   **Syntactic Interoperability**: Standards and protocols, data/wire formats. 
-   **Semantic Interoperability**: What is sent is what is understood. e.g. WBC and Leucocytes is understood as one and same, or that Dilatation of the aorta is a type of Aneurysm

The aim of the reference stack, is to solve the Syntactic interoperability, thus allowing a machine readable format for systems that consume the data. We use [HL7 FHIR](http://hl7.org/fhir/) as data formats to solve the syntactic interoperability.  

Semantic interoperability can be achieved by adopting a common standard; typically in health domain, by means of adopting common terminology / coding standards. Examples of such standards are SNOMED-CT, ICD10, LOINC etc. India already has member country license and National Resource Centre for EHR Standards (NRCeS) NRC maintains so. Anyone in India can get the license free of cost from NRCeS, by registering as MLDS. Please visit [here]([https://www.nrces.in/standards/snomed-ct](https://www.nrces.in/standards/snomed-ct)) for more information on how to get the license. We understand that adoption and mapping of Clinical terminologies can be a arduous process, and hence the documentation reflects the simplistic approach anyone can take to send machine readable standard format data. At the same time, if you would want to send the data using standard clinical terminologies mapping - you are much welcome and encouraged. We will continue to strive to embrace (and interpret) standard terminologies but that can happen progressively, as adoption and implementation of EHR/EMR, points-of-care systems, end user systems happen. 

For details of the FHIR formats in the reference stack, please refer to the [WIKI](https://github.com/ProjectEKA/projecteka.github.io/wiki).  
