---
title: Capability Statement
keywords: resources, rest, resource
tags: [rest,fhir]
sidebar: foundations_sidebar
permalink: resources_capabilitystatement.html
summary: "A capability statement is a set of capabilities of a FHIR Server that may be used as a statement of actual server functionality or a statement of required or desired server implementation."
---

{% include custom/search.warnbanner.html %}

{% include custom/fhir.referencemin.html resource="CapabilityStatement" page="eRS-CapabilityStatement-1" fhirlink="[CapabilityStatement](http://www.http://hl7.org/fhir/STU3/capabilitystatement.html)"%}

## 1. Read ##

<div markdown="span" class="alert alert-success" role="alert">
GET [baseUrl]/metadata</div>

The /metadata path on the root of the FHIR server will return the CapabilityStatement for the FHIR server:

<!--Alternatively, a HTTP OPTIONS request against the root of the FHIR server will also return the conformance profile:-->

<!--<div markdown="span" class="alert alert-success" role="alert">-
OPTIONS [baseUrl]/</div>-->

For details of this interaction - see the [HL7 FHIR STU3 RESTful API](https://www.hl7.org/fhir/STU3/http.html#capabilities)

All requests SHALL contain a valid ‘Authorization’ header and SHALL contain an ‘Accept’ header with at least one of the following application/json+fhir or application/xml+fhir.

## 2. CapabilityStatement ##

<script src="https://gist.github.com/sufyanpat/f0c23031cb71baf750b3b41c292ca7cc.js"></script>