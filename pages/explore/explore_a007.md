---
title: A007 - Retrieve Clinical Information
keywords: getcarerecord, structured, rest, resource
tags: [rest,fhir,a007]
sidebar: foundations_sidebar
permalink: explore_a007.html
---

{% include custom/search.warnbanner.html %}


API
-----------
[GET /v1/Binary/$ers.generateCRI}](http://api-ers.spine2.ncrs.nhs.uk:88/swagger-ui/#!/binary/getClinicalInfoPDFUsingGET)

Description
-----------
This API lets users create a real-time Portable Document Format (PDF) of the referral. This is suitable for integration into a 3rd party system. You can find the Clinical Information for a referral request using a UBRN.