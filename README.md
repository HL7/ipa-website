# ipa-website
International Patient Access (IPA) is a FHIR implementation guide that attempts to establish a universal/global set of requirements for FHIR servers and apps that nations can use to kickstart the ability for their citizens to access their health information via APIs.

# IPA Organization Directory

This repository includes a public directory of organizations that host a FHIR server enabling patient access (among other use-cases) conformant to the [International Patient Access FHIR Implementation Guide](https://hl7.org/fhir/uv/ipa/).
The directory is represented in the [ipa-organizations.json file](ipa-organizations.json) and [ipa-apps.json file](ipa-apps.json). The organizations file is a simple listing of organization name, website, type, location, FHIR server url, and a reference to a successful Inferno IPA test.  This information is used for purposes of verification and display. 

# IPA App Directory

This repository includes a public directory of patient-facing software applications ("apps") that adhere to the [International Patient Access FHIR Implementation Guide](https://hl7.org/fhir/uv/ipa/). The directory is represented in the [ipa-apps.json file](ipa-apps.json).The apps file is a simple listing of patient-facing application developers and products. This information is used for purposes of verification and display. 

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
Organizations and Apps must follow the [International Patient Access FHIR Implementation Guide](https://hl7.org/fhir/uv/ipa/). Each production implementation must fully comply with the open standards and specifications noted therein.

### Getting Listed
Complete the registration and [attestation form](https://www.commontrustnetwork.org/joinhealth).

The HL7 IPA Project reviews each submission, verifies information contained in the submission, and performs technical validation. In the event that a submission requires subjective evaluation, the HL7 Patient Care Workgroup may be consulted for resolution.