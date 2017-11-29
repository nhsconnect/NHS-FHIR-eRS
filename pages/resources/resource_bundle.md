---
title: Bundle
keywords: resources, bundle, resource
tags: [rest,fhir]
sidebar: foundations_sidebar
permalink: resource_bundle.html
summary: "Overview of the Bundle resource"
---

{% include custom/search.warnbanner.html %}

{% include custom/fhir.reference.html resource="Bundle" page="https://fhir.nhs.uk/STU3/eRS-Bundle-1" fhirlink="[Location](http://hl7.org/fhir/bundle.html)" %}


## 1. Read ##

<div markdown="span" class="alert alert-success" role="alert">
GET [baseUrl]/Bundle/[id]</div>

{% include custom/read.response.html resource="Bundle" content="" %}

## 2. Search ##

<div markdown="span" class="alert alert-success" role="alert">
GET [baseUrl]/Bundle?[searchParameters]</div>

Fetches a bundle of all `Bundle` resources for the specified search criteria.

{% include custom/search.header.html resource="Bundle" %}


## 3. FHIR&reg; RESTful API Examples ##

**JSON Example 1**

<script src="https://gist.github.com/sufyanpat/e25b76bd009a3f29041dc08a7546eac2.js"></script>