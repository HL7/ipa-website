# IPA Apps Directory Metadata

## Metadata Representation

[apps.json](../apps.json) contains information about each listed app.

### Metadata about the Developer Organization

| Attribute | Meaning | Optionality |
|-----------|---------| ------- |
| `name` | Name of the organization. | Required |
| `website` | A public website for the organization. | Optional |
| `locations` | A list of locations (see below for details) that the organization is associated with. | Required |
| `contact_email` | A public-facing email address of the developer of the app. | Required |

### Metadata about the App Itself

| Attribute | Meaning | Optionality |
|-----------|---------| ------- |
| `name` | Name of the organization. | Required |
| `website` | A public website for the organization. | Optional |
| `capabilitystatement_url` | A url to a publicly accessible CapabilityStatement of the conformant app (typically `/metadata`). | Optional |

### Location Representation

An app developer can provide a single application in multiple country or country-state locations.

This location representation is heavily inspired by the [FHIR `Address` type][fhir-address-type].

| Attribute | Meaning | Optionality |
|-----------|---------| ------- |
| `state` | The state, province, territory, or other administrative division within a country associated with the issuer | Optional |
| `country` | The country associated with the issuer expressed as ISO 3166 2 or 3 letter code | Required |

```json
{
  "locations": [
    { "state": "NY", "country": "US" },
    { "state": "NJ", "country": "US" }
  ]
}
```
#### References:
* fhir-address-type: https://www.hl7.org/fhir/datatypes.html#Address