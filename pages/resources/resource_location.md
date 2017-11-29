---
title: Location
keywords: resources, location, resource
tags: [rest,fhir]
sidebar: foundations_sidebar
permalink: resource_location.html
summary: "Overview of the Location resource"
---

{% include custom/search.warnbanner.html %}

{% include custom/fhir.reference.html resource="Location" page="https://fhir.nhs.uk/STU3/eRS-Location-1" fhirlink="[Location](http://hl7.org/fhir/location.html)" %}


## 1. Read ##

<div markdown="span" class="alert alert-success" role="alert">
GET [baseUrl]/Location/[id]</div>

{% include custom/read.response.html resource="Location" content="" %}

## 2. Search ##

<div markdown="span" class="alert alert-success" role="alert">
GET [baseUrl]/Location?[searchParameters]</div>

Fetches a bundle of all `Location` resources for the specified search criteria.

{% include custom/search.header.html resource="Location" %}


## 3. FHIR&reg; RESTful API Examples ##

**JSON Example 1**

<script src="https://gist.github.com/sufyanpat/c4a39f2f66fef530910745d9153c63c4.js"></script>
