# SIEM, Security, and Audit Questions - Answer Key

## Multiple Choice Questions

### Q.N.1. Which feature is a characteristic of later SIEMs?
**Options:**
- Manage network information and alerts
- Manage network events and alerts
- Connect all security tools together into defined workflows
- Collect, normalize, and store log events and alerts

**Answer:** Connect all security tools together into defined workflows

**Explanation:** Later-generation SIEMs evolved beyond simple log collection and event management to provide security orchestration, automation, and response (SOAR) capabilities, connecting various security tools into integrated workflows.

---

### Q.N.2. Which feature provides SIEM greater visibility into the entire network?
**Options:**
- Analyzing logs and alerts from a single-pane-of-glass
- Complying with regulations
- Deciphering encrypted logs and alerts
- Sharing of logs by IoTs and BYODs

**Answer:** Analyzing logs and alerts from a single-pane-of-glass

**Explanation:** The single-pane-of-glass approach consolidates all security information in one unified view, providing comprehensive visibility across the entire network infrastructure.

---

### Q.N.3. Which three compliance regulations are legislative and industry-sponsored?
**Options:**
- Payment Industry Card (PIC) standard
- General Data Protection Regulation (GDPR)
- Health Portability Insurance and Accountability Act
- Payment Card Industry (PCI) standard
- Health Insurance Portability and Accountability Act (HIPAA)

**Answer:** 
- General Data Protection Regulation (GDPR)
- Payment Card Industry (PCI) standard
- Health Insurance Portability and Accountability Act (HIPAA)

**Explanation:** These three are the correct compliance regulations. Note: "Payment Industry Card (PIC)" is incorrect terminology - the proper name is PCI (Payment Card Industry).

---

### Q.N.4. Which problem was a barrier to the general acceptance of first-generation SIEM?
**Options:**
- The point solution approach to network security
- Cost to purchase was prohibitive
- High-level of skill was required
- Did not have the features needed by organizations

**Answer:** High-level of skill was required

**Explanation:** First-generation SIEM systems were complex and required significant expertise to configure, manage, and interpret results, which created a barrier to widespread adoption.

---

### Q.N.5. What is one method that SIEM uses to analyze data?
**Options:**
- Apply security controls
- Decipher encrypted logs and alerts
- Watch for known indicators of compromise (IoC)
- Decipher encrypted data flows

**Answer:** Watch for known indicators of compromise (IoC)

**Explanation:** SIEM systems monitor for known IoCs (patterns, signatures, behaviors) that indicate potential security breaches or malicious activity.

---

### Q.N.6. What is the primary objective of post-implementation review in SDLC?
**Options:**
- Authorize vendor's final payment from escrow
- Conduct remedial actions
- Determine that its organizational objectives have been fulfilled
- Recognition for forcing an installation to be successful

**Answer:** Determine that its organizational objectives have been fulfilled

**Explanation:** The post-implementation review assesses whether the implemented system meets the business objectives and requirements that justified the project.

---

### Q.N.7. What is the IS auditor's primary purpose in regard to life-cycle management?
**Options:**
- To verify that internal controls are tested prior to implementation by a third-party review laboratory
- To verify that all business contracts are properly signed and executed by management
- To verify that a sufficient budget was allocated to pay for software development within the allotted time period
- To verify that evidence supports the organizational objective and that each decision is properly authorized by management

**Answer:** To verify that evidence supports the organizational objective and that each decision is properly authorized by management

**Explanation:** IS auditors ensure proper governance, authorization, and alignment with organizational objectives throughout the system development lifecycle.

---

### Q.N.8. Which of the following design techniques will document internal logic functions used for data transformation?
**Options:**
- Entity-relationship diagram
- Flowchart
- Function point analysis
- Database schema

**Answer:** Flowchart

**Explanation:** Flowcharts visually represent the logical flow and transformation processes within a system, making them ideal for documenting internal logic functions.

---

### Q.N.9. Which of the following is used to add extra complexity before using a one-way data transformation algorithm?
**Options:**
- Data masking
- Key stretching
- Steganography
- Salting

**Answer:** Salting

**Explanation:** Salting adds random data to input before hashing to prevent rainbow table attacks and ensure identical inputs produce different outputs.

---

### Q.N.10. An administrator notices that several users are logging in from suspicious IP addresses. After speaking with the users, the administrator determines that the employees were not logging in from those IP addresses and resets the affected users' passwords. Which of the following should the administrator implement to prevent this type of attack from succeeding in the future?
**Options:**
- Permissions assignment
- Multifactor authentication
- Password complexity
- Access management

**Answer:** Multifactor authentication

**Explanation:** MFA provides an additional layer of security beyond passwords. Even if credentials are compromised, attackers cannot authenticate without the second factor.

---

