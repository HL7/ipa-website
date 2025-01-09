---
layout: faq
permalink: /faqs/
lang: de
page_header_image: "/assets/images/page_header.jpg"
title: "FAQs (German)"

# FAQ Accordions
accordion:
  heading: "Frequently Asked Questions"
  text: ""
  column1:
    - section: "General Questions"
      questions:
        - question: "Was ist das International Patient Access (IPA)-Projekt von HL7® und FHIR®?"
          answer: |
            Das Projekt International Patient Access (IPA) ist eine kostenlose und offene Initiative, die Patienten weltweit durch die sichere und selektive Weitergabe ihrer Gesundheitsdaten zwischen verschiedenen Gesundheitssystemen unterstützen soll. 
            
            Durch die Verwendung der Standards „Fast Healthcare Interoperability Resources“ (FHIR) von Health Level Seven (HL7) stellt IPA sicher, dass Patienten kontrollieren können, wer auf ihre Gesundheitsinformationen zugreift, während gleichzeitig ein Höchstmaß an Datenschutz und Privatsphäre gewährleistet wird.

            HL7® und FHIR® sind eingetragene Marken von Health Level Seven International und ihre Verwendung dieser Marken stellt keine Billigung durch HL7 dar.
        - question: "Was sind HL7 FHIR-Standards?"
          answer: |
            HL7 FHIR-Standards (Fast Healthcare Interoperability Resources) sind eine Reihe kostenloser und offener Richtlinien, die von Health Level Seven International (HL7) entwickelt wurden, um den elektronischen Austausch von Gesundheitsinformationen zu erleichtern. 
            
            FHIR-Standards stellen sicher, dass Gesundheitsdaten über verschiedene Systeme und Plattformen hinweg geteilt und verstanden werden können, was die Interoperabilität und eine verbesserte Patientenversorgung fördert.
        - question: "Warum brauchen wir IPA?"
          answer: | 
            Viele Länder verwenden bereits FHIR, aber IPA behebt entscheidende Einschränkungen:
            - Sicherer Zugriff: IPA stellt sicher, dass nur autorisierte Benutzer und Apps auf Gesundheitsinformationen zugreifen können, wodurch die Privatsphäre der Patienten geschützt wird. Es definiert, wie Apps mithilfe von Industriestandardmethoden (wie OAuth 2.0) die Berechtigung zum Zugriff auf Daten erhalten.
            - Standardisierte Daten: IPA erstellt einen gemeinsamen Satz von Datentypen und -formaten. Dies bedeutet, dass medizinische Apps weltweit auf verschiedenen Systemen konsistent funktionieren können, was die Entwicklung vereinfacht, die Interoperabilität und den Patientenzugriff verbessert.
            - Konsistenter globaler Standard: IPA ermöglicht es einzelnen Regionen und Nationen, bewährte FHIR-Standards wiederzuverwenden, um eine digitale Gesundheits-IT-Wirtschaft voranzutreiben und die Interoperabilität zu verbessern.
        - question: "Welchen Nutzen hat das IPA-Projekt für Patienten?"
          answer: |
            IPA ermöglicht Patienten den einfachen Zugriff auf ihre Gesundheitsdaten von verschiedenen Gesundheitsdienstleistern. Durch den einfachen Zugriff sind die Patienten besser informiert und können besser in ihre Gesundheitsentscheidungen eingebunden werden.

            Dies kann zu besseren Gesundheitsergebnissen führen, da die Patienten ihren Zustand verfolgen, ihre Behandlungen verstehen und effektiver mit ihren Gesundheitsdienstleistern kommunizieren können.
    - section: "Datenfreigabe und Datenschutz"
      questions:
        - question: "Wie kann ein Patient seine Gesundheitsdaten mithilfe von IPA teilen?"
          answer: "Mit IPA können Patienten Gesundheitsdaten teilen, indem sie Zugriff auf bestimmte Gesundheits-Apps gewähren. Dies geschieht über Einwilligungsverwaltungsfunktionen in IPA-konformen Systemen, sodass der Patient kontrollieren kann, wer seine Informationen sieht und zu welchem ​​Zweck."
        - question: "Wie werden die Gesundheitsdaten der Patienten geschützt?"
          answer: |
            Die Gesundheitsdaten der Patienten werden durch robuste Sicherheitsmaßnahmen geschützt, darunter Verschlüsselung, sichere Authentifizierung und die Einhaltung von Datenschutzbestimmungen wie der Datenschutz-Grundverordnung (DSGVO) und dem Health Insurance Portability and Accountability Act (HIPAA).
        - question: "Kann der Patient den Zugriff auf seine Gesundheitsdaten widerrufen?"
          answer: "Ja, Patienten können den Zugriff auf Ihre Gesundheitsdaten jederzeit widerrufen, da die patientengesteuerte Zustimmung ein wesentliches Merkmal unseres Systems ist. Es ist jedoch wichtig zu beachten, dass alle Daten, auf die vor dem Widerruf zugegriffen wurde, weiterhin der Datenschutzrichtlinie der App oder des Gesundheitssystems unterliegen, das auf die Informationen zugegriffen hat. Dies bedeutet, dass Sie deren Richtlinien überprüfen sollten, um zu verstehen, wie mit Ihren Daten nach dem Widerruf des Zugriffs verfahren wird."
  column2:
    - section: "Beteiligte Institutionen und Anwendungen"
      questions:
        - question: "Welche Krankenhäuser oder Kliniken erlauben einem Patienten, seine Daten mithilfe von IPA zu teilen?"
          answer: |
            Viele Krankenhäuser und Kliniken weltweit übernehmen HL7 FHIR-Standards und nehmen am IPA-Projekt teil. Um herauszufinden, ob Ihre lokalen Gesundheitsdienstleister IPA unterstützen, wenden Sie sich direkt an sie oder besuchen Sie unseren [offiziellen Blog](https://blog.hl7.org/international-patient-access){: target="_blank"} für eine Liste der teilnehmenden Institutionen.
        - question: "Mit welchen Apps kann ein Patient seine Daten teilen?"
          answer: |
            Zahlreiche Gesundheits-Apps lassen sich in IPA integrieren und bieten so nahtlose Möglichkeiten zum Datenaustausch. Diese reichen von persönlichen Gesundheitsmanagement-Tools bis hin zu speziellen medizinischen Anwendungen. Eine Beispielliste kompatibler Apps finden Sie in unserem [offiziellen Blog](https://blog.hl7.org/international-patient-access){: target="_blank"}.
    - section: "Mitmachen"
      questions:
        - question: "Wie kann ich mich am IPA-Projekt beteiligen?"
          answer: |
            Es gibt mehrere Möglichkeiten, sich am IPA-Projekt zu beteiligen:
            - Kontaktieren Sie Ihren Regierungsvertreter: Setzen Sie sich für die Übernahme von IPA-Standards in die nationale Gesundheitspolitik ein.
            - Beteiligen Sie sich an der IPA-Community: Nehmen Sie an Diskussionen auf dem [chat.fhir.org](https://chat.fhir.org/#narrow/channel/261969-IPA){: target="_blank"} Chat-Server.
            - Beteiligen Sie sich an Connectathons: Testen und verbessern Sie FHIR-Implementierungen bei gemeinsamen Veranstaltungen.
            - Treten Sie der HL7-Arbeitsgruppe zur Patientenermächtigung bei: Tragen Sie zu Initiativen bei, die die Patientenbeteiligung und -kontrolle über ihre Gesundheitsdaten verbessern.
              - [Bevorstehende HL7-Events](https://www.hl7.org/events/index.cfm){: target="_blank"}
              - [HL7 Patientenversorgung](https://confluence.hl7.org/display/PC){: target="_blank"}
              - [HL7 Patientenermächtigung](https://confluence.hl7.org/display/PE){: target="_blank"}
            - Verbreiten Sie die Nachricht: Geben Sie Informationen über das IPA-Projekt an Ihr Netzwerk weiter.
            - Geben Sie Feedback: Ihr Input ist für die Verbesserung der IPA-Standards von unschätzbarem Wert.
            - Stellen Sie Fragen: Prüfen Sie, ob Ihr Anbieter elektronischer Gesundheitsakten (EHR) IPA unterstützt.
    - section: "Technische Informationen"
      questions:
        - question: "Was sind die technischen Anforderungen für die IPA-Konformität?"
          answer: |
            Um IPA-konform zu sein, müssen Systeme auf hoher Ebene:
            - Das FHIR RESTful API-Framework implementieren.
            - FHIR Version 4.0.1 oder höher unterstützen.
            - Endpunkte für den Zugriff und die Freigabe von Patientendaten bereitstellen.
            - Die Einwilligungsressource zur Verwaltung von Patientenberechtigungen nutzen.
            - Robuste Sicherheitsprotokolle sicherstellen, einschließlich OAuth 2.0 und SMART auf FHIR.
             
            Eine vollständige Liste der Anforderungen und Spezifikationen finden Sie in der [International Patient Access API Specification](https://hl7.org/fhir/uv/ipa/){: target="_blank"}
        - question: "Wie wird die Sicherheit von APIs für den Zugriff auf Gesundheitsdaten gewährleistet?"
          answer: |
            Es wurden Millionen von Dollar investiert, um die SMART App Launch-Mechanismen im Rahmen des International Patient Access (IPA) zu sichern. 
            
            Einige Gerichtsbarkeiten haben sich bewusst dafür entschieden, auf eine App-Zertifizierung zu verzichten, sodass Entwickler selbstbewusst Innovationen entwickeln und gleichzeitig sicherstellen können, dass die Patientendaten geschützt sind.  
            
            No matter what level of certification frameworks for apps you’ve Unabhängig davon, welche Zertifizierungsrahmen Sie für Ihre Apps erstellt haben, ermöglicht diese robuste Sicherheit ein zuverlässiges und effizientes Gesundheitsinformationsmanagement.
        - question: "Wie erfahre ich, ob mein Gesundheitssystem oder meine elektronische Patientenakte IPA unterstützt?"
          answer: |
            Erkundigen Sie sich bei Ihrem Anbieter von EHR- oder Gesundheits-IT-Systemen, ob dieser die HL7 FHIR IPA-Standards unterstützt. Sie können auch in unserem [offiziellen Blog](https://blog.hl7.org/international-patient-access){: target="_blank"} nach einer Liste kompatibler Systeme und Anbieter suchen.

# Contact Area
contact_area:
  heading: "Get In Touch With Us"
  description: "When unknow printer took a gallery of type and scramblted it to make a type specimen book"
---
