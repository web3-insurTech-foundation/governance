# Comprehensive Privacy Policy for the InsurTech Operating Protocol

# I. Introduction, Scope, and Regulatory Mandate
## 1.1. Purpose, Applicability, and Key Definitions
This Privacy Policy establishes the authoritative standards and procedures for the collection, processing, security, and disposal of Personal Data (PD) and Sensitive Personal Information (SPII) utilized by the InsurTech Operating Protocol (the "Protocol"). Its purpose is to ensure full regulatory adherence while preserving the core tenets of decentralized ledger technology (DLT). This policy applies universally to the Protocol Foundation (the managing entity), all software developers and contributors, network participants (nodes, miners), policyholders (data subjects), and off-chain service providers or partners.   

To ensure clarity and transparency, especially regarding the complex architecture of a DLT system, key definitions are provided in plain language, consistent with the requirements of major global privacy frameworks.   

Protocol Foundation (The Controller): The legal entity registered to oversee the Protocol, which assumes primary responsibility for determining the purposes and means of processing PII required for legal, regulatory, and contractual functions.

Data Subject: An identified or identifiable natural person to whom the Personal Data relates (e.g., policyholders, claimants, or open-source contributors).

Pseudonymous Identifier: A cryptographic address or account that identifies a user on the DLT network but does not directly reveal the real-world identity.   

On-Chain Data: Immutable data permanently recorded on the Protocol’s distributed ledger, restricted exclusively to non-reconstructable cryptographic hashes and pseudonymous transaction metadata.   

Off-Chain Data (PII Repository): Personal Data and Sensitive Personal Information stored separately from the DLT in secure, centralized, and controlled databases, necessary for regulatory compliance and contract fulfillment.

Logical Deletion: The specific Technical and Organizational Measure (TOM) employed to satisfy the Right to Erasure, involving the permanent physical deletion of off-chain PII coupled with the irreversible destruction of all cryptographic keys linking the deleted PII to its corresponding on-chain hash.

## 1.2. Governing Frameworks and Compliance Mandate
The Protocol operates under a comprehensive, maximalist compliance strategy, adhering to the strictest applicable global privacy regulations. The European Union’s General Data Protection Regulation (GDPR) serves as the baseline standard for processing activities worldwide, given its extraterritorial reach and severe penalties for non-compliance. This strategy minimizes regulatory fragmentation and manages the high legal risk associated with global DLT operations.   

Mandated compliance extends beyond GDPR to include:

The California Consumer Privacy Act (CCPA) as amended by the California Privacy Rights Act (CPRA).

The Personal Information Protection Law (PIPL) of China and the Lei Geral de Proteção de Dados (LGPD) of Brazil.

Specific InsurTech sector regulations, including standards set forth by the National Association of Insurance Commissioners (NAIC) model laws, which govern data retention and auditability.   

The Policy affirms absolute commitment to the seven fundamental principles of data processing required under GDPR Article 5: Lawfulness, Fairness, Transparency, Purpose Limitation, Data Minimisation, Accuracy, Storage Limitation, and Integrity/Confidentiality.   

## 1.3. Principle of Privacy-by-Design and Default
The Protocol is engineered to incorporate privacy and data protection measures from the initial stages of system development, upholding the legal mandate of Privacy-by-Design and Default (PbD). This means the default settings for all Protocol services are configured to offer the maximum level of privacy to the Data Subject.   

For a DLT operation, PbD is manifested through key architectural commitments: the implementation of a necessary Hybrid Storage Model (Section IV), which separates mutable PII from the immutable DLT, and the pervasive use of Zero-Knowledge Proofs (ZKP) (Section V) to enable verifiability without compromising data confidentiality. These measures proactively address the fundamental tensions between decentralized operations and regulatory mandates.   

# II. Roles, Accountability, and Governance in the Protocol
## 2.1. Defining the Data Controller: The Protocol Foundation
The identification of a Data Controller is a critical challenge in decentralized networks, where traditional central authority is absent, leading to legal ambiguity. However, because the InsurTech Operating Protocol must adhere to highly regulated financial and insurance mandates—specifically Anti-Money Laundering (AML), Know-Your-Customer (KYC), and fiduciary requirements—a single legal entity must assume accountability.   

