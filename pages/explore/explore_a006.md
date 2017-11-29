---
title: A006 - Retrieve Attachment
keywords: getcarerecord, structured, rest, resource
tags: [rest,fhir,a006]
sidebar: foundations_sidebar
permalink: explore_a006.html
---

{% include custom/search.warnbanner.html %}


API
-----------
[GET /v1/Binary/att-{referralRequestAttachmentId}](http://api-ers.spine2.ncrs.nhs.uk:88/swagger-ui/#!/binary/getAttachmentContentBodyUsingGET)

Description
-----------
This lets users retrieve and download linked files for a referral. Identify the file using both the request and attachment identifier.
