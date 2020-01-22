---
layout: home
---

### Components
There are 4 essential components of the architecture, which must conform to the protocols of National Health Stack.

![Components of the Architecture](../images/ProjectEKA-Simplified-Arch.jpg)

- Health Data Consent Manager (HDCM): A fiduciary/trustee that manages patient consents, to facilitate information flow between HIP and HIU and Patient App(s)
- Health Information User (HIU): A web application to request/fetch/view Patient's Health Information. 
- Patient App: An Android application for patient's to signup with a HDCM, link accounts with providers, grant consents to HIU request of Health Information, and view patient Health records. In future, more access channels (e.g a Web Portal) may be introduced. 
- Health Information Provider (HIP): A set of useful toolings, like shared Libraries, handling the common workflow/interactions, while providing extension means for plugging HIP specific Health Information System


For more info, please check out Niti Aayog's National Health Stack [consultation paper](https://niti.gov.in/writereaddata/files/document_publication/NHS-Strategy-and-Approach-Document-for-consultation.pdf)
