---
layout: faq
permalink: /faqs/
page_header_image: "/assets/images/page_header.jpg"
title: "FAQs"

# FAQ Accordions
accordion:
  heading: "Frequently Asked Questions"
  text: ""
  column1:
    - section: "General Questions"
      questions:
        - question: "What is the International Patient Access (IPA) by HL7® FHIR® project?"
          answer: |
            The International Patient Access (IPA) project is a free and open initiative aimed at empowering patients worldwide by enabling secure, selective sharing of their health data across different healthcare systems. 
            
            By using Health Level Seven (HL7) Fast Healthcare Interoperability Resources (FHIR) standards, IPA ensures that patients can control who accesses their health information while maintaining the highest levels of data protection and privacy.

            HL7®, and FHIR® are the registered trademarks of Health Level Seven International and their use of these trademarks does not constitute an endorsement by HL7.
        - question: "What are HL7 FHIR standards?"
          answer: "HL7 FHIR (Fast Healthcare Interoperability Resources) standards are a set of free and open guidelines developed by Health Level Seven International (HL7) to facilitate the exchange of healthcare information electronically. FHIR standards ensure that health data can be shared and understood across different systems and platforms, promoting interoperability and improved patient care."
        - question: "Why Do We Need IPA?"
          answer: | 
            Many countries already use FHIR, but IPA addresses crucial limitations:
            - Secure Access: IPA ensures that only authorized users and apps can access health information, protecting patient privacy.  It defines how apps get permission to access data using standard methods (like OAuth 2.0).
            - Standardized Data: IPA creates a common set of data types and formats.  This means medical apps can work consistently across different systems worldwide, simplifying development, improving interoperability and patient access.
        - question: "How does the IPA project benefit patients?"
          answer: "IPA allows patients to easily access their health data from various healthcare providers. With easy access, patients become more informed and engaged in their healthcare decisions. This can lead to better health outcomes as patients can track their conditions, understand their treatments, and communicate more effectively with their healthcare providers."
    - section: "Data Sharing and Privacy"
      questions:
        - question: "How can I share my health data using IPA?"
          answer: "With IPA, you can share your health data by granting access to specific health apps. This is done through consent management features within IPA-compliant systems, allowing you to control who sees your information and for what purposes."
        - question: "How is my health data protected?"
          answer: |
            Your health data is protected through robust security measures, including encryption, secure authentication, and compliance with data protection regulations such as the [General Data Protection Regulation](https://gdpr.eu/what-is-gdpr/){: target="_blank} (GDPR) and the [Health Insurance Portability and Accountability Act](https://www.cdc.gov/phlp/php/resources/health-insurance-portability-and-accountability-act-of-1996-hipaa.html){: target="_blank"} (HIPAA).
        - question: "Can I revoke access to my health data?"
          answer: "Yes, you can revoke access to your health data at any time, as patient-controlled consent is a key feature of our system. However, it's important to note that any data that was accessed prior to revocation will still be subject to the privacy policy of the app or health system that accessed the information. This means that you should review their policies to understand how your data will be handled after access is revoked."
  column2:
    - section: "Participating Institutions and Applications"
      questions:
        - question: "What hospitals or clinics allow me to share my data using IPA?"
          answer: "Many hospitals and clinics worldwide are adopting HL7 FHIR standards and participating in the IPA project. To find out if your local healthcare providers support IPA, check with them directly or visit our [official blog](https://blog.hl7.org/international-patient-access) for a list of participating institutions."
        - question: "What apps can I share my data with?"
          answer: "There are numerous health apps that are integrating with IPA to provide seamless data sharing capabilities. These range from personal health management tools to specialized medical applications. For a sample list of compatible apps, visit our [official blog](https://blog.hl7.org/international-patient-access)."
    - section: "Getting Involved"
      questions:
        - question: "How can I get involved with the IPA project?"
          answer: |
            There are several ways to get involved with the IPA project:
            - Contact Your Government Representative: Advocate for the adoption of IPA standards in national healthcare policies.
            - Engage in the IPA Community: Join discussions on the [chat.fhir.org](https://chat.fhir.org/#narrow/channel/261969-IPA){: target="_blank"} chat server.
            - Participate in Connectathons: Test and improve FHIR implementations in collaborative events.
            - Join the HL7 Patient Empowerment Workgroup: Contribute to initiatives that enhance patient engagement and control over their health data.
              - [Upcoming HL7 Events](https://www.hl7.org/events/index.cfm){: target="_blank"}
              - [HL7 Patient Care](https://confluence.hl7.org/display/PC){: target="_blank"}
              - [HL7 Patient Empowerment](https://confluence.hl7.org/display/PE){: target="_blank"}
            - Spread the Word: Share information about the IPA project with your network.
            - Provide Feedback: Your input is invaluable for improving IPA standards.
            - Ask Questions: See if your Electronic Health Records (EHR) vendor supports IPA.
    - section: "Technical Information"
      questions:
        - question: "What are the technical requirements for IPA compliance?"
          answer: |
            At a high-level, to be compliant with IPA, systems must:
            - Implement the FHIR RESTful API framework.
            - Support FHIR Version 4.0.1 or later.
            - Provide endpoints for patient data access and sharing.
            - Utilize the Consent resource for managing patient permissions.
            - Ensure robust security protocols, including OAuth 2.0 and SMART on FHIR.
            For a full list of requirements and specifications, visit the [International Patient Access API Specification](https://hl7.org/fhir/uv/ipa/){: target="_blank"}
        - question: "How is security ensured for health data access APIs?"
          answer: "Millions of dollars have been invested to secure the SMART App Launch mechanisms within the International Patient Access (IPA) framework. Some jurisdictions have confidently opted to forgo app certification, allowing developers to innovate confidently while ensuring patient data is protected. No matter what level of certification frameworks for apps you’ve built, this robust security empowers reliable, efficient health information management."
        - question: "How do I know if my EHR or health IT system supports IPA?"
          answer: "Check with your EHR or health IT system provider to confirm their support for HL7 FHIR IPA standards. You can also refer to our [official blog](https://blog.hl7.org/international-patient-access) for a list of compliant systems and providers."

# Contact Area
contact_area:
  heading: "Get In Touch With Us"
  description: "When unknow printer took a gallery of type and scramblted it to make a type specimen book"
---
