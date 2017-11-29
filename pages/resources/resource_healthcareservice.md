---
title: HealthcareService
keywords: resources, healthcareservice, resource
tags: [rest,fhir]
sidebar: foundations_sidebar
permalink: resource_healthcareservice.html
summary: "Overview of the HealthcareService resource"
---

{% include custom/search.warnbanner.html %}

{% include custom/fhir.reference.html resource="HealthcareService" page="https://fhir.nhs.uk/STU3/eRS-HealthcareService-1" fhirlink="[HealthcareService](http://hl7.org/fhir/healthcareservice.html)" %}


## 1. Read ##

<div markdown="span" class="alert alert-success" role="alert">
GET [baseUrl]/HealthcareService/[id]</div>

{% include custom/read.response.html resource="HealthcareService" content="" %}

## 2. Search ##

<div markdown="span" class="alert alert-success" role="alert">
GET [baseUrl]/HealthcareService?[searchParameters]</div>

Fetches a bundle of all `HealthcareService` resources for the specified search criteria.

{% include custom/search.header.html resource="HealthcareService" %}


## 3. FHIR&reg; RESTful API Examples ##

**JSON Example 1**

<script src="https://gist.github.com/sufyanpat/11dcc8691f33a3da5bf4fda108d14d90.js"></script>