Consequently, the Protocol Foundation is formally designated as the primary Data Controller for all processing of PII, especially concerning off-chain repositories necessary for legal and regulatory adherence. The Foundation determines the explicit purposes and the technical means of processing PII, including establishing data retention periods. This designation provides the essential centralized legal accountability required for compliance, offering a clear point of legal recourse for data subjects and regulatory bodies.   

## 2.2. Defining Data Processors and Sub-Processors
Any individual or entity that handles or operates on PII under the strict, explicit instruction of the Protocol Foundation acts as a Data Processor. This includes, but is not limited to, specific licensed insurance partners, third-party KYC/AML verification services, and, in a technical sense, the network nodes themselves when they process data references or transaction metadata based on the Controller’s coded instructions.   

Processors are mandated to implement appropriate Technical and Organisational Measures (TOMs) and are bound by the instructions stipulated by the Controller. The relationship between the Foundation and any Processor must be formalized through a legally binding Data Processing Agreement (DPA), which meticulously documents the processing operations and security requirements.   

## 2.3. Determining Joint Controllership
Joint controllership arises in situations where the Protocol Foundation and an external regulated entity (e.g., a collaborating insurance carrier) jointly define the purpose and means for processing the same PII. This typically occurs during activities requiring shared data pools, such as co-underwriting or mutual fraud detection mechanisms.   

In cases of joint control, a formal Joint Controller Agreement must be established. This document explicitly delineates the specific responsibilities of each controller, including who manages data subject rights requests (like SARs or erasure requests), who is responsible for data breach notification, and who maintains specific security protocols for the shared data. This measure ensures compliance clarity even when data processing relies on complex, distributed collaborations.   

## 2.4. Accountability Measures and Documentation
The Protocol Foundation is responsible for demonstrating compliance with every principle of data protection law. This includes maintaining comprehensive records of processing activities, regularly conducting Data Protection Impact Assessments (DPIAs)—especially on novel DLT implementations—and verifying the compliance status of all contracted third-party processors.   

The table below illustrates the definitive assignment of roles based on the necessity of the processing activity:

Table 1: Assignment of Data Controller and Processor Responsibilities in the Protocol

| Data Processing Activity	| PII Type | Assigned Role (Controller/Processor) | Legal Basis / Justification |
| ------------------------- | -------- | ------------------------------------ | --------------------------- |
| KYC/AML Verification (Off-Chain) | Identity Documents, Biometrics | Protocol Foundation (Controller)	| Legal Obligation (AML/InsurTech Mandates) |
| Storing Off-Chain InsurTech PII |	Underwriting/Claims Data (SPII) |	Protocol Foundation (Controller)	| Contractual Necessity (Fulfilling policy obligations) |
| Network Telemetry/Usage Data | IP Address, Usage Patterns | Protocol Foundation (Controller)	| Legitimate Interest (Network & Information Security) |
| Storing Encrypted Transaction Hashes (On-Chain) | Pseudonymous Identifiers | Network Nodes (Processors/Technical Functionaries)	| Processing under Controller instruction (Protocol automation) |

  
# III. Data Collection, Minimization, and Lawful Basis
## 3.1. Categories of Personal Data Processed
Data processed by the Protocol is strictly categorized based on its sensitivity and architecture:

Off-Chain PII/SPII: This includes basic identifying information (name, contact details), financial PII (bank account data, credit or debit card data), creditworthiness scores, KYC verification documents, and potentially health data related to risk assessment (which qualifies as SPII). Due to the inherent risk of identity theft or fraud associated with this information, it is subject to the strictest security controls.   

On-Chain Data: This category is limited to non-identifying cryptographic data, specifically pseudonymous cryptographic addresses and irreversible transaction hashes that serve only as metadata references to off-chain records.   

## 3.2. Lawful Bases for Processing InsurTech PII
Every processing activity carried out by the Protocol Foundation must be supported by a lawful basis as defined by GDPR. For a regulated financial technology project, reliance primarily falls upon:

Legal Obligation: This forms the bedrock for critical functions such as mandated KYC/AML procedures, necessary regulatory reporting, and fraud prevention protocols. The nature of the financial services sector necessitates a reliance on legal mandates , as the stability and compliance of core network functions cannot be subject to the operational risk introduced by relying solely on consent (which can be withdrawn).   

