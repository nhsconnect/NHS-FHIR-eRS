---
title: A008 - Retrieve Worklist
keywords: getcarerecord, structured, rest, resource
tags: [rest,fhir,a008]
sidebar: foundations_sidebar
permalink: explore_a008.html
---

{% include custom/search.warnbanner.html %}

API
-----------
[POST /v1/ReferralRequest/$ers.fetchworklist](http://api-ers.spine2.ncrs.nhs.uk:88/swagger-ui/#!/referralrequest/getWorklistUsingPOST)

Description
-----------
This lets authorised users retrieve the ‘Referrals for Review’ work list. This is the same as the existing interface. This work list gives details of new referrals sent to the service by GPs and others. It includes their key attributes.
