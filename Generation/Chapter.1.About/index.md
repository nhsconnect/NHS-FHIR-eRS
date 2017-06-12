# About #

### Overview: FHIR Implementation Guide for the NHS e-Referral Service#


**Background**

This specification provides information on the design and implementation of FHIR Application Programming Interfaces (APIs) within the NHS e-Referral Service (NHS e-RS).  In 2015, the NHS made a strategic decision to replace the Choose and Book (CAB) Service with the new NHS e-Referral Service (NHS e-RS).  This implementation was completed by NHS Digital (formerly the Health and Social Care Information Centre) and uses enhanced technology to enhance the quality of the referral experience for patients, and improve business processes for clinicians and administrative staff.  In so doing, it aims to create a more patient-centred, people-powered NHS, making the NHS much easier to do business with, and support the drive towards paperless referrals and a paperless NHS.

The new Service aims to build upon the current and supported message interfaces (N3-based HL7 message interactions from the NHS Connecting for Health Message Implementation Manual (MiM) version 2.3 and from MiM version 3.1.09) and to extend these with a new implementation of APIs.

This N3 interface approach is currently being developed as part of the NHS e-RS solution to provide access to services and content through a well-defined and secure interface. This approach is influenced by RESTful/RPC service interfaces and the emerging HL7 FHIR (Fast Healthcare Interoperability Resources) standard.


**Exclusions**

-	The information presented within this website section forms an integral part of the API Beta Project to release an initial set of secure Clinical Referral Information (CRI) APIs to allow providers to consume structured clinical content as part of the integrated referral management process.

-	Though the intent is to publish profiles and FHIR conformance statements for all models within the API; at the time of writing it is highlighted that this project activity remains in the exploratory Beta development phase with work ongoing.

-	The implementation of a user-focused Ecosystem to support third party API development is currently in progress. This aims to provide a host of user information and documentation on the engagement process, API architecture, test environments and other supporting development resources.


**Further Information**

This specification is based on and is intended to be used alongside the published [FHIR DSTU2 1.0.2] (Oct 24, 2015) specification.

[FHIR DSTU2 1.0.2]:http://hl7.org/fhir/index.html


**Note**

This FHIR API specification is published as a **'work in progress'** version and as such is subject to change.  It has been published to show the direction of travel and to serve as a discussion document for parties involved within the implementation of FHIR based communication.