Contractual Necessity: Processing PII necessary for the execution and administration of the insurance contract, including underwriting, assessing risk, and settling claims.   

Legitimate Interests: Processing for core operational support, such as ensuring network and information security, provided this activity does not infringe upon the fundamental rights of the Data Subject.   

Explicit Consent: Used restrictively for optional processing activities or for certain categories of highly sensitive data that fall outside legal or contractual necessity (e.g., marketing or optional research).

## 3.3. Handling Sensitive Personal Information (SPII)
The InsurTech sector inherently processes SPII, including financial data and, in certain circumstances, personal health information related to risk (e.g., life insurance underwriting). The Foundation commits to processing SPII under heightened restrictions:   

Safeguards: SPII is subject to strict purpose limitation, meaning it is only used for the specified, legitimate purpose for which it was collected. Access is rigorously restricted, limited only to staff who have followed specialized training. The Foundation maintains a detailed, mandatory record of all access to SPII.   

Prohibition on DLT Storage: Sensitive Personal Information is strictly prohibited from being stored directly on the DLT.

## 3.4. Data Minimization Strategy
In alignment with the principle of Data Minimization, the Protocol only collects PII that is adequate, relevant, and strictly limited to what is necessary to achieve the stated purposes. Any collection that goes beyond minimum necessity must be supported by explicit and voluntary consent.   

To enforce this, the Protocol incorporates technical mechanisms such as tokenization and ZKPs, which allow necessary verification and processing to occur without requiring the underlying, full PII to be exposed or transferred. This reduction in the volume of PII collected and retained is vital for minimizing both security exposure and the administrative burden of responding to subject access and erasure requests.   

# IV. Data Flows: On-Chain, Off-Chain, and Hybrid Architecture
## 4.1. The Necessity of the Hybrid Storage Model
The core solution for reconciling DLT immutability with regulatory requirements for data mutability and control is the mandatory Hybrid Storage Architecture. This model ensures that personal data is never immutably embedded in the ledger, adhering to the principle of Privacy-by-Design.   

Off-Chain Repository: This serves as the sole authorized, secure repository for mutable PII/SPII. It is stored on secure servers with robust security protocols, access controls, and encryption. The Foundation, acting as Controller, maintains centralized oversight of this repository.   

On-Chain DLT: The DLT ledger is strictly limited to storing irreversible cryptographic hashes and pseudonymous metadata references. These hashes are designed to be non-reconstructable back into the original PII. The design is engineered such that the cryptographic linkage must be incapable of revealing the PII, even if the off-chain data were later compromised.   

## 4.2. Pseudonymity and On-Chain Identifiers
Participants engaging in transactions are identified on the DLT network only by pseudonymous cryptographic addresses. This allows for public verifiability of transactions, a core feature of decentralized networks, while concealing the real-world identity of the user.   

It is essential to recognize that the Protocol operates pseudonymously, not anonymously. Pseudonymity implies that while the digital address (the alias) is visible, the real-world identity remains concealed unless external information can be utilized to penetrate the veil. In the Protocol’s hybrid environment, the sensitive linking mechanisms and keys needed to associate the pseudonymous address with the Off-Chain PII are held centrally by the Foundation and guarded under stringent security protocols.   

## 4.3. Mechanisms for De-Identification, Tokenization, and Encryption
The Protocol relies on advanced Technical and Organisational Measures (TOMs) to protect off-chain data:

Tokenization: PII is replaced with non-sensitive substitute identifiers (tokens) for transaction processing and internal operations, significantly reducing the exposure surface.   

Encryption: All sensitive data, both at rest in the off-chain repository and in transit during transfers, must be secured using robust, industry-standard encryption protocols.

Irreversible Hashes: The cryptographic hashes recorded on the DLT must be constructed using secure hashing algorithms and salting keys. These keys are managed separately, guaranteeing that if the off-chain PII is deleted, the on-chain hash cannot be reverse-engineered or used to reconstruct or verify identity, even in combination with other data. This compliance mechanism ensures the integrity of the ledger while adhering to data privacy standards.   

# V. Technical Compliance and Privacy-Enhancing Measures (TOMs)
## 5.1. Resolving DLT Immutability: The Right to Erasure (Article 17)
Blockchain’s core feature of immutability creates a fundamental conflict with the GDPR’s Right to Erasure (Article 17), which mandates the deletion of personal data upon request. Since physical removal of data from a distributed ledger is impossible, the Protocol utilizes a rigorous technical definition of erasure: Logical Deletion.   

