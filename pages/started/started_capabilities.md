---
title: Capabilities
keywords: capabilities ,overview, API
tags: [explanation]
sidebar: overview_sidebar
permalink: started_capabilities.html
summary: Providing a RESTful API for the first time is a journey. This page explains a starting point of the work involved in providing an API
---

##  Capabilities ##
The NHS e-Referral Service aims to build upon the current, supported message interfaces, which were transitioned from Choose and Book and to extend these with new APIs. The Service is dependent on other national components, such as:

- The Patient Demographic Service (PDS) as the master source of patient demographics
- Spine Directory Services for NHS organisational structures (SDS)
- User authentication, security and naming services
- Interface specifications such as message header and transportation standards
- The Transaction Messaging Service (TMS)

Since its inception, the Service supports N3-based HL7 message interactions from the NHS Connecting for Health Message Implementation Manual (MiM) version 2.3 and from MiM version 3.1.09. Suppliers must support Ebooking interactions either from MiM 2.3 or MiM3.1.09, but can support other MiM versions for other interactions such as PDS. MiM2.3 is supported for backward compatibility only, with partners new to compliance, expected to be MiM3.1.09 compliant.

Through the period 2015-16, a new Integration Workstream was established with the aim of delivering the progressive implementation of user-driven APIs, in a secure and clinically safe manner. Using Government Digital Service (GDS) delivery principles early Discovery and Alpha implementation phases were successfully completed, leading to an overall approach centred on  the use of N3/smartcard based interface,  influenced by RESTful service interfaces and the emerging HL7 FHIR (Fast Healthcare Interoperability Resources) standards.

Current Capabilities

Towards the end of the 2016 calendar year and initial release of eight Beta APIs was completed and made available in the e-RS/DEV1 Path-To-Live (PTL) environment for external business partners elaboration and feedback. These comprised three capability suites which currently comprise eight individual APIs:

**Authentication and Authorisation**
The ability to initiate, access and exit an Spine-based API session, equivalent to an existing NHS e-Referral Service Professional User.

**Reference Data**
The ability to access NHS e-Referral Service reference data lists in the form of FHIR ValueSets.

**Clinical Referral Information (CRI)**
The ability to search, access and download provider-based CRI, comprising an equivalent Referrals for Review Worklist, Referral Header, Clinical Information PDF and Supplementary Attachments.