### Q.N.11. A security analyst is reviewing the following logs: [10:00:00 AM] Login rejected - username administrator - password Spring2023 [10:00:01 AM] Login rejected - username jsmith - password Spring2023 [10:00:01 AM] Login rejected - username guest - password Spring2023 [10:00:02 AM] Login rejected - username cpolk - password Spring2023 [10:00:03 AM] Login rejected - username fmartin - password Spring2023. Which of the following attacks is most likely occurring?
**Options:**
- Pass-the-hash
- Account forgery
- Password spraying
- Brute-force

**Answer:** Password spraying

**Explanation:** Password spraying uses the same password (Spring2023) against multiple usernames, unlike brute-force which tries multiple passwords against one account.

---

### Q.N.12. During a security incident, the security operations team identified sustained network traffic from a malicious IP address: 10.1.4.9. A security analyst is creating an inbound firewall rule to block the IP address from accessing the organisation's network. Which of the following fulfils this request?
**Options:**
- access-list inbound permit ig source 0.0.0.0/0 destination 10.1.4.9/32
- access-list inbound permit ig source 10.1.4.9/32 destination 0.0.0.0/0
- access-list inbound deny ig source 10.1.4.9/32 destination 0.0.0.0/0
- access-list inbound deny ig source 0.0.0.0/0 destination 10.1.4.9/32

**Answer:** access-list inbound deny ig source 10.1.4.9/32 destination 0.0.0.0/0

**Explanation:** This rule denies inbound traffic from the malicious source IP (10.1.4.9/32) to any destination (0.0.0.0/0) on the network.

---

### Q.N.13. A cyber operations team informs a security analyst about a new tactic malicious actors are using to compromise networks. SIEM alerts have not yet been configured. Which of the following best describes what the security analyst should do to identify this behavior?
**Options:**
- Threat hunting
- Digital forensics
- E-discovery
- Incident response

**Answer:** Threat hunting

**Explanation:** Threat hunting is the proactive search for threats before they trigger automated alerts, ideal for identifying new tactics not yet configured in SIEM.

---

### Q.N.14. Which of the following is the most likely to be used to document risks, responsible parties, and thresholds?
**Options:**
- Risk analysis
- Risk register
- Risk tolerance
- Risk transfer

**Answer:** Risk register

**Explanation:** A risk register is a comprehensive document that catalogs identified risks, their owners, severity levels, mitigation strategies, and risk thresholds.

---

### Q.N.15. A company is developing a business continuity strategy and needs to determine how many staff members would be required to sustain the business in the case of a disruption. Which of the following best describes this step?
**Options:**
- Capacity planning
- Tablet exercise
- Redundancy
- Geographic dispersion

**Answer:** Capacity planning

**Explanation:** Capacity planning determines the resources (including personnel) needed to maintain business operations during disruptions.

---

### Q.N.16. Which of the following factors are the most important to address when formulating a training curriculum plan for a security awareness program? (Select two)
**Options:**
- The reporting mechanisms for ethics violations
- Cadence and duration of training events
- Channels by which the organization communicates with customers
- Threat vectors based on the industry in which the organization operates

**Answer:**
- Cadence and duration of training events
- Threat vectors based on the industry in which the organization operates

**Explanation:** Training frequency/duration and industry-specific threats ensure relevant, effective security awareness programs.

---

### Q.N.17. A systems administrator is working on a solution with the following requirements: Provide a secure zone. Enforce a company-wide access control policy. Reduce the scope of threats. Which of the following is the systems administrator setting up?
**Options:**
- CIA
- Zero Trust
- Non-repudiation
- IAAA

**Answer:** Zero Trust

**Explanation:** Zero Trust architecture creates secure zones, enforces strict access controls, and minimizes attack surface by assuming no implicit trust.

---

### Q.N.18. Which of these choices is the best answer regarding who is primarily responsible for providing internal controls to detect, correct, and prevent irregularities or illegal acts?
**Options:**
- Board of directors
- Human resources
- Legal, aka general counsel
- Information technology

**Answer:** Board of directors

**Explanation:** The board of directors has ultimate oversight responsibility for establishing and maintaining an effective internal control environment.

---

### Q.N.19. Which of the following functions should be separated from the others if segregation of duties cannot be achieved in an automated system?
**Options:**
- Origination
- Reprocessing
- Transaction logging
- Authorization

**Answer:** Authorization

**Explanation:** Authorization should be separated to prevent individuals from approving their own transactions, which is a critical control point.

---

### Q.N.20. Segregation or separation of duties may not be practical in a small environment. A single employee may be performing the combined functions of server operator and application programmer. The IS auditor should recommend controls for which of the following?
**Options:**
- Automated controls to prevent the operator logon ID from making program modifications
- Hiring additional technical staff to force segregation of duties
- Automated logging of changes made to development libraries
- Procedures that verify that only approved program changes are implemented

**Answer:** Procedures that verify that only approved program changes are implemented