Logical Deletion is executed through the following procedure upon receipt of a valid erasure request:

The corresponding PII/SPII is immediately and securely deleted (shredded) from the mutable Off-Chain Repository.

The cryptographic keys, salt, and linking mechanisms necessary to associate the individual’s identity with the on-chain pseudonymous address or hash are simultaneously and irreversibly destroyed.   

The result is that the on-chain data, though technically still present, is rendered cryptographically unidentifiable and functionally useless for linking back to the individual. By revoking all access rights and destroying the crucial linkage mechanism, the Foundation ensures that the data is treated as effectively "erased" and no longer qualifies as Personal Data.   

## 5.2. Implementing Zero-Knowledge Proofs (ZKP)
The Protocol incorporates Zero-Knowledge Proofs (ZKP) to achieve verifiable, confidential computation. ZKPs enable a party (the prover) to prove that a specific statement about data is true without revealing any information about the underlying data itself.   

Application: ZKPs are essential for sensitive InsurTech operations, allowing parties to verify policy terms, credit scores, claims eligibility, or specific DAO governance votes without revealing confidential data.   

Regulatory Balancing Act: The advanced privacy afforded by ZKPs must be proactively balanced against global obligations to mitigate illicit financial risk (AML/CTF). To prevent the Protocol from becoming an unregulated vehicle for money laundering, the Foundation implements a specific de-anonymization safeguard: A multi-key escrow mechanism is established, requiring a private key held by a neutral, trusted gatekeeper organization and a separate key held by designated government authorities. Both keys must be used together to de-anonymize transactions under strict legal requirements, such as a court order or warrant. This solution maintains user privacy by default while providing a necessary avenue for lawful oversight.   

## 5.3. Smart Contracts with Expiration Clauses
To automatically enforce the principle of Storage Limitation (data must not be kept longer than necessary) , the Protocol utilizes Smart Contracts with Expiration Clauses in its hybrid environment. These automated clauses are coded to correspond precisely with the mandatory InsurTech regulatory retention periods (Section IX). Upon expiration, the smart contract automatically triggers the formal logical deletion process, initiating the revocation of access rights and the deletion of the linking keys for the associated off-chain PII.   

# VI. Data Security, Integrity, and Confidentiality
## 6.1. Technical and Organizational Measures (TOMs)
The Foundation commits to deploying industry-leading Technical and Organizational Measures (TOMs) designed to ensure a security level appropriate to the high risk involved in processing SPII. These measures encompass:   

Access Control: Strict controls ensuring PII access is limited to the absolute minimum extent necessary, subject to confidentiality restrictions, and verified through identity checks prior to granting access.   

Storage and Transmission Security: Use of secure, hardened servers for off-chain data storage and mandatory strong encryption for data both at rest and in transit.

Process Security: Training employees on GDPR and security protocols, and enforcing formal data governance policies.   

## 6.2. Network and Information Security
The Protocol recognizes network and information security as a legitimate interest justifying the limited processing of non-PII operational data. Server log files are maintained to record access and provide an audit trail for security analysis.   

Given the open-source nature of the project, which increases transparency, the Foundation places a high priority on coordinated vulnerability disclosure (CVD) and rapid patching mechanisms to address potential security weaknesses that may be inadvertently exposed. Users are also reminded of their own obligation to protect personal security, including choosing robust passwords and guarding log-in credentials.   

## 6.3. Incident Response and Data Breach Notification Procedures
The Foundation maintains comprehensive incident response and data breach notification procedures. As the Data Controller, the Foundation assumes responsibility for notifying supervisory authorities and affected Data Subjects without undue delay in the event of a breach of PII or the compromise of linking cryptographic keys. Notification requirements are particularly stringent when sensitive categories of data, such as financial account numbers or government identifiers, are implicated.   

# VII. Open-Source Contributor and Telemetry Policy
## 7.1. Collection and Use of Contributor PII
To facilitate collaboration, code attribution, and compliance with open licenses (which may require source code availability and distribution rights) , the Protocol processes PII from its contributors, typically managed through platforms like GitHub.   

PII Collected: Identification and contact information, including name, email address, location, and GitHub profile details.   

