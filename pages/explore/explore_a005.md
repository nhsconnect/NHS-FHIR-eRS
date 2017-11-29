---
title: A005 - Retrieve Referral Request
keywords: getcarerecord, structured, rest, resource
tags: [rest,fhir,a005]
sidebar: foundations_sidebar
permalink: explore_a005.html
---

{% include custom/search.warnbanner.html %}


API
-----------
[GET /v1/ReferralRequest/{id}](http://api-ers.spine2.ncrs.nhs.uk:88/swagger-ui/#!/referralrequest/getUsingGET)

Description
-----------
This API gets the referral request identified by the given ID. For each new referral, the user will be able to get key data attributes. External systems can show these in their system. The user can then see status and content header info.