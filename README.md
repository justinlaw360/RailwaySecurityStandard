# Railway Security Standard
Railway Security Standard

Yes! TS 50701:2023 is closely related to several other cybersecurity standards, particularly those used in industrial and railway applications. Here are a few similar standards:

IEC 62443 Series – This is a widely recognized standard for cybersecurity in industrial automation and control systems. TS 50701 is heavily based on IEC 62443, particularly Part 3-2 (Security risk assessment for system design) and Part 3-3 (System security requirements and security levels).

EN 50126 – This standard focuses on Reliability, Availability, Maintainability, and Safety (RAMS) in railway systems. TS 50701 integrates cybersecurity considerations into the RAMS lifecycle.

EN ISO/IEC 27001 & EN ISO 27002 – These are general cybersecurity standards that provide guidelines for information security management systems. TS 50701 aligns with some of their security management principles

China has several railway security standards, particularly focusing on cybersecurity and critical infrastructure protection. Here are some key ones:

IEC 63452 – This is an international railway cybersecurity standard that China has adopted alongside other countries like France and Japan.

Cybersecurity Measures for Railway Critical Information Infrastructure – Adopted by China's Ministry of Transport in December 2023, this regulation strengthens security for railway critical information infrastructure, including network security monitoring, early warning systems, and regular security inspections. https://xxgk.mot.gov.cn/2020/jigou/fgs/202401/t20240104_3980678.html

ISO 27001, TS50701, and IEC 62443 are international standards that provide guidance on cybersecurity best practices.

ISO 27001 is a generic information security standard that can be applied to any organization. It provides a framework for managing information security risks and protecting data and systems.
TS50701 is a railway-specific information security standard. It is based on ISO 27001 and includes additional requirements for railway cybersecurity.
IEC 62443 is a set of standards that provide guidance on cybersecurity for industrial control systems. This includes railway signalling and control systems.
Railways can use these standards to develop and implement their cybersecurity programs.

Railway Cybersecurity Framework – China has developed a national cybersecurity framework for railways, integrating physical security, network security, data security, and personnel security


As rail systems become interconnected, this digitization enhances traffic management, network communication, and energy efficiency. However, it also means more potential threats from cyberattacks. As the attack surface grows, governments and committees worldwide commit to providing guidance and specifications to improve rail organizations' cybersecurity.

In 2021, CENELEC issued technical specifications known as the CLC/TS 50701:2021, the first international standard providing cybersecurity guidance for rail applications. The adoption of new measures like TS 50701 can take time; nevertheless, the standard's influence exceeds EU boundaries, with implementation efforts extending globally. Two years after its publication, the TS 50701 has become the reference standard used by operators to define security requirements.

This blog post will dive into the CLC/TS 50701:2021 (TS 50701), describing the approach and guidance on how to manage cybersecurity in the context of the RAMS (Reliability, Availability, Maintainability, and Safety) lifecycle process for Communications, Signaling, Rolling Stock, and Fixed Installations domains. It will also address the challenges individuals unfamiliar with it could encounter when navigating it. 

The Link Between TS 50701 and IEC 62443 Series
Before diving into the TS 50701, it’s important to understand the relationship between the standard and the IEC 62443. The TS 50701 is a technical specification that relies heavily on the IEC 62443 standard, especially Part 3-2 (Security risk assessment for system design) and Part 3-3 (System security requirements and security levels).

The IEC 62443 series is an international standard that addresses cybersecurity for operational technology in automation and control systems. The TS 50701 is more specific, providing guidance on addressing cybersecurity in the specific railway context. In that sense, the TS 50701 seeks the delicate balance between being auto-conclusive and avoiding repeating content already available in the IEC 62443.

The TS 50701 incorporates numerous concepts and requirements from the IEC 62443 series. Some of the most relevant concepts are:

Security Levels from SL0 to SL4
Risk assessment process and requirements
Component and System-level cybersecurity requirements
Zones and conduits approach
Overview of the TS 50701 Structure
The TS 50701 begins with introductory chapters that cover the scope, references, terms, definitions, and abbreviations. These initial sections establish a common understanding and provide context for the rest of the document. The standard is then divided into seven clauses and seven informative annexes, which delve into specific aspects of the subject matter, offering guidance, requirements, and additional information.  

These clauses are as follows: 

(4) Railway system overview
This chapter provides a beneficial introduction to the rail systems specificities that can be extremely useful for cybersecurity professionals approaching the sector for the first time. It includes, for example, models for the typical railway assets and the typical railway physical architecture.