Purpose: This data is collected strictly for code attribution, communication, security management, and regulatory compliance associated with software licensing.   

## 7.2. Telemetry Data Collection and Principles
If the Protocol software implements the collection of usage or performance data (Telemetry Data), it adheres to stringent transparency and minimization rules, ensuring that the open-source ethos of sharing documentation is balanced with the need for individual privacy.   

The collection of Telemetry Data must comply with three core principles:

Non-Identification: The data collected must be engineered so that it does not track or uniquely identify individual users.   

Awareness and Opt-In: Users and installers must be explicitly made aware of the Telemetry Data collection mechanism before it is enabled, often requiring an explicit opt-in procedure.   

Security: The data collection mechanism must not introduce any inadvertent security vulnerabilities into the software.   

Any collected Telemetry Data must be fully documented in the public documentation and, if shared with the project community, must be thoroughly anonymized or aggregated beforehand.   

## 7.3. PII Detection and Mitigation in Public Repositories
The open nature of collaborative development poses a risk of accidental exposure of PII in public forums (e.g., in commit messages, issues, or pull requests). The Protocol utilizes automated mitigation tools, such as GitHub actions, designed to detect and flag common PII elements (e.g., phone numbers, SSNs, IP addresses) submitted to the public repository. Strict operational procedures are maintained for the prompt review, redaction, and removal of any PII inadvertently disclosed in public communications.   

# VIII. Data Subject Rights and Exercise Procedures
## 8.1. Summary of Data Subject Rights
The Protocol guarantees global Data Subjects comprehensive rights over their PII:

Right of Access: The right to obtain confirmation that PII is being processed and to receive a copy of that PII.   

Right to Rectification: The right to request the correction of inaccurate or incomplete PII maintained in the Off-Chain Repository.   

Right to Erasure (Right to be Forgotten): The right to request the physical deletion of PII from the mutable repository and the subsequent Logical Deletion of the on-chain linkage, subject to exceptions based on legal retention requirements.   

Right to Restriction of Processing: The right to limit processing under certain circumstances.

Right to Data Portability: The right to receive PII in a structured, commonly used, and machine-readable format.   

Right to Object: The right to object to processing based on the Foundation’s legitimate interests.

Right to Withdraw Consent: The right to withdraw consent for processing based on that lawful basis at any time.   

## 8.2. Procedure for Submitting and Responding to Requests
All requests must be submitted through the Protocol’s designated, secure privacy portal. The Foundation requires rigorous verification of the individual’s identity prior to processing any request for access, portability, or deletion to prevent unauthorized disclosure.   

The response to erasure requests must comply with strict transparency rules. The Foundation will use clear, unambiguous language to explain the DLT hybrid model, confirming the secure deletion of the off-chain PII and explaining that the corresponding on-chain hash has been rendered non-identifiable through the destruction of linkage keys (Logical Deletion).   

## 8.3. Right to Complaint
Data Subjects retain the right to lodge a formal complaint regarding the Foundation's data processing practices with a relevant supervisory authority. For US Data Subjects, this explicitly includes the right to appeal the denial of a privacy request to the state’s Attorney General.   

# IX. Data Retention Schedule (InsurTech Compliance and Storage Limitation)
## 9.1. Principle of Storage Limitation and Review
The Storage Limitation principle mandates that PII may be retained only for as long as necessary for the specified processing purpose. Retention beyond this period is only permissible if justified by a clear legal obligation or, under specific circumstances, for archiving in the public interest.   

The Foundation maintains formal retention schedules and is obligated to review all retained PII regularly to ensure that the lawful basis for retention remains valid. If the basis expires, the deletion process must be immediately initiated.   

## 9.2. Specific InsurTech Regulatory Retention Requirements
The Protocol’s obligation to comply with global insurance and financial regulatory mandates dictates specific long-term retention requirements that constitute a Legal Obligation. These requirements supersede standard data minimization timelines for essential financial and contractual records. Insurers are required by state and international model laws (e.g., NAIC standards) to maintain books and records necessary for auditing regulatory compliance over extended periods.   

These retention mandates typically require data to be held for six to ten years for purposes such as auditability, fraud investigation, and legal defense of long-tail claims. The explicit reliance on the legal obligation grounds the retention policy in regulatory necessity.   

Table 3: InsurTech Protocol Data Retention Schedule

