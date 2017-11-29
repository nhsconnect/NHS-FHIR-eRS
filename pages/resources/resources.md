---
title: eRS Resources
keywords: resources, rest, resource
tags: [rest,fhir]
sidebar: foundations_sidebar
permalink: resources.html
summary: "Overview of the Explore section"
---

{% include custom/search.warnbanner.html %}


## 1. Pre-Requisites for FHIR Servers ##

### 1.1 API Requirements ###

- SHALL support HL7 FHIR STU3 version 3.0.1.

<!--- SHALL support the CareConnect Patient resource profile.
- SHALL support at least one additional resource profile from the list of CareConnect Profiles-->

- SHALL Implement REST behavior according to the [FHIR specification](http://http://www.hl7.org/fhir/http.html)

- Resources SHALL identify the profile supported as part of the [FHIR Base Resource](https://hl7.org/fhir/resource-definitions.html#Resource.meta)

- SHALL support XML **or** JSON formats for all API interactions and SHOULD support both formats.


### 1.2 FHIR Conformance ###

SHALL declare a Conformance identifying the list of profiles, operations and search parameters supported.

In order to be a compliant FHIR server, client systems need to expose a valid FHIR [CapabilityStatement](https://www.http://hl7.org/fhir/STU3/capabilitystatement.html) profile.

{% include custom/contribute.html content="Get in touch with interoperabilityteam@nhs.net to improve the Prerequisites." %}

## 2. Resource API Structure ##
The FHIR profile API's described in the Explore section of this implementation guide have been structured consistently in the following way:
- `0.` References
- `1.` Read
- `2.` Search Parameters
- `3.` Example

### 2.1 Resource API Structure Details ###

<table style="min-width:100%;width:100%">
<tr id="clinical">
<th style="width:20%;">General</th>
<th style="width:80%;">Description </th>
</tr>
<tr>
<td>0. References</td>
<td>Links to other parts of the implementation guide which might help with context and understanding the API's described</td>
</tr>
<tr>
<td>1. Read</td>
<td>A description of how to get the API</td>
</tr>
<tr>
<td>2. Search Parameters</td>
<td>List of search parameters for the profile being described, including any tips for searching. This section shows examples of how to search using the provided search parameters</td>
</tr>
<tr>
<td>3. Example</td>
<td>Description of of the Request & Response headers, example of how to search on a server and the expected response body as an example</td>
</tr>
</table>