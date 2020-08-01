---
layout: home
---

## Error Codes 
The response callback APIs (e.g. /on-discover), have an error attribute, which have a code and a message. The codes are described below. Note, only the ones relevant to the network are documented here, for application/system specification error codes (e.g. Patient App), please refer to the reference implementation documentations. 

All network API error codes are documented in [WIKI](https://github.com/ProjectEKA/projecteka.github.io/wiki/API-Error-Codes)


## Meta/Concept codes
These are codes that are used within the contract to express specific concepts. 
Reference implementations only demonstrate the means and usages of the codes, and not establish a standard. The standards themselves are to be defined by a competent authority, available publicly, and the codes in the reference systems should only reference/use such defintiions.

Example codes used in reference stack for Purpose-of-use and Hi-Types are documented in [WIKI](https://github.com/ProjectEKA/projecteka.github.io/wiki/Meta-Codes) 


##### Health Information (HI) type codes
The following codes are defined as the exchangeable Health Information (HI) types. In the reference implementations, they are synonymous to the FHIR resource types. It is expected that a competent authority will define such HI types that are accepted within the affinity domain. 

The reference CM implementation [exposes an API](https://github.com/ProjectEKA/consent-manager/blob/master/src/main/resources/static/ValueSet/health-info-type.json) using FHIR Value Set specification to express the HI Types. 


Please see below for examples:
```
{
    "code": "Condition",
    "display": "Condition"
},
{
    "code": "Observation",
    "display": "Observation"
},
{
    "code": "DiagnosticReport",
    "display": "Diagnostic Report"
},
{
    "code": "MedicationRequest",
    "display": "Medication Request"
}

```