Category of Personal Data	Purpose of Processing	Lawful Basis	Minimum Regulatory Retention Period	Policy Action at Expiry
KYC/AML Identity Documents (Off-Chain)	Financial Crime Prevention & Regulatory Compliance	
Legal Obligation 

6 to 10 years (post-policy or post-relationship termination) 

Secure, irreversible deletion of off-chain documents/data.
Insurance Contract PII (Underwriting Data, Claims History) (Off-Chain)	Contractual Necessity & Claims Defense	
Legal Obligation / Contractual Necessity 

6 years (post-policy expiry or final claim settlement) 

Automated deletion, except when subject to a judicial legal hold.

Protocol Telemetry/Usage Logs (Anonymized PII)	Network Security and Optimization	
Legitimate Interest 

2 years (max retention for low-value operational data) 

Anonymization, aggregation, or deletion.
On-Chain Transaction Hashes/Metadata (Pseudonymous)	Immutable Audit Trail & DLT Integrity	Necessary for Protocol Function	
Perpetual (Immutable by design) 

PII linkage keys are destroyed upon expiration of related off-chain PII, rendering the hash anonymous/pseudonymous.

  
The perpetual existence of the transaction hash on the DLT is deemed compliant only because the PII linkage keys are deliberately and irrevocably destroyed upon the expiry of the associated off-chain PII. This action ensures that the on-chain record ceases to be legally defined as personal data.

# X. International Data Transfers and Regulatory Jurisdiction
## 10.1. Cross-Border Transfers
Due to the distributed and global nature of the Protocol, PII may be transferred internationally. Transfers of PII outside of jurisdictions deemed to provide adequate protection (e.g., the EEA) must be safeguarded by legally sanctioned mechanisms. The Foundation requires the implementation of legally approved instruments such as Standard Contractual Clauses (SCCs) or Binding Corporate Rules (BCRs) to guarantee that the data maintains continuous, high-level protection regardless of geographic location. The Foundation is responsible for ensuring that all data processors handling international transfers adhere to these safeguards.   

## 10.2. Jurisdiction and Supervisory Authority Designation
The Protocol Foundation designates its legal establishment and relevant supervisory authority, providing Data Subjects and international regulatory bodies with a clear point of jurisdictional contact for all data protection matters.

# XI. Openness and Review
## 11.1. Policy Accessibility and Plain Language
This Policy is immediately available on a public, easily accessible interface to ensure maximum transparency. The language used is designed to be clear and comprehensible to the average Data Subject, fulfilling the GDPR requirement for policies not to hide important information behind dense jargon.   

## 11.2. Policy Revisions
The Protocol Foundation retains the right to amend this Policy as necessary to adapt to technological evolution or changes in regulatory jurisprudence. Material changes will be communicated directly to Data Subjects and published prominently on the Protocol's public documentation interface.

# XII. Conclusion and Regulatory Compliance Blueprint
The InsurTech Operating Protocol’s privacy policy successfully navigates the complex regulatory environment unique to decentralized financial technology. The central commitment is to operate transparently within the boundaries defined by global data protection law, using technical controls to resolve fundamental conflicts inherent to DLT.

The core of this blueprint lies in the mandatory implementation of the Hybrid Storage Model and Logical Deletion. This strategy systematically addresses the Right to Erasure by defining "erasure" as the calculated, irreversible destruction of the cryptographic link between the immutable on-chain record and the mutable off-chain PII.   

Furthermore, regulatory mandates inherent to the InsurTech sector—particularly KYC, AML, and long-term retention for claims auditing—require the Foundation to formally assume the role of Data Controller. This centralization of legal accountability provides the crucial point of contact and liability required by financial regulators, ensuring that the decentralized structure does not compromise mandatory anti-crime and consumer protection functions.   

By automating data lifecycle management through smart contract expiration clauses based on specific 6-to-10-year regulatory retention periods, the Protocol transforms the legal burden of record-keeping into a demonstrably compliant and auditable technical process. Finally, the strategic adoption of Zero-Knowledge Proofs for privacy, coupled with the defined multi-key escrow system for regulatory access, establishes a governance model that is both privacy-enhancing and fully cooperating with necessary financial oversight. Adherence to this comprehensive policy is foundational for the Protocol’s lawful operation and global acceptance.   

