---
title: A002 - Professional Session Select Role
keywords: getcarerecord, structured, rest, resource
tags: [rest,fhir,a002]
sidebar: foundations_sidebar
permalink: explore_a002.html
---

{% include custom/search.warnbanner.html %}

API
-----------
[PUT /v1/ProfessionalSession/{sessionKey}](http://api-ers.spine2.ncrs.nhs.uk:88/swagger-ui/#!/professionalsession/updateProfessionalSessionSelectRoleUsingPUT)

Description
-----------
Updates a Professional Session with the appropriate NHS organisation and role. This ensures the correct access rights for the user.