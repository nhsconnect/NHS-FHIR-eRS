---
title: Retrieve Referral Request Data
keywords:  rest, resource
sidebar: foundations_sidebar
permalink: referralrequest_resources_stu3.html
summary: "Example of the Referral Request profile"
---

{% include warning.html content="The profiles below have been created using FHIR STU3 and are currently in a draft state. Is it advised not to develop 
using this version until further notice." %}

## Profiles ##

|OperationDefinition|
|-------|
|[eRS-FetchWorklist-Operation-1](https://fhir.nhs.uk/STU3/OperationDefinition/eRS-FetchWorklist-Operation-1)|


|StructureDefinition| 
|-------|
| [eRS-ReferralRequest-1](https://fhir.nhs.uk/STU3/StructureDefinition/eRS-ReferralRequest-1) | 
| [eRS-Patient-1](https://fhir.nhs.uk/STU3/StructureDefinition/eRS-Patient-1) | 
| [eRS-DocumentReference-1](https://fhir.nhs.uk/STU3/StructureDefinition/eRS-DocumentReference-1) | 
| [eRS-Appointment-1](https://fhir.nhs.uk/STU3/StructureDefinition/eRS-Appointment-1) | 
| [eRS-Practitioner-1](https://fhir.nhs.uk/STU3/StructureDefinition/eRS-Practitioner-1) | 
| [eRS-ReferralsForReview-HealthcareService-1](https://fhir.nhs.uk/STU3/StructureDefinition/eRS-ReferralsForReview-HealthcareService-1) | 
| [eRS-Location-1](https://fhir.nhs.uk/STU3/StructureDefinition/eRS-Location-1) | 
| [eRS-OperationOutcome-1](https://fhir.nhs.uk/STU3/StructureDefinition/eRS-OperationOutcome-1) | 
| [eRS-Specialty-ValueSet-1](https://fhir.nhs.uk/STU3/StructureDefinition/eRS-Specialty-ValueSet-1) |

|Extensions|
|-------|
|[Extension-eRS-Appointment-1](https://fhir.nhs.uk/STU3/StructureDefinition/Extension-eRS-Appointment-1)|
|[Extension-eRS-ClinicalInfoFirstSubmitted-1](https://fhir.nhs.uk/STU3/StructureDefinition/Extension-eRS-ClinicalInfoFirstSubmitted-1)|
|[Extension-eRS-ClinicalInfoLastUpdated-1](https://fhir.nhs.uk/STU3/StructureDefinition/Extension-eRS-ClinicalInfoLastUpdated-1)|
|[Extension-eRS-AttachedBy-1](https://fhir.nhs.uk/STU3/StructureDefinition/Extension-eRS-AttachedBy-1)|

|ValueSets|
|-------|
|[eRS API Error Code](https://fhir.nhs.uk/STU3/ValueSet/eRS-APIErrorCode-1)|
|[eRS Appointment Status](https://fhir.nhs.uk/STU3/ValueSet/eRS-AppointmentStatus-1)|
|[eRS Attachment Type](https://fhir.nhs.uk/STU3/ValueSet/eRS-AttachmentType-1)|
|[eRS Priority](https://fhir.nhs.uk/STU3/ValueSet/eRS-Priority-1)|
|[eRS Referral Type](https://fhir.nhs.uk/STU3/ValueSet/eRS-ReferralType-1)|
|[eRS Request Context Status](https://fhir.nhs.uk/STU3/ValueSet/eRS-RequestContextStatus-1)|

|CodeSystems|
|-------|
|[eRS API Error Code](https://fhir.nhs.uk/STU3/CodeSystem/eRS-APIErrorCode-1)|
|[eRS Appointment Status](https://fhir.nhs.uk/STU3/CodeSystem/eRS-AppointmentStatus-1)|
|[eRS Attachment Type](https://fhir.nhs.uk/STU3/CodeSystem/eRS-AttachmentType-1)|
|[eRS Priority](https://fhir.nhs.uk/STU3/CodeSystem/eRS-Priority-1)|
|[eRS Referral Type](https://fhir.nhs.uk/STU3/CodeSystem/eRS-ReferralType-1)|
|[eRS Request Context Status](https://fhir.nhs.uk/STU3/CodeSystem/eRS-RequestContextStatus-1)|

## Examples ##

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
          "https://fhir.nhs.uk/STU3/StructureDefinition/eRS-ReferralsForReview-HealthcareService-1"
        ]
      },
      "identifier": [
        {
          "system": "https://fhir.nhs.uk/Id/eRS-service",
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
            "system": "https://fhir.nhs.uk/STU3/ValueSet/eRS-APIErrorCode-1",
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
  "type": {
    "coding": [
      {
        "system": "https://fhir.nhs.uk/STU3/ValueSet/eRS-AttachmentType-1",
        "code": "REFERRER",
        "display": "Referrer"
      }
    ]
  },
  "indexed": "2016-09-05T14:24:53+01:00",
  "status": "current",
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
}

```

### HealthcareService Example ###
```

{
  "resourceType": "HealthcareService",
  "id": "300511",
  "meta": {
    "profile": [
      "https://fhir.nhs.uk/STU3/StructureDefinition/eRS-ReferralsForReview-HealthcareService-1"
    ]
  },
  "identifier": [
    {
      "system": "https://fhir.nhs.uk/Id/ers-service",
      "value": "300511"
    }
  ],
  "location": {
    "reference": "#RKE123"
  },
  "serviceName": "LGI Orthopaedics Service"
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
