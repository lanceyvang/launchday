## Framework
* Policies: High-level statements of management intent.
* Standards: How an organization will carry out policies.
* Procedures: Step by step processes to achieve security objective.
* Guidelines: Best practices and recommendations.

## Regulations
* HIPAA (Health Insurance Portability and Accountability Act)
    * Security and privacy rules that affect healthcare providers, health insurers, and health information clearinghouses (bills from member banks are exchanged).

* (PCI DSS) Payment Card Industry Data Security Standard 
    * Rules about the storage, processing, and transmission of credit card and debit card information.
    * Not a law but contractual obligation.

* GLBA (Gramm-Leach-Bliley Act)
    * Covers financial insitutions.
    * Have a formal security program and individual responsible for that program.

* SOX (Sarbanes-Oxley)
    * Financial records of publicly traded companies.
    * Strong degree of assurance around the IT system that store and process those records.

* FERPA (Family Educational Rights and Privacy Act)
    * Educational insituations implement security and privacy control for student and educational records.


## NIST Cybersecurity Framework
* National Insitute for Standards and Technology
* Resposible for developing cybersecurity standards across US federal government.
* Includes 3 components:
    1. The Framework Core:
        * Identify, protect, detect, respond, recover
        * Divides each of these functions into categories, subcategories, and informative references.
    2. Framework Implementation Tiers
        * Assesses how an organization is positioned to meet cybersecurity objectives.
    3. Framework Profiles
        * Describes how a specific organization might approach the security functions covered by the Framework Core.
        * Use framework profile to descripbe its current state and then separate profile to descrie its desired future state.

CIA vs AAA
* AAA (Authentication, Authorization, Accounting)
    * AAA framework used to control access to computers, networks, and services
    * Authenication requiring credentials like username and password.
    * Authorization allows owner of the identity to perform actions oro to gain access to systems.
    * Accounting monitors usage and provides information about how and what users are doing.

CIA Triad
* Three key objectives of cybersecurity programs.
    * Confidentiality ensures that unauthoried individuals are not able to gain access to sensitive information.
        * Firewalls, ACL, encryption
        * Unauthorized disclore of sensitve information.
    * Integrity ensures that there is no unauthorized modifcations to information or systems, intentionally or unintentionally. 
        * Hashing and integrity monitoring
        * Power spikes can cause corruption of information.
    * Availability ensures information and systems are ready to meet the needs ot legitimate users at the time those users request them.
        * Fault tolerance, clustering, backups

