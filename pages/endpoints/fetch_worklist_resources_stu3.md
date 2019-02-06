---
title: Fetch Worklist Resources
keywords: rest, resource
sidebar: foundations_sidebar
permalink: fetch_worklist_resources_stu3.html
summary: "Links to the Fetch Worklist endpoint profiles"
---

## Profiles ##

|OperationDefinition|
|-------|
|[eRS-FetchWorklist-Operation-1](https://fhir.nhs.uk/STU3/OperationDefinition/eRS-FetchWorklist-Operation-1)|


|StructureDefinition| 
|-------|
| [eRS-Appointment-1](https://fhir.nhs.uk/STU3/StructureDefinition/eRS-Appointment-1/_history/1.0) | 
| [eRS-DocumentReference-1](https://fhir.nhs.uk/STU3/StructureDefinition/eRS-DocumentReference-1/_history/1.0) | 
| [eRS-FetchWorklist-List-1](https://fhir.nhs.uk/STU3/StructureDefinition/eRS-FetchWorklist-List-1/_history/1.0) | 
| [eRS-HealthcareService-1](https://fhir.nhs.uk/STU3/StructureDefinition/eRS-HealthcareService-1/_history/1.0) | 
| [eRS-Location-1](https://fhir.nhs.uk/STU3/StructureDefinition/eRS-Location-1/_history/1.0) | 
| [eRS-OperationOutcome-1](https://fhir.nhs.uk/STU3/StructureDefinition/eRS-OperationOutcome-1/_history/1.0) | 
| [eRS-Patient-1](https://fhir.nhs.uk/STU3/StructureDefinition/eRS-Patient-1/_history/1.0) | 
| [eRS-Practitioner-1](https://fhir.nhs.uk/STU3/StructureDefinition/eRS-Practitioner-1/_history/1.0) | 
| [eRS-ReferralRequest-1](https://fhir.nhs.uk/STU3/StructureDefinition/eRS-ReferralRequest-1/_history/1.0) | 
| [eRS-Specialty-ValueSet-1](https://fhir.nhs.uk/STU3/StructureDefinition/eRS-Specialty-ValueSet-1/_history/1.0) |

|Extensions|
|-------|
|[Extension-eRS-Appointment-1](https://fhir.nhs.uk/STU3/StructureDefinition/Extension-eRS-Appointment-1/_history/1.0)|
|[Extension-eRS-AttachedBy-1](https://fhir.nhs.uk/STU3/StructureDefinition/Extension-eRS-AttachedBy-1/_history/1.0)|
|[Extension-eRS-ClinicalInfoFirstSubmitted-1](https://fhir.nhs.uk/STU3/StructureDefinition/Extension-eRS-ClinicalInfoFirstSubmitted-1/_history/1.0)|
|[Extension-eRS-ClinicalInfoLastUpdated-1](https://fhir.nhs.uk/STU3/StructureDefinition/Extension-eRS-ClinicalInfoLastUpdated-1/_history/1.0)|
|[Extension-eRS-OperationOutcomeElementName-1](https://fhir.nhs.uk/STU3/StructureDefinition/Extension-eRS-OperationOutcomeElementName-1/_history/1.0)|
|[Extension-eRS-OperationOutcomeElementValue-1](https://fhir.nhs.uk/STU3/StructureDefinition/Extension-eRS-OperationOutcomeElementValue-1/_history/1.0)|
|[Extension-eRS-ReferralsforReview-WorkListItem-1](https://fhir.nhs.uk/STU3/StructureDefinition/Extension-eRS-ReferralsforReview-WorkListItem-1/_history/1.0)|
|[Extension-eRS-ReferralPriority-1](https://fhir.nhs.uk/STU3/StructureDefinition/Extension-eRS-ReferralPriority-1/_history/1.0)|

|ValueSets|
|-------|
|[eRS API Error Code](https://fhir.nhs.uk/STU3/ValueSet/eRS-APIErrorCode-1/_history/1.0)|
|[eRS Appointment Status](https://fhir.nhs.uk/STU3/ValueSet/eRS-AppointmentStatus-1/_history/1.0)|
|[eRS Assigned Indicator](https://fhir.nhs.uk/STU3/ValueSet/eRS-AssignedIndicator-1/_history/1.0)|
|[eRS Attachment Type](https://fhir.nhs.uk/STU3/ValueSet/eRS-AttachmentType-1/_history/1.0)|
|[eRS Priority](https://fhir.nhs.uk/STU3/ValueSet/eRS-Priority-1/_history/1.0)|
|[eRS Referral Type](https://fhir.nhs.uk/STU3/ValueSet/eRS-ReferralType-1/_history/1.0)|
|[eRS Request Context Status](https://fhir.nhs.uk/STU3/ValueSet/eRS-RequestContextStatus-1/_history/1.0)|
|[eRS Referral List Selector](https://fhir.nhs.uk/STU3/ValueSet/eRS-ReferralListSelector-1/_history/1.0)|

|CodeSystems|
|-------|
|[eRS API Error Code](https://fhir.nhs.uk/STU3/CodeSystem/eRS-APIErrorCode-1/_history/1.0)|
|[eRS Appointment Status](https://fhir.nhs.uk/STU3/CodeSystem/eRS-AppointmentStatus-1/_history/1.0)|
|[eRS Assigned Indicator](https://fhir.nhs.uk/STU3/CodeSystem/eRS-AssignedIndicator-1/_history/1.0)|
|[eRS Attachment Type](https://fhir.nhs.uk/STU3/CodeSystem/eRS-AttachmentType-1/_history/1.0)|
|[eRS Priority](https://fhir.nhs.uk/STU3/CodeSystem/eRS-Priority-1/_history/1.0)|
|[eRS Referral Type](https://fhir.nhs.uk/STU3/CodeSystem/eRS-ReferralType-1/_history/1.0)|
|[eRS Request Context Status](https://fhir.nhs.uk/STU3/CodeSystem/eRS-RequestContextStatus-1/_history/1.0)|
|[eRS Referral List Selector](https://fhir.nhs.uk/STU3/CodeSystem/eRS-ReferralListSelector-1/_history/1.0)|

## Examples ##

### FetchWorklist Operation ###

```

{
  "resourceType": "OperationDefinition",
  "id": "eRS-FetchWorklist-Operation-1",
  "meta": {
    "lastUpdated": "2018-03-05T00:00:00+01:00"
  },
  "url": "https://fhir.nhs.uk/STU3/OperationDefinition/eRS-FetchWorklist-Operation-1",
  "version": "1.0",
  "name": "eRS-FetchWorklist-Operation-1",
  "status": "active",
  "kind": "operation",
  "date": "2018-05-25T00:00:00+01:00",
  "publisher": "NHS Digital",
  "contact": [
    {
      "name": "Interoperability Team",
      "telecom": [
        {
          "system": "email",
          "value": "interoperabilityteam@nhs.net",
          "use": "work"
        }
      ]
    }
  ],
  "description": "Request to retrieve a worklist for a referral request.",
  "code": "ers.fetchworklist",
  "system": false,
  "type": true,
  "instance": false,
  "parameter": [
    {
      "name": "listType",
      "use": "in",
      "min": 1,
      "max": "1",
      "documentation": "Indicates the type of list requested, this is currently fixed to 'REFERRALS_FOR_REVIEW'.",
      "type": "CodeableConcept",
      "binding": {
        "strength": "required",
        "valueSetUri": "https://fhir.nhs.uk/STU3/ValueSet/eRS-ReferralListSelector-1"
      }
    },
    {
      "name": "service",
      "use": "in",
      "min": 0,
      "max": "1",
      "documentation": "The service identifier",
      "type": "Identifier"
    },
    {
      "name": "specialtyAssignedIndicator",
      "use": "in",
      "min": 0,
      "max": "1",
      "documentation": "Indicates whether a Specialty is assigned to the Referral Request. If 'Assigned' the 'Specialty' parameter must be present. If 'Not Assigned' the 'specialtyAssignedIndicator' and 'Specialty' parameter must be absent.",
      "type": "CodeableConcept",
      "binding": {
        "strength": "required",
        "valueSetUri": "https://fhir.nhs.uk/STU3/ValueSet/eRS-AssignedIndicator-1"
      }
    },
    {
      "name": "specialty",
      "use": "in",
      "min": 0,
      "max": "1",
      "documentation": "The Specialty for the service. If present, the 'specialtyAssignedIndicator' parameter must be set to 'Assigned'.",
      "type": "CodeableConcept",
      "binding": {
        "strength": "required",
        "valueSetUri": "https://fhir.nhs.uk/STU3/ValueSet/eRS-Specialty-1"
      }
    },
    {
      "name": "location",
      "use": "in",
      "min": 0,
      "max": "1",
      "documentation": "The service location identifier.",
      "type": "Identifier"
    },
    {
      "name": "clinicianAssignedIndicator",
      "use": "in",
      "min": 0,
      "max": "1",
      "documentation": "Indicates whether a clinician is assigned to the Referral Request. If 'Assigned' the 'Clinician' parameter must be present. If 'Not Assigned' the 'Clinician' parameter must be absent.",
      "type": "CodeableConcept",
      "binding": {
        "strength": "required",
        "valueSetUri": "https://fhir.nhs.uk/STU3/ValueSet/eRS-AssignedIndicator-1"
      }
    },
    {
      "name": "clinician",
      "use": "in",
      "min": 0,
      "max": "1",
      "documentation": "The clinician assigned to the Referral Request. If present, the 'ClinicianAssignedIndicator' parameter must be set to 'Assigned'",
      "type": "Identifier"
    },
    {
      "name": "response",
      "use": "out",
      "min": 1,
      "max": "1",
      "documentation": "The List resource that has been returned in response to the given input parameters",
      "type": "List",
      "profile": {
        "reference": "https://fhir.nhs.uk/STU3/StructureDefinition/eRS-Fetchworklist-List-1"
      }
    }
  ]
}

```

### FetchWorklist ###

```
{
  "resourceType": "List",
  "fhir_comments": [
    "This example message is provided for illustrative purposes only. It has had no clinical validation. Where there are conflicts with the written message specification or schema, the specification or schema shall be considered to take precedence"
  ],
  "meta": {
    "profile": [
      "https://fhir.nhs.uk/STU3/StructureDefinition/eRS-FetchWorklist-List-1"
    ]
  },
  "contained": [
    {
      "resourceType": "Patient",
      "id": "1000000001",
      "meta": {
        "profile": [
          "https://fhir.nhs.uk/STU3/StructureDefinition/eRS-Patient-1"
        ]
      },
      "identifier": [
        {
          "system": "https://fhir.nhs.uk/Id/nhs-number",
          "value": "1000000001"
        }
      ]
    }
  ],
  "status": "current",
  "mode": "snapshot",
  "entry": [
    {
      "extension": [
        {
          "url": "https://fhir.nhs.uk/STU3/StructureDefinition/Extension-eRS-ReferralsforReview-WorkListItem-1",
          "extension": [
            {
              "url": "patient",
              "valueReference": {
                "reference": "#1000000001"
              }
            },
            {
              "url": "priority",
              "valueCodeableConcept": {
                "coding": [
                  {
                    "system": "https://fhir.nhs.uk/STU3/CodeSystem/eRS-Priority-1",
                    "code": "ROUTINE"
                  }
                ]
              }
            },
            {
              "url": "appointmentStart",
              "valueDateTime": "2017-10-05T08:00:00.000Z"
            },
            {
              "url": "clinicalInfoFirstSubmitted",
              "valueDateTime": "2017-10-03T13:30:48.861Z"
            },
            {
              "url": "clinicalInfoPrinted",
              "valueBoolean": false
            },
            {
              "url": "requestContextStatus",
              "valueCodeableConcept": {
                "coding": [
                  {
                    "system": "https://fhir.nhs.uk/STU3/CodeSystem/eRS-RequestContextStatus-1",
                    "code": "NEVER_REVIEWED",
                    "display": "Never Reviewed"
                  }
                ]
              }
            },
            {
              "url": "specialty",
              "valueCodeableConcept": {
                "coding": [
                  {
                    "system": "https://fhir.nhs.uk/STU3/CodeSystem/eRS-Specialty-1",
                    "code": "2WW",
                    "display": "2WW"
                  }
                ]
              }
            },
            {
              "url": "eReferralPathwayStart",
              "valueDateTime": "2017-10-03T13:30:36.139Z"
            },
            {
              "url": "referralType",
              "valueCodeableConcept": {
                "coding": [
                  {
                    "system": "https://fhir.nhs.uk/STU3/CodeSystem/eRS-ReferralType-1",
                    "code": "TRIAGE_DEFERRAL",
                    "display": "Triage Deferral"
                  }
                ]
              }
            }
          ]
        }
      ],
      "item": {
        "reference": "ReferralRequest/000000070001"
      }
    },
    {
      "extension": [
        {
          "url": "https://fhir.nhs.uk/STU3/StructureDefinition/Extension-eRS-ReferralsforReview-WorkListItem-1",
          "extension": [
            {
              "url": "patient",
              "valueReference": {
                "reference": "#1000000001"
              }
            },
            {
              "url": "priority",
              "valueCodeableConcept": {
                "coding": [
                  {
                    "system": "https://fhir.nhs.uk/STU3/CodeSystem/eRS-Priority-1",
                    "code": "TWO_WEEK_WAIT",
                    "display": "2 Week Wait"
                  }
                ]
              }
            },
            {
              "url": "appointmentStart",
              "valueDateTime": "2017-10-05T08:00:00.000Z"
            },
            {
              "url": "clinicalInfoFirstSubmitted",
              "valueDateTime": "2017-10-03T13:17:19.613Z"
            },
            {
              "url": "clinicalInfoPrinted",
              "valueBoolean": false
            },
            {
              "url": "requestContextStatus",
              "valueCodeableConcept": {
                "coding": [
                  {
                    "system": "https://fhir.nhs.uk/STU3/CodeSystem/eRS-RequestContextStatus-1",
                    "code": "NEVER_REVIEWED",
                    "display": "Never Reviewed"
                  }
                ]
              }
            },
            {
              "url": "specialty",
              "valueCodeableConcept": {
                "coding": [
                  {
                    "system": "https://fhir.nhs.uk/STU3/CodeSystem/eRS-Specialty-1",
                    "code": "2WW",
                    "display": "2WW"
                  }
                ]
              }
            },
            {
              "url": "eReferralPathwayStart",
              "valueDateTime": "2017-10-03T13:16:57.813Z"
            },
            {
              "url": "referralType",
              "valueCodeableConcept": {
                "coding": [
                  {
                    "system": "https://fhir.nhs.uk/STU3/CodeSystem/eRS-ReferralType-1",
                    "code": "APPOINTMENT",
                    "display": "Appointment"
                  }
                ]
              }
            }
          ]
        }
      ],
      "item": {
        "reference": "ReferralRequest/000000070000"
      }
    }
  ]
}

```

### Patient Example ###
```

{
  "resourceType": "Patient",
  "id": "9900002831",
  "meta": {
    "profile": [
      "https://fhir.nhs.uk/STU3/StructureDefinition/eRS-Patient-1"
    ]
  },
  "identifier": [
    {
      "system": "https://fhir.nhs.uk/Id/nhs-number",
      "value": "9900002831"
    }
  ]
}

```

### Referral Request Example ###

```

{
  "resourceType": "ReferralRequest",
  "id": "000234620011",
  "fhir_comments": [
    "This example message is provided for illustrative purposes only. It has had no clinical validation. Where there are conflicts with the written message specification or schema, the specification or schema shall be considered to take precedence"
  ],
  "meta": {
    "versionId": "2",
    "profile": [
      "https://fhir.nhs.uk/STU3/StructureDefinition/eRS-ReferralRequest-1"
    ]
  },
  "contained": [
    {
      "resourceType": "HealthcareService",
      "id": "300511",
      "meta": {
        "profile": [
          "https://fhir.nhs.uk/STU3/StructureDefinition/eRS-HealthcareService-1"
        ]
      },
      "identifier": [
        {
          "system": "http://fhir.nhs.net/Id/ers-service",
          "value": "300511"
        }
      ],
      "location": [
        {
          "reference": "#RKE123"
        }
      ],
      "name": "LGI Orthopaedics Service"
    },
    {
      "resourceType": "Location",
      "id": "RKE123",
      "meta": {
        "profile": [
          "https://fhir.nhs.uk/STU3/StructureDefinition/eRS-Location-1"
        ]
      },
      "identifier": [
        {
          "system": "https://directory.spineservices.nhs.uk/STU3",
          "value": "RKE123"
        }
      ]
    },
    {
      "resourceType": "Practitioner",
      "id": "123456789012",
      "meta": {
        "profile": [
          "https://fhir.nhs.uk/STU3/StructureDefinition/eRS-Practitioner-1"
        ]
      },
      "identifier": [
        {
          "system": "https://fhir.nhs.uk/Id/sds-user-id",
          "value": "123456789012"
        }
      ]
    },
    {
      "resourceType": "Appointment",
      "id": "appointment",
      "meta": {
        "profile": [
          "https://fhir.nhs.uk/STU3/StructureDefinition/eRS-Appointment-1"
        ]
      },
      "status": "booked",
      "start": "2016-10-10T09:00:00Z",
      "end": "2016-10-11T09:00:00Z",
      "participant": [
        {
          "actor": {
            "reference": "#300511"
          },
          "status": "accepted"
        },
        {
          "type": [
            {
              "coding": [
                {
                  "system": "http://hl7.org/fhir/ValueSet/encounter-participant-type",
                  "code": "CON"
                }
              ]
            }
          ],
          "actor": {
            "reference": "#123456789012"
          },
          "status": "accepted"
        }
      ]
    },
    {
      "resourceType": "Patient",
      "id": "9900002831",
      "meta": {
        "profile": [
          "https://fhir.nhs.uk/STU3/StructureDefinition/eRS-Patient-1"
        ]
      },
      "identifier": [
        {
          "system": "https://fhir.nhs.uk/Id/nhs-number",
          "value": "9900002831"
        }
      ]
    },
    {
      "resourceType": "DocumentReference",
      "id": "attachment1",
      "meta": {
        "profile": [
          "https://fhir.nhs.uk/STU3/StructureDefinition/eRS-DocumentReference-1"
        ]
      },
      "status": "current",
      "type": {
        "coding": [
          {
            "system": "https://fhir.nhs.uk/STU3/CodeSystem/eRS-AttachmentType-1",
            "code": "REFERRER",
            "display": "Referrer"
          }
        ]
      },
      "indexed": "2016-09-05T13:24:53Z",
      "description": "Clinical comment as entered by clinician",
      "content": [
        {
          "attachment": {
            "id": "5345434",
            "extension": [
              {
                "url": "https://fhir.nhs.uk/STU3/StructureDefinition/Extension-eRS-AttachedBy-1",
                "valueReference": {
                  "reference": "#123456789012"
                }
              }
            ],
            "contentType": "text/plain",
            "url": "Binary/att-100763-5345434",
            "size": 23000,
            "title": "clinical-comment.txt",
            "creation": "2016-07-04"
          }
        }
      ]
    },
    {
      "resourceType": "DocumentReference",
      "id": "attachment2",
      "meta": {
        "profile": [
          "https://fhir.nhs.uk/STU3/StructureDefinition/eRS-DocumentReference-1"
        ]
      },
      "status": "current",
      "type": {
        "coding": [
          {
            "system": "https://fhir.nhs.uk/STU3/CodeSystem/eRS-AttachmentType-1",
            "code": "REFERRER",
            "display": "Referrer"
          }
        ]
      },
      "indexed": "2016-09-05T09:24:53Z",
      "description": "X-ray of relevant body part",
      "content": [
        {
          "attachment": {
            "id": "876220",
            "extension": [
              {
                "url": "https://fhir.nhs.uk/STU3/StructureDefinition/Extension-eRS-AttachedBy-1",
                "valueReference": {
                  "reference": "#123456789012"
                }
              }
            ],
            "contentType": "image/png",
            "url": "Binary/att-100763-876220",
            "size": 20000,
            "title": "animage.png",
            "creation": "2016-07-04"
          }
        }
      ]
    }
  ],
  "extension": [
    {
      "url": "https://fhir.nhs.uk/STU3/StructureDefinition/Extension-eRS-Appointment-1",
      "valueReference": {
        "reference": "#appointment"
      }
    },
    {
      "url": "https://fhir.nhs.uk/STU3/StructureDefinition/Extension-eRS-ClinicalInfoFirstSubmitted-1",
      "valueDateTime": "2016-07-01T09:00:00Z"
    },
    {
      "url": "https://fhir.nhs.uk/STU3/StructureDefinition/Extension-eRS-ClinicalInfoLastUpdated-1",
      "valueDateTime": "2016-07-31T11:20:00Z"
    },
    {
      "url": "https://fhir.nhs.uk/STU3/StructureDefinition/Extension-eRS-ReferralPriority-1",
      "valueCodeableConcept": {
        "coding": [
          {
            "system": "https://fhir.nhs.uk/STU3/CodeSystem/eRS-Priority-1",
            "code": "TWO_WEEK_WAIT",
            "display": "2 Week Wait"
          }
        ]
      }
    }
  ],
  "status": "active",
  "intent": "proposal",
  "subject": {
    "reference": "#9900002831"
  },
  "specialty": {
    "coding": [
      {
        "system": "https://",
        "code": "DERMATOLOGY",
        "display": "Dermatology"
      }
    ]
  },
  "supportingInfo": [
    {
      "reference": "#attachment1"
    },
    {
      "reference": "#attachment2"
    },
    {
      "reference": "ReferralRequest/000231602100"
    },
    {
      "reference": "ReferralRequest/000231601933"
    }
  ]
}

```

### Location Example ###
```
{
  "resourceType": "Location",
  "id": "RKE123",
  "meta": {
    "profile": [
      "https://fhir.nhs.uk/STU3/StructureDefinition/eRS-Location-1"
    ]
  },
  "identifier": [
    {
      "system": "https://directory.spineservices.nhs.uk/STU3",
      "value": "RKE123"
    }
  ]
}
```

### OperationOutcome Example ###
```
{
  "resourceType": "OperationOutcome",
  "id": "f3819168-4847-44ea-8728-1f50a520e294",
  "meta": {
    "profile": [
      "https://fhir.nhs.uk/STU3/StructureDefinition/eRS-OperationOutcome-1"
    ]
  },
  "issue": [
    {
      "severity": "error",
      "code": "required",
      "details": {
        "coding": [
          {
            "system": "https://fhir.nhs.uk/STU3/CodeSystem/eRS-APIErrorCode-1",
            "code": "MISSING_VALUE",
            "display": "A mandatory input field is missing"
          }
        ]
      },
      "diagnostics": "A mandatory input field is missing.",
      "location": [
        "ReferralRequest.identifier"
      ]
    }
  ]
}

```

### DocumentReference Example ###
```

{
  "resourceType": "DocumentReference",
  "meta": {
    "profile": [
      "https://fhir.nhs.uk/STU3/StructureDefinition/eRS-DocumentReference-1"
    ]
  },
  "status": "current",
  "type": {
    "coding": [
      {
        "system": "https://fhir.nhs.uk/STU3/CodeSystem/eRS-AttachmentType-1",
        "code": "REFERRER",
        "display": "Referrer"
      }
    ]
  },
  "indexed": "2016-09-05T14:24:53+01:00",
  "description": "Clinical comment as entered by clinician",
  "content": [
    {
      "attachment": {
        "id": "5345434",
        "extension": [
          {
            "url": "https://fhir.nhs.uk/STU3/StructureDefinition/Extension-eRS-AttachedBy-1",
            "valueReference": {
              "reference": "#123456789012"
            }
          }
        ],
        "contentType": "text/plain",
        "url": "Binary/att-100763-5345434",
        "size": 23000,
        "title": "clinical-comment.txt",
        "creation": "2016-07-04"
      }
    }
  ]
}

```

### Appointment Example ###
```
{
  "resourceType": "Appointment",
  "id": "appointment",
  "meta": {
    "profile": [
      "https://fhir.nhs.uk/STU3/StructureDefinition/eRS-Appointment-1"
    ]
  },
  "status": "booked",
  "start": "2016-10-10T10:00:00+01:00",
  "end": "2016-10-10T10:00:00+01:00",
  "participant": [
    {
      "actor": {
        "reference": "#300511"
      },
      "status": "accepted"
    },
    {
      "type": [
        {
          "coding": [
            {
              "system": "http://hl7.org/fhir/CodeSystem/encounter-participant-type",
              "code": "CON"
            }
          ]
        }
      ],
      "actor": {
        "reference": "#123456789012"
      },
      "status": "accepted"
    }
  ]
}

```

### HealthcareService Example ###
```

{
  "resourceType": "HealthcareService",
  "id": "300511",
  "meta": {
    "profile": [
      "https://fhir.nhs.uk/STU3/StructureDefinition/eRS-HealthcareService-1"
    ]
  },
  "identifier": [
    {
      "system": "http://fhir.nhs.net/Id/ers-service",
      "value": "300511"
    }
  ],
  "location": [
    {
      "reference": "#RKE123"
    }
  ],
  "name": "LGI Orthopaedics Service"
}

```

### Practitioner Example ###
```
{
  "resourceType": "Practitioner",
  "id": "123456789012",
  "meta": {
    "profile": [
      "https://fhir.nhs.uk/STU3/StructureDefinition/eRS-Practitioner-1"
    ]
  },
  "identifier": [
    {
      "system": "https://fhir.nhs.uk/Id/sds-user-id",
      "value": "123456789012"
    }
  ]
}

```