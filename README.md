International Patient Access (IPA) is a FHIR implementation guide that attempts to establish a universal/global set of requirements for FHIR servers and apps that nations can use to kickstart the ability for their citizens to access their health information via APIs.

# IPA Organization Directory

This repository includes a public directory of organizations that host a FHIR server enabling patient access (among other use-cases) conformant to the [International Patient Access FHIR Implementation Guide](https://hl7.org/fhir/uv/ipa/).
The directory is represented in the [organizations.json file](directory-documentation/organizations.json). The organizations file is a simple listing of organization name, website, type, location, FHIR server url, and a reference to a successful Inferno IPA test.  This information is used for purposes of verification and display. Additional information about the fields in the directory file is available in [organizations-metadata.md](directory-documentation/organizations-metadata.md).


# IPA App Directory

This repository includes a public directory of patient-facing software applications ("apps") that adhere to the [International Patient Access FHIR Implementation Guide](https://hl7.org/fhir/uv/ipa/). The directory is represented in the [apps.json file](directory-documentation/apps.json).The apps file is a simple listing of patient-facing application developers and products. This information is used for purposes of verification and display.  Additional information about the fields in the directory file is available in [apps-metadata.json](directory-documentation/apps-metadata.json).

## Requirements for Organizations
### Types of Organizations
Today, the types of organizations permitted in the IPA Organization Directory are limited to the following:

- clinical health systems and hospitals providing patient care
- national and regional pharmacy chains
- national and regional laboratory diagnostics providers
- national and regional health insurance payors
- government and governmental agencies. 

Participation is currently limited to these issuers because it’s easier for website visitors to understand who these organizations are and how they work, to understand where data originate and are held, and to audit if issues arise. 

### Technical Requirements
Organizations and Apps must follow the [International Patient Access FHIR Implementation Guide](https://hl7.org/fhir/uv/ipa/). The minimum requirements to comply to the specification are support for: 
* the [IPA Patient Profile](https://hl7.org/fhir/uv/ipa/StructureDefinition-ipa-patient.html),
* at least one other [additional IPA Profile](https://hl7.org/fhir/uv/ipa/artifacts.html#profiles-primary-resources),
* the IPA required (SHALL) [search parameters for the profiles you support](https://hl7.org/fhir/uv/ipa/CapabilityStatement-ipa-server.html#Patient1-9),
* and the required (SHALL) [SMART on FHIR Capabilities](https://hl7.org/fhir/uv/ipa/access.html#smart-on-fhir-server-capabilities)."


### Getting Listed
The HL7 IPA Project reviews each submission, verifies information contained in the submission, and performs technical validation. In the event that a submission requires subjective evaluation, the HL7 Patient Care Workgroup may be consulted for resolution. 
#### Organization Listing
* Organizations hosting IPA-compliant FHIR servers should complete the registration and [attestation form](https://forms.gle/U73qymT4SjMDcF1x6).

#### App Listing
* Developers offering IPA-compliant apps should complete the registration and [attestation form](https://forms.gle/oWdXck4by1yAFy4FA).


# Technical Website Deployment Documentation
Unrelated to directory listings is the [IPA Website]() [Deployment instructions](site-build-instructions/index.md)