**Explanation:** When segregation isn't possible, compensating controls like change verification procedures help ensure accountability and prevent unauthorized modifications.

---

### Q.N.21. Who should issue the organisational policies?
**Options:**
- The policy should be signed and enforced by any level of management.
- The auditor should issue the policies in accordance with standards, and they should be authorized by the highest level of management to ensure compliance.
- The policy should be signed and enforced by the highest level of management.
- Policies should originate from the bottom and move up to the department manager for approval.

**Answer:** The policy should be signed and enforced by the highest level of management.

**Explanation:** Policies must have executive-level authority to ensure organization-wide compliance and demonstrate commitment from top leadership.

---

### Q.N.22. How should the auditor assist in the remediation of problems found during the audit?
**Options:**
- The auditor should take ownership of the issue and participate in designing the plan for fixing the problem. The auditor should help the auditees.
- The auditor can add value by defining the specific steps necessary for remediation of the problem.
- The auditor should decide whether the problem is major or minor and then advise the auditee with a specific solution after considering the impact to the business.
- The auditor should never take ownership of problems found. Auditors are encouraged to provide general advice to the auditee, including an explanation of what to look for during the audit.

**Answer:** The auditor should never take ownership of problems found. Auditors are encouraged to provide general advice to the auditee, including an explanation of what to look for during the audit.

**Explanation:** Auditors must maintain independence and objectivity. Taking ownership of remediation compromises their ability to audit those controls in the future.

---

## Long Answer Questions

### Q.N.23. As a newly appointed Information Systems (IS) auditor in a medium-sized enterprise conducting a full-scope systems audit, explain how the foundational elements of the audit process contribute to a successful audit engagement. (13 marks)

**Eight Key Points:**

• **Audit Charter - Authority:** Establishes formal authority for IS auditor to access systems, data, personnel and conduct independent assessments without management interference

• **Audit Charter - Independence & Accountability:** Defines reporting lines to board/audit committee, ensures objectivity, and sets professional standards for audit quality and confidentiality

• **Compliance Testing:** Tests whether controls operate as designed per policies/regulations; uses evidence like policy documents, system configs, and approval records to verify adherence

• **Substantive Testing:** Examines actual data/transactions to detect errors or fraud regardless of controls; uses transaction logs, database queries, and reconciliations to validate accuracy and completeness

• **Risk Assessment in Pre-Planning:** Identifies and prioritizes threats (security vulnerabilities, compliance gaps, fraud) based on likelihood and impact to focus audit resources on high-risk areas

• **Materiality Determination:** Establishes significance thresholds (financial impact, user count, regulatory violations) that influence audit scope and sampling size decisions

• **Risk-Based Scope & Sampling:** Allocates audit resources proportionally - high-risk areas receive comprehensive testing while low-risk areas use analytical review or reduced sampling

• **Evaluation with Context:** Interprets findings using risk/materiality framework - same control weakness is major in critical systems but informational in low-risk areas, ensuring meaningful actionable insights

---

### Q.N.24. How does the COBIT framework support auditability in organizational security processes and information systems? Discuss the key governance and management objectives, control practices, and implementation steps required to ensure effective and continuous auditability. (8 Marks)

**Eight Key Points:**

• **Governance - Stakeholder Value:** Establishes clear accountability structures aligning IT security with enterprise objectives, creating transparency in decision-making and ensuring security processes have built-in auditability from design

• **Management - Risk Optimization (EDM03):** Requires documented risk registers, assessment methodologies, and treatment plans creating audit trails showing how risks were identified, assessed, mitigated, and monitored over time

• **Control Practice - Security Services (DSS05):** Establishes monitoring, detection, and response processes with security logs, SIEM systems, and incident documentation providing time-stamped, tamper-evident records of security events

• **Control Practice - Configuration Management (BAI10):** Maintains CMDBs and change control with complete documentation of who, when, why, and what approvals, enabling verification that security controls remain effective

• **Implementation - Monitoring Mechanisms (MEA01):** Deploys automated monitoring tools, KPIs, and KRIs for continuous evidence collection, creating real-time audit trails without disrupting operations

• **Implementation - Policy Documentation (APO01):** Maintains version-controlled policy repositories showing evolution of security requirements, providing baselines for compliance testing and traceability to governance decisions

• **Implementation - Access Controls (DSS05/APO13):** Implements RBAC, privileged access management, and segregation of duties with detailed access records, approval workflows, and periodic reviews preventing conflicts of interest

• **Continuous Improvement - Maturity Model:** Conducts regular self-assessments using capability maturity levels (0-5) to document gaps and improvement initiatives, creating audit trail of progression toward higher process maturity

---

## End of Answer Key

**Note:** This document provides comprehensive answers to all 24 questions covering SIEM, security, compliance, and IS audit topics. All MCQ options are included for reference. Questions 23 and 24 are formatted with 8 concise bullet points as requested.