# IPA Organization Directory Metadata

## Metadata Representation

[organizations.json](../organizations.json) contains information about each listed organization.

| Attribute | Meaning | Optionality |
|-----------|---------|--------|
| `name` | Name of the organization. | Required |
| `label` | A representative label for the organization. Used when organization name may be too long, misrepresentative, or provides more common nomenclature. | Required |
| `website` | A public website for the organization. | Required |
| `fhir_base_url` | The base url of the organization's FHIR server that conforms to IPA. | Optional |
| `org_type` | The type of organization (see below for details). | Required |
| `locations` | A list of locations (see below for details) that the organization is associated with. | Required |
| `ipa_inferno_test_result` | A url to a publicly accessible test run result for the [IPA Inferno test kit](https://inferno.healthit.gov/test-kits/international-patient-access/). | Optional |

### Organization Type Representation

The type of institution may be important for website visitors. This value set captures the currently permitted and participating [organization types in the IPA Directory]: clinical health systems and hospitals providing patient care, pharmacies, laboratory diagnostics providers, health insurance payors, and government and governmental agencies.

A simple hierarchy provides an easier means to segregate government and non-governmental issuers for those who find that valuable.

| Attribute | Meaning |
|-----------|---------|
| `organizational.health_system` | A clinical health system or hospital providing patient care |
| `organizational.pharmacy` | A national or regional pharmacy chain |
| `organizational.laboratory` | A national or regional laboratory diagnostics provider |
| `organizational.insurer` | A national or regional health insurance payor |
| `governmental.nation` | A nation or national governmental agency issuing for a nation |
| `governmental.state_province_territory` | A state, province, territory or governmental agency issuing for a state, province, or territory |
| `governmental.city_county` | A city, county or governmental agency issuing for a city |
| `governmental.health_jurisdiction` | A jurisdiction or governmental agency issuing for a jurisdiction |
| `governmental.agency` | A governmental agency |

### Location Representation

In order to best represent the reality of an institution spanning multiple locations, an organization can be associated to multiple country-state locations.

This location representation is heavily inspired by the [FHIR `Address` type][fhir-address-type].

| Attribute | Meaning |  Optionality |
|-----------|---------|--------|
| `state` | The state, province, territory, or other administrative division within a country associated with the issuer | Required |
| `country` | The country associated with the issuer expressed as ISO 3166 2 or 3 letter code | Required |

Each location within the list of `locations` should be independently-defined. For
example, if an issuer has operations in the states of New York and New Jersey, each of its
`locations` should include both state and country:


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