![image](https://github.com/user-attachments/assets/d4597ca8-4b05-437c-aab4-53892468642a)


rail tech cybersecurity environment
Source: CLC/TS 50701:2021
(5) Cybersecurity within a railway application lifecycle
The standard’s second chapter provides concrete guidance on the cybersecurity activities and deliverables within the RAMS lifecycle proposed by standard EN50126-1. This is extremely useful for identifying the safety-cybersecurity main interfaces and work products that shall be synchronized through a rail project. Here we can see an example extracted from the specification:

![image](https://github.com/user-attachments/assets/35f6d7ac-416d-4d66-a19b-eb656d1da942)

A picture containing text, screenshot, number, fontDescription automatically generated
Source: CLC/TS 50701:2021
‍

(6) System definition and initial risk assessment
This clause guides readers on defining the SuC (System under Consideration) and partitioning it into zones and conduits by performing an initial high-level risk assessment of the overall system.

(7) Detailed risk assessment
As its name indicates, this clause provides a specific methodology to perform a detailed risk assessment of the zones and conduits identified in the previous step. The methodology is very close to the one proposed by the IEC 62443 series. It brings some concepts inherited from rail RAMS processes, such as “Code of Practice” and “Reference Systems,” to simplify the risk assessment when designs from similar projects are being reused.

(8) Cybersecurity requirements
This clause guides how to apply the cybersecurity requirements from IEC 62443-3-3 and IEC 62443-4-2 to rail systems. It also provides guidance on allocating and apportioning the requirements and compensating countermeasures.

(9) Cybersecurity assurance and system acceptance for operation
This clause focuses on assurance and verification activities. It brings a new concept imported from the RAMS processes called “Cybersecurity Case,” which aims to be the documentation artifact to hand over the cybersecurity responsibilities between the system integrator and the system operator.

7. (10) Operational, maintenance, and disposal requirements 

This clause addresses specific operational topics such as vulnerability management and patching processes.

Lastly, we have seven annexes providing specific guidance on several relevant topics:

(Annex A) Handling conduits
(Annex B) Handling legacy systems
The informative Annex B of the TS 50701 proposes guidance on handling cybersecurity for rail legacy systems. A concern was raised that only a few components would implement security requirements compliant with EN IEC 62443-4-2 in the medium term, which could challenge implementing effective cybersecurity into the rail systems. Moreover, rail systems' life cycles typically last decades, so implementing cybersecurity functions might last a long time for some systems.
For this reason, the annex provides guidance on technical and organizational countermeasures to deal with the residual risks derived from legacy systems, such as using security solutions to detect anomalous and malicious traffic in those legacy networks.

(Annex C) Cybersecurity design principles
(Annex D) Safety and Security
(Annex E) Risk acceptance methods
(Annex F) Railway architecture and Zoning
(Annex G) Cybersecurity deliverables content
The Safety Lifecycle in the TS 50701 
Clause 5 of the TS 50701 specifies cybersecurity activities for each phase of a railway application lifecycle as described in the safety standard EN 50126-1. It suggests specific synchronization points between cybersecurity and key functions such as system engineering, safety, RAM, V&V, and T&C. The TS describes the deliverables that should be exchanged for each synchronization point.

The safety process should inform cybersecurity about the safety-related functions or assets to be protected to avoid safety issues. This information would be valuable input for the cybersecurity risk assessment.

The TS 50701 introduces the cybersecurity case, which is heavily inspired by the safety case concept. The idea is that the existing cybersecurity risks can be managed by defining cybersecurity requirements and implementing countermeasures. They can also be transferred to the asset owner by exporting security-related application conditions (SecRAC) and documented as part of the Security Case. The cybersecurity case and its SecRACs shall then be communicated to the Safety management. They can include these SecRACs as part of their Safety-related application conditions (SRACs) and document them on the Safety Case.

So, the cybersecurity case becomes a documentation artifact that includes or references the Cybersecurity Requirement Specification, the security application conditions, and the related assurance evidence. It is used as part of the handover of cybersecurity responsibilities between the system integrator, the system operator, and/or the owner.

![image](https://github.com/user-attachments/assets/3401266e-2293-40ed-8127-de082b8e7574)

cybersecurity case - provided by integrator vs operator
Risk Assessment and Requirements Definition 
‍

The risk assessment process proposed by TS 50701 is very close to that defined by the IEC 62443. The initial risk assessment process is identical in both cases:

![image](https://github.com/user-attachments/assets/6a7a3136-9230-4fd9-9faf-bbb438214a8d)


Risk Assessment
Source: CLC/TS 50701:2021
However, some differences can be found in the process related to the detailed risk assessment. The following diagram from the TS 50701 illustrates the proposed process:

![image](https://github.com/user-attachments/assets/4d989b45-84d9-4561-95ef-f2935c76ee06)


Risk Assessment
Source: CLC/TS 50701
The change introduced by the TS 50701 allows using a “Code of Practice” or a “Reference System” to avoid performing an explicit risk evaluation of specific threats. These two concepts are also imported from the safety practices in the rail sector.

For a Code of Practice to be applicable, the TS requires that it is widely recognized in the railway domain and relevant to rule out the threats for which it is applied effectively.

For the Reference System, the requirements are that it shall be acceptable according to the cybersecurity state-of-the-art and that the functions and interfaces are very similar to the targeted system.

Final Words
The TS 50701 has been a significant first step into defining a common international framework for rail cybersecurity. It quickly became the reference standard for many new rail projects, used or referenced by rail tenders to determine cybersecurity requirements, especially in European markets.

Having been written by experts from the different rail tiers (operators, integrators, and manufacturers) and including safety and cybersecurity specialists, the document accommodates and covers the view and perspective on how cybersecurity should be handled from all these relevant industry roles.

By harnessing collaborative efforts, expertise, and an unwavering commitment to the rail domain, the TS 50701 exemplifies the essence of advancement. This essence is a guiding force, moving the railway industry toward a cyber-secure future. 
