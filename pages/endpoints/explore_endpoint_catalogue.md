---
title: Endpoint Catalogue
keywords: endpoint ,catalogue, API
tags: [endpoint]
sidebar: overview_sidebar
permalink: explore_endpoint_catalogue.html
---



##  Endpoint Catalogue ##

|Id   | Name| Family | Verb | URI
|----------|-----------|-----|-----|----|
| A001|[Create Professional Session](explore_a001.html)|Session|POST|[/v1/ProfessionalSession](http://api-ers.spine2.ncrs.nhs.uk:88/swagger-ui/#!/professionalsession/createProfessionalSessionUsingPOST)|
| A002|[Professional Session Select Role](explore_a002.html)|Session|PUT|[/v1/ProfessionalSession/{sessionKey}](http://api-ers.spine2.ncrs.nhs.uk:88/swagger-ui/#!/professionalsession/updateProfessionalSessionSelectRoleUsingPUT)|
| A003|[Delete Professional Session	](explore_a003.html)|Session|DELETE|[/v1/ProfessionalSession/{sessionKey}](http://api-ers.spine2.ncrs.nhs.uk:88/swagger-ui/#!/professionalsession/deleteProfessionalSessionUsingDELETE)|
| A004|[Retrieve Reference Data](explore_a004.html)|Reference Data|GET|[/v1/ValueSet/{valueSetId}n](http://api-ers.spine2.ncrs.nhs.uk:88/swagger-ui/#!/valueset/getValueSetUsingGET)|
| A005|[Retrieve Referral Request](explore_a005.html)|Clinical Referral Information|GET|[/v1/ReferralRequest/{id}](http://api-ers.spine2.ncrs.nhs.uk:88/swagger-ui/#!/referralrequest/getUsingGET)|
| A006|[Retrieve Attachment](explore_a006.html)|Clinical Referral Information|GET|[/v1/Binary/att-{referralRequestAttachmentId](http://api-ers.spine2.ncrs.nhs.uk:88/swagger-ui/#!/binary/getAttachmentContentBodyUsingGET)|
| A007|[Retrieve Clinical Information](explore_a007.html)|Clinical Referral Information|GET|[/v1/Binary/$ers.generateCRI](http://api-ers.spine2.ncrs.nhs.uk:88/swagger-ui/#!/binary/getClinicalInfoPDFUsingGET)|
| A008|[Retrieve Worklist](explore_a008.html)|Clinical Referral Information|POST|[/v1/ReferralRequest/$ers.fetchworklist](http://api-ers.spine2.ncrs.nhs.uk:88/swagger-ui/#!/referralrequest/getWorklistUsingPOST)|
