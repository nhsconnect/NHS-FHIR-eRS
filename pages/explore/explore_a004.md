---
title: A004 - Retrieve Reference Data
keywords: getcarerecord, structured, rest, resource
tags: [rest,fhir,a004]
sidebar: foundations_sidebar
permalink: explore_a004.html
---

{% include custom/search.warnbanner.html %}

API
-----------
[GET /v1/ValueSet/{valueSetId}](http://api-ers.spine2.ncrs.nhs.uk:88/swagger-ui/#!/valueset/getValueSetUsingGET)

Description
-----------
This read-only API lets a user access a pre-populated list of reference data. The NHS e-Referral Service uses these lists throughout. For example, a list of specialities. They support data accuracy and effective re-use. It retrieves a specific Value Set (Reference Dataset) by ID. 
