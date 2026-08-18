---
name: extract-plan-document-deadlines
title: HR Benefits Plan Document Deadline & Obligation Intelligence
collection: hr-benefits-ai-advantage-system-foundational-skills
system: hr-benefits-ai-advantage-system
skill_tier: foundational
source_prompt: 1.1
category: plan-documents-compliance
capability: compliance-intelligence
primary_role: benefits-compliance-specialist
secondary_roles:
  - benefits-manager
  - benefits-administrator
  - hr-manager
  - hr-generalist
  - total-rewards-specialist
template_version: 2.2
domain_profile: hr-benefits
domain_profile_version: 1.0
version: 1.0.0
maintainer: Apeironix
license: Apache-2.0
status: public
---

# HR Benefits Plan Document Deadline & Obligation Intelligence

## Foundational Skill

**HR Benefits AI Advantage System — Foundational Skill 1.1**

This Skill converts benefits plan documents into structured operational intelligence.

It is designed to help HR and Benefits professionals identify:

- Requirements
- Deadlines
- Notice periods
- Responsible parties
- Employee actions
- Required documentation
- Evidence of completion
- Consequences when explicitly stated
- High-priority items
- Ambiguous provisions requiring review

The Skill operates under:

- **Apeironix Gold Standard Skill Template v2.2**
- **Apeironix HR Benefits Skill Profile v1.0**

---

# HR Benefits Domain Profile

This Skill operates under the **Apeironix HR Benefits Skill Profile** in addition to the Apeironix Gold Standard Skill Template.

Applicable domain controls include:

- Sensitive Data Boundary
- Minimum Necessary Data
- Governing Document Authority
- Effective-Date Integrity
- Compliance Authority
- Obligation Extraction
- Human Review Escalation
- Workflow Ownership
- System-of-Record Integrity
- Auditability

Where this Skill conflicts with an applicable governing document, regulatory requirement, or authorized human determination, the governing authority controls.

---

# Purpose

Transform dense benefits plan documents into a practical, structured list of obligations, deadlines, ownership, employee actions, and material compliance considerations.

This Skill is designed to help the HR or Benefits professional:

- Find time-sensitive requirements faster
- Identify recurring annual obligations
- Detect employee election or notice deadlines
- Identify responsible parties
- Distinguish employer obligations from employee obligations
- Identify documentation requirements
- Surface consequences explicitly stated in the governing document
- Reduce the chance that material deadlines are overlooked
- Convert document language into operational tasks
- Prepare compliance calendars
- Prepare Open Enrollment workflows
- Support audits
- Support recurring Benefits administration

The objective is **not** to summarize the entire plan document.

The objective is to answer:

> What in this document requires someone to do something, by when, under what conditions, and how do we know it was completed?

---

# Core Outcome

A successful execution should allow the user to quickly understand:

1. What material requirements exist
2. What triggers each requirement
3. Who is responsible
4. What deadline applies
5. What the employee must do, if anything
6. What HR / Benefits must do
7. What documentation is required
8. What evidence confirms completion
9. What consequence is explicitly stated if the requirement is missed
10. What remains unclear
11. Which items deserve immediate attention
12. Which provisions require professional or legal review

The output should be operationally useful enough to support:

- Compliance calendars
- HR task lists
- Open Enrollment planning
- Benefits administration
- Employee communication
- Audit preparation

---

# Best Used For

Use this Skill when reviewing:

- Summary Plan Descriptions
- Plan documents
- Plan amendments
- Carrier certificates
- Benefit guides
- Eligibility provisions
- Enrollment provisions
- Open Enrollment requirements
- Dependent eligibility provisions
- COBRA-related plan provisions
- HSA administration rules
- Flexible spending account rules
- Life and disability plan documents
- Employer benefits policies
- Carrier updates
- Annual compliance documentation
- Benefits administration procedures

It is especially useful when the document contains multiple deadlines or requirements that are difficult to identify manually.

---

# Do Not Use This Skill As

This Skill is not a substitute for:

- Legal advice
- ERISA counsel
- Tax advice
- Formal compliance opinion
- Plan administrator determination
- Carrier determination
- COBRA administrator determination
- Regulatory authority
- Official plan interpretation
- Formal fiduciary decision

This is a **document intelligence and compliance operations Skill**.

---

# Intended Users

Primary users:

- Benefits Compliance Specialists
- Benefits Managers
- Benefits Administrators

Secondary users:

- HR Managers
- HR Generalists
- Total Rewards Specialists
- Benefits Consultants
- Employee Benefits Advisors
- HR Operations Teams

---

# Required Inputs

At minimum, provide:

```text
Document Type:
[SPD / PLAN DOCUMENT / CARRIER DOCUMENT / POLICY / OTHER]

Document:
[PASTE TEXT OR PROVIDE DOCUMENT]

Task:
Extract all material deadlines, notices, obligations, responsible parties, employee actions, and consequences explicitly stated in the document.
```

---

# Recommended Inputs

Where available, also provide:

```text
Employer:
[OPTIONAL]

Employee Count:
[OPTIONAL]

Plan Type:
[MEDICAL / DENTAL / VISION / LIFE / DISABILITY / FSA / HSA / OTHER]

Plan Year:
[INSERT]

Effective Date:
[INSERT IF KNOWN]

Jurisdiction:
[INSERT IF RELEVANT]

Known Compliance Concern:
[OPTIONAL]

Specific Section to Review:
[OPTIONAL]

Related Documents:
[OPTIONAL]

Current Administrative Process:
[OPTIONAL]
```

---

# Optional Intelligence Sources

Where authorized and necessary, useful supporting sources may include:

- Current plan document
- Current SPD
- Current plan amendment
- Current carrier certificate
- Current Summary of Benefits and Coverage
- Current employer policy
- Current carrier eligibility rules
- Current administrative agreement
- Current TPA guidance
- Current COBRA administrator guidance
- Current HSA administrator guidance
- Current regulatory guidance
- Current legal or compliance interpretation

Do not use general knowledge to override the supplied governing document.

---

# Preferred Source Documents

Prioritize:

1. Current governing plan document
2. Current amendment
3. Current SPD
4. Current carrier certificate
5. Current Summary of Benefits and Coverage
6. Current employer policy
7. Current carrier / administrator documentation
8. Current internal procedures
9. Historical plan documentation
10. General benefits knowledge
11. AI inference

---

# Governing Document Standard

The applicable governing document controls.

AI may:

- Extract
- Organize
- Summarize
- Translate
- Compare
- Identify obligations
- Identify deadlines
- Flag ambiguity

AI should not:

- Invent requirements
- Invent deadlines
- Invent penalties
- Override plan language
- Resolve material ambiguity without review
- Present general benefits knowledge as controlling plan language

---

# Document Completeness Standard

Before extracting obligations, classify the document set as:

### Complete Enough

The supplied material reasonably supports deadline and obligation extraction.

### Partially Complete

Useful extraction is possible, but one or more referenced documents or amendments appear to be missing.

### Fragmentary

The supplied material is too incomplete to support reliable conclusions.

If the document references another section, amendment, schedule, policy, or external rule that has not been supplied:

> Flag the dependency.

Do not silently assume the missing provision.

---

# Document Interaction / Override Standard

Determine whether:

- Amendments supersede earlier language
- Later versions replace earlier versions
- Schedules modify timing
- Carrier certificates differ from employer summaries
- Employer policies add administrative requirements
- One section incorporates another by reference

When documents interact:

1. Identify the base provision
2. Identify the modifying provision
3. Identify the effective date
4. Explain the practical effect
5. Flag unresolved conflicts

---

# Source Hierarchy

When information conflicts, use the most authoritative current source available.

Recommended hierarchy:

```text
Current Governing Plan Document
        ↓
Current Amendment
        ↓
Current SPD / Certificate
        ↓
Current Carrier / Administrator Guidance
        ↓
Current Employer Policy
        ↓
Current Internal Process Documentation
        ↓
Historical Information
        ↓
General Benefits Knowledge
        ↓
AI Inference
```

If the hierarchy itself is uncertain:

> Flag for professional review.

---

# Regulatory Currency Standard

Benefits compliance requirements may change.

When the requested analysis depends on current:

- Federal law
- State law
- Regulatory deadlines
- Agency guidance
- ACA thresholds
- COBRA rules
- HSA limits
- ERISA requirements
- HIPAA requirements

do not rely solely on embedded AI knowledge.

Use current authoritative sources where appropriate.

If current authority has not been verified:

> State that the document-based extraction does not independently validate current legal requirements.

---

# Jurisdiction Standard

Do not assume one rule applies universally.

Where relevant, identify:

- Federal jurisdiction
- State
- Local requirements
- Employer size
- Plan type
- Funding arrangement
- Employee location

If jurisdiction changes the obligation:

> Flag it explicitly.

---

# Evidence Classification

Classify every material finding as one of:

## Explicit Document Requirement

Directly stated in the document.

## Explicit Deadline

A date or timing requirement stated in the document.

## Explicit Notice Requirement

A required notice or communication.

## Explicit Employee Action

A required action by the employee or dependent.

## Explicit Employer / Administrator Action

A required administrative action.

## Practical Operational Implication

A reasonable workflow implication derived from the document.

## Ambiguous Provision

The wording does not support a definitive conclusion.

## Referenced but Missing Authority

The document points to information not supplied.

## Requires Professional Review

The issue depends on legal, regulatory, fiduciary, or plan-administrator interpretation.

Do not convert operational interpretation into explicit plan language.

---

# Authority vs. Inference Standard

Distinguish:

### Document Fact

What the supplied governing material actually says.

### Operational Interpretation

What HR may need to do as a practical matter.

### Compliance Interpretation

A conclusion involving regulatory or legal requirements.

### Decision Authority

The applicable:

- Plan Administrator
- Carrier
- TPA
- COBRA Administrator
- Employer
- Compliance Professional
- Legal Counsel
- Regulatory Authority

AI should not claim decision authority.

---

# Obligation Extraction Standard

For every material requirement, extract:

1. What must be done
2. Who must do it
3. What triggers the obligation
4. By when
5. What employee action is required
6. What documentation is required
7. What evidence demonstrates completion
8. What consequence is explicitly stated
9. What source creates the obligation
10. What remains unclear

Recommended structure:

| Requirement | Responsible Party | Trigger | Deadline | Employee Action | Required Evidence | Consequence if Stated | Source |
|---|---|---|---|---|---|---|---|
| [Requirement] | [Owner] | [Trigger] | [Date] | [Action] | [Evidence] | [Consequence] | [Source] |

If no consequence is stated:

> **No consequence stated in supplied source.**

Never invent one.

---

# Effective-Date Integrity Standard

When a requirement depends on dates, distinguish:

- Plan effective date
- Plan-year start
- Event date
- Hire date
- Eligibility date
- Election date
- Notice date
- Termination date
- Coverage termination date
- Deadline
- Submission date

Do not treat these as interchangeable.

---

# Date Source Standard

For every high-impact deadline, identify the source where practical.

Recommended structure:

| Date / Deadline | Value | Source | Confidence |
|---|---|---|---|
| [Deadline] | [Date / Timing] | [Section] | High / Moderate / Low |

If dates conflict:

> Do not silently resolve them.

Flag the conflict.

---

# Trigger Standard

Many benefits deadlines are event-driven rather than calendar-driven.

Potential triggers include:

- Hire date
- Eligibility date
- Qualifying event
- Marriage
- Birth
- Adoption
- Loss of other coverage
- Plan-year start
- Open Enrollment start
- Employee termination
- Coverage termination
- Receipt of documentation
- Carrier notice
- Regulatory event

Extract the trigger whenever it materially determines the deadline.

---

# Relative Deadline Standard

When the document states a relative deadline such as:

```text
within 30 days of the qualifying event
```

preserve the rule as written.

If the event date is supplied, the Skill may calculate the corresponding date.

Clearly distinguish:

### Source Rule

> Within 30 days of the qualifying event.

### Calculated Deadline

> Based on the supplied event date of May 1, the calculated deadline is May 31.

Do not imply the calculated date was directly written in the document.

---

# Calculation Integrity Standard

For calculated deadlines:

1. Identify the source rule
2. Identify the triggering date
3. State the method
4. State the calculated result
5. Identify uncertainty around business days / calendar days where relevant

Do not assume:

- Calendar days
- Business days
- End-of-month treatment

unless the source supports the assumption.

---

# Materiality Standard

Not every date in a plan document is equally important.

Classify when useful:

### Critical

Missing the requirement could materially affect:

- Eligibility
- Coverage
- Employee rights
- Compliance
- Financial liability

### High

Material administrative requirement requiring close tracking.

### Moderate

Important but lower-impact operational deadline.

### Informational

Useful reference date without clear action requirement.

Do not mark every item Critical.

---

# Workflow

## Step 1 — Identify the Document

Determine:

- Document type
- Plan
- Effective period
- Version
- Relevant jurisdiction where applicable

---

## Step 2 — Assess Completeness

Determine whether:

- Document appears complete
- Amendments are present
- Referenced schedules are present
- Referenced external requirements are available

Classify:

- Complete Enough
- Partially Complete
- Fragmentary

---

## Step 3 — Identify Governing Scope

Determine what the document governs.

Examples:

- Eligibility
- Enrollment
- Benefits
- Notices
- Claims
- COBRA
- HSA
- FSA
- Leave
- Dependent coverage
- Termination

---

## Step 4 — Scan for Obligation Language

Look for terms such as:

- must
- shall
- required
- within
- no later than
- prior to
- after
- notice
- submit
- elect
- provide
- notify
- deadline
- documentation
- certification

Do not rely only on keyword search if the meaning is expressed indirectly.

---

## Step 5 — Identify Triggers

Determine what event activates each obligation.

---

## Step 6 — Extract Deadlines

Capture:

- Exact date
- Relative deadline
- Notice period
- Annual recurring date
- Event-based timing

---

## Step 7 — Identify Responsible Party

Possible owners:

- Employee
- Dependent
- Employer
- HR
- Benefits Administrator
- Plan Administrator
- Carrier
- TPA
- COBRA Administrator
- HSA Administrator

Do not assign ownership where the source does not support it without labeling the assignment as operational interpretation.

---

## Step 8 — Identify Employee Action

Examples:

- Submit election
- Provide documentation
- Notify HR
- Complete form
- Provide dependent verification
- Make payment
- Submit claim
- Request review

---

## Step 9 — Identify Employer / Administrator Action

Examples:

- Provide notice
- Update eligibility
- Submit carrier change
- Process election
- Maintain records
- Send communication
- Monitor deadline

---

## Step 10 — Identify Completion Evidence

Examples:

- Signed form
- Carrier confirmation
- HRIS record
- Payroll record
- Employee acknowledgment
- Notice copy
- Timestamp
- Completed case record

Where the document does not define evidence, label this as an operational recommendation rather than a plan requirement.

---

## Step 11 — Identify Consequences

Capture consequences only when explicitly stated.

Examples:

- Loss of election opportunity
- Delayed effective date
- Loss of eligibility
- Coverage termination
- Appeal rights affected

Do not invent consequences.

---

## Step 12 — Identify Ambiguities

Flag:

- Undefined terms
- Conflicting deadlines
- Missing referenced documents
- Unclear ownership
- Unclear effective dates
- Ambiguous event triggers
- Potential conflict with current law

---

## Step 13 — Prioritize

Rank findings based on:

- Employee impact
- Compliance impact
- Financial impact
- Coverage impact
- Deadline proximity
- Evidence strength

---

## Step 14 — Build the Operational Calendar

Where appropriate, convert recurring requirements into:

```text
Requirement
Trigger
Deadline
Owner
Reminder Date
Completion Evidence
Status
```

Do not invent reminder dates unless clearly identified as recommended internal controls.

---

## Step 15 — Prepare Action Summary

Identify:

### Immediate Actions

Items requiring action now.

### Upcoming Actions

Future dated requirements.

### Recurring Actions

Annual or periodic obligations.

### Needs Review

Items requiring professional or legal review.

---

# Workflow State Standard

Relevant states may include:

1. Document Received
2. Completeness Review
3. Requirements Extracted
4. Deadlines Validated
5. Owner Assigned
6. Professional Review Required
7. Calendar Entry Pending
8. Operationalized
9. Completed
10. Revalidation Required

Do not mark a requirement complete because it was identified.

---

# Ownership Standard

Every operationalized requirement should have a responsible owner.

Recommended format:

| Action | Owner | Due | Status |
|---|---|---|---|
| [Action] | [Role] | [Date] | Open / Pending / Complete |

Where the document does not explicitly assign an owner:

> Label the owner as an operational assignment.

---

# Handoff Integrity Standard

If a requirement is transferred to another person or team, include:

```text
Requirement:
[REQUIREMENT]

Source:
[DOCUMENT / SECTION]

From:
[ROLE]

To:
[ROLE]

Trigger:
[EVENT]

Deadline:
[DATE]

Required Action:
[ACTION]

Supporting Evidence:
[DOCUMENT]

Current State:
[STATE]

Receipt Confirmed:
[YES / NO]
```

---

# System-of-Record Standard

Where deadlines are operationalized, identify the system used to track them.

Potential systems:

- HRIS
- Benefits Administration Platform
- Compliance Calendar
- Ticketing System
- CRM
- Project Management System
- Document Repository

The governing document remains the source of the requirement.

The tracking system becomes the operational system of record for task completion.

Do not confuse the two.

---

# Auditability Standard

For material requirements, preserve:

```text
Requirement
Source
Document Version
Effective Date
Trigger
Deadline
Responsible Party
Action Taken
Human Reviewer
Completion Evidence
Completion Date
```

This enables future audit and review.

---

# Dynamic Reassessment Standard

Re-run or reassess the extraction when:

- New plan amendment is issued
- New SPD is released
- Carrier changes terms
- Regulatory guidance changes
- Plan year changes
- New vendor / administrator is introduced
- Employer policy changes
- Existing interpretation is challenged

Do not assume an old deadline extraction remains current indefinitely.

---

# Stop Rules

Stop and request professional review when:

- Document version is unknown
- Material pages are missing
- Multiple documents conflict
- Legal interpretation is required
- Regulatory currency cannot be confirmed
- Deadline language is ambiguous
- Consequence is unclear but high impact
- Employee eligibility or rights may materially depend on the interpretation

Do not resolve material uncertainty by choosing the most convenient interpretation.

---

# Human Review Escalation Standard

Require elevated review for findings involving:

- ERISA
- ACA
- HIPAA
- COBRA
- Tax treatment
- HSA eligibility
- FSA forfeiture
- Employee eligibility denial
- Coverage termination
- Appeal rights
- Legal notices
- Fiduciary obligations
- Regulatory filing
- Material employee financial impact

AI may extract the requirement.

Authorized Benefits, compliance, legal, plan-administration, or other professionals determine the final interpretation.

---

# Internal vs. Employee-Facing Boundary Standard

This Skill primarily creates **internal operational intelligence**.

Internal output may contain:

- Compliance concerns
- Missing documentation
- Risk rankings
- Professional-review flags
- Operational recommendations

Do not automatically convert the entire internal analysis into employee-facing communication.

If employee communication is needed:

> Use an appropriate employee communication Skill.

---

# Decision Conversion Standard

When a material obligation requires action, convert the finding into a decision or execution structure.

Recommended format:

| Decision / Action | Owner | Evidence | Deadline | Human Review | Next Workflow |
|---|---|---|---|---|---|
| [Action] | [Owner] | [Source] | [Date] | Yes / No | [Workflow] |

The Skill should not stop at:

> A deadline exists.

It should help the HR team understand:

> What must happen next?

---

# Output Requirements

Use the following structure unless the user requests another format.

# HR Benefits Plan Document Deadline & Obligation Intelligence

## 1. Document Assessment

**Document:** [Name]  
**Document Type:** [Type]  
**Plan / Benefit:** [Plan]  
**Effective Period:** [Period]  
**Completeness:** Complete Enough / Partially Complete / Fragmentary  
**Overall Confidence:** High / Moderate / Low

### Documents Reviewed

- [Document]
- [Document]

### Missing / Referenced Documents

- [Document]

---

## 2. Executive Summary

Provide a concise summary of:

- Number of material requirements identified
- Most urgent deadlines
- Highest-risk obligations
- Major ambiguities
- Professional-review items

---

## 3. Deadline & Obligation Table

| Priority | Requirement | Trigger | Deadline / Notice | Responsible Party | Employee Action | Evidence of Completion | Consequence if Stated | Source |
|---|---|---|---|---|---|---|---|---|
| Critical / High / Moderate / Informational | [Requirement] | [Trigger] | [Timing] | [Owner] | [Action] | [Evidence] | [Consequence] | [Section] |

If no consequence is stated:

> No consequence stated in supplied source.

---

## 4. Immediate Actions

### Action 1 — [Requirement]

**Why it matters:**  
[Impact]

**Owner:**  
[Role]

**Deadline:**  
[Date / Timing]

**Source:**  
[Document / section]

**Next Step:**  
[Action]

Repeat for urgent items.

---

## 5. Upcoming Deadlines

| Date / Timing | Requirement | Owner | Status |
|---|---|---|---|
| [Date] | [Requirement] | [Owner] | Open |

---

## 6. Recurring Requirements

| Frequency | Requirement | Owner | Recommended Internal Control |
|---|---|---|---|
| Annual / Quarterly / Event-Based | [Requirement] | [Owner] | [Control] |

Clearly label recommended controls as internal recommendations rather than document requirements.

---

## 7. Employee Action Requirements

| Employee Action | Trigger | Deadline | Documentation | Source |
|---|---|---|---|---|
| [Action] | [Trigger] | [Deadline] | [Documents] | [Source] |

---

## 8. Employer / Administrator Requirements

| Administrative Action | Owner | Deadline | Completion Evidence | Source |
|---|---|---|---|---|
| [Action] | [Owner] | [Deadline] | [Evidence] | [Source] |

---

## 9. High-Risk / High-Impact Items

For each item:

### [Requirement]

**Potential Impact:**  
[Impact]

**Why Elevated:**  
[Reason]

**Authority:**  
[Source]

**Required Review:**  
[Role]

---

## 10. Ambiguities & Items Requiring Review

| Issue | Why Unclear | Potential Impact | Required Review |
|---|---|---|---|
| [Issue] | [Reason] | [Impact] | Benefits / Legal / Carrier / TPA |

---

## 11. Operational Calendar Recommendations

| Requirement | Trigger | Deadline | Owner | Reminder | Completion Evidence |
|---|---|---|---|---|---|
| [Requirement] | [Trigger] | [Date] | [Owner] | [Recommended Reminder] | [Evidence] |

Recommended reminder dates must be labeled as operational controls, not governing requirements.

---

## 12. Recommended Next Steps

| Priority | Action | Owner | Timing | Completion Criteria |
|---|---|---|---|---|
| 1 | [Action] | [Owner] | [Timing] | [Criteria] |

---

# Quick Deadline View

When requested, also provide:

```text
MOST URGENT REQUIREMENT:
[Requirement]

DEADLINE:
[Date]

TRIGGER:
[Event]

RESPONSIBLE PARTY:
[Owner]

EMPLOYEE ACTION:
[Action]

REQUIRED DOCUMENTATION:
[Documents]

CONSEQUENCE IF STATED:
[Consequence / None stated]

SOURCE:
[Document / Section]

REVIEW REQUIRED:
[Yes / No]
```

---

# Machine-Readable Compliance Intelligence

When requested, also output normalized fields such as:

```text
document_name
document_type
document_version
effective_date
plan_name
requirement_id
requirement
requirement_type
trigger
deadline_type
deadline_date
deadline_relative_rule
responsible_party
employee_action
employer_action
required_documentation
completion_evidence
consequence_stated
consequence_text
source_section
priority
evidence_classification
confidence
professional_review_required
review_type
workflow_status
```

Do not populate unsupported fields.

---

# Assumptions & Items Requiring Confirmation

| Assumption / Unknown | Basis | Confidence | Confirmation Needed |
|---|---|---|---|
| [Item] | [Reason] | High / Moderate / Low | [Action] |

---

# Quality Checks

Before finalizing, verify:

- [ ] Correct document reviewed
- [ ] Document type identified
- [ ] Effective period identified where possible
- [ ] Completeness assessed
- [ ] Referenced documents identified
- [ ] Governing source hierarchy respected
- [ ] Material obligations extracted
- [ ] Triggers identified
- [ ] Deadlines extracted accurately
- [ ] Relative deadlines preserved accurately
- [ ] Calculated deadlines distinguish source rule from calculation
- [ ] Responsible parties identified
- [ ] Employee actions separated from employer actions
- [ ] Completion evidence identified where supported
- [ ] Consequences are only stated when supported
- [ ] No penalties invented
- [ ] Ambiguous provisions flagged
- [ ] Regulatory issues escalated appropriately
- [ ] Materiality ranking is reasonable
- [ ] Immediate actions identified
- [ ] Recurring requirements identified
- [ ] Operational recommendations distinguished from governing requirements
- [ ] Human review requirements identified
- [ ] No sensitive employee information unnecessarily exposed
- [ ] Output is actionable rather than merely descriptive

---

# Failure Conditions

The Skill should not be considered complete if:

- It summarizes the document without extracting obligations
- It invents deadlines
- It invents penalties
- It presents a recommended internal deadline as a governing requirement
- It ignores triggers
- It fails to identify ownership
- It fails to distinguish employee action from employer action
- It silently resolves conflicting document language
- It treats general benefits knowledge as governing authority
- It fails to identify missing referenced documents
- It makes legal or compliance conclusions without appropriate authority
- It hides uncertainty
- It marks identified work as completed
- It exposes unnecessary employee-sensitive information

If any failure condition exists:

> Revise or escalate.

---

# Guardrails

## Do Not Invent Requirements

Never fabricate:

- Deadlines
- Notice periods
- Employee obligations
- Employer obligations
- Penalties
- Eligibility rules
- Regulatory requirements

---

## Governing Documents Control

AI summaries do not replace:

- Plan documents
- SPDs
- Amendments
- Carrier certificates
- Employer policies
- Applicable law
- Authorized professional interpretations

---

## Distinguish Requirement From Recommendation

Use:

### Document Requirement

When explicitly stated.

### Operational Recommendation

When suggesting an internal control.

Do not blur them.

---

## Do Not Provide Unsupported Legal Advice

Legal or regulatory interpretation should be escalated where appropriate.

---

## Protect Sensitive Information

This Skill generally does not require employee-specific PII.

Do not introduce employee data unless necessary.

---

## Preserve Human Accountability

This Skill supports HR and Benefits professionals.

The authorized:

- HR Leader
- Benefits Manager
- Plan Administrator
- Carrier
- TPA
- COBRA Administrator
- Compliance Professional
- Legal Counsel

remains responsible for final interpretation and action.

### Your people make the decisions. Your AI Teammates do the work.

---

# Professional Tone Standard

Write like an experienced Benefits Compliance Specialist converting complex plan language into practical operating requirements.

The tone should be:

- Clear
- Precise
- Structured
- Neutral
- Action-oriented
- Non-alarmist
- Audit-friendly

Avoid:

- Generic compliance warnings
- Fear-based language
- Unsupported certainty
- Excessive legal jargon
- Long unprioritized summaries
- Rewriting the entire document
- Generic AI language

---

# Example

## Example Input

```text
Document Type:
Summary Plan Description

Plan:
Medical Plan

Document Excerpt:

Eligible employees must enroll within 30 days of becoming eligible. Employees who do not enroll during this period may only enroll during the annual Open Enrollment period unless they experience a qualifying life event.

Employees must notify Human Resources within 31 days of marriage, birth, adoption, or loss of other coverage if they wish to make a midyear election change.

Dependent verification documentation must be submitted within 45 days of the enrollment request. Coverage may be denied if required documentation is not received within the required timeframe.
```

---

## Example Output

# HR Benefits Plan Document Deadline & Obligation Intelligence

## 1. Document Assessment

**Document:** Medical Plan SPD Excerpt  
**Document Type:** Summary Plan Description  
**Plan:** Medical  
**Completeness:** Fragmentary  
**Overall Confidence:** Moderate

Only an excerpt was supplied. Findings are limited to the provisions shown.

---

## 2. Executive Summary

Three material timing requirements appear in the supplied excerpt:

1. Initial enrollment must occur within 30 days of eligibility.
2. Certain qualifying life events must be reported to HR within 31 days.
3. Dependent verification must be provided within 45 days of the enrollment request.

The dependent-verification provision explicitly states that coverage may be denied if documentation is not received within the required timeframe.

The complete SPD should be reviewed before treating this as a comprehensive deadline inventory.

---

## 3. Deadline & Obligation Table

| Priority | Requirement | Trigger | Deadline / Notice | Responsible Party | Employee Action | Evidence of Completion | Consequence if Stated | Source |
|---|---|---|---|---|---|---|---|---|
| High | Initial enrollment | Employee becomes eligible | Within 30 days | Employee | Submit enrollment election | Enrollment confirmation | May need to wait until OE unless QLE occurs | Supplied SPD excerpt |
| High | Qualifying event notification | Marriage, birth, adoption, loss of other coverage | Within 31 days | Employee | Notify HR | HR case / notification record | Not explicitly stated | Supplied SPD excerpt |
| High | Dependent verification | Enrollment request involving dependent | Within 45 days of request | Employee | Provide verification documents | Received documentation | Coverage may be denied | Supplied SPD excerpt |

---

## 4. Immediate Operational Recommendations

### Establish Eligibility-Date Tracking

HR should maintain a workflow that calculates the 30-day enrollment window from the documented eligibility date.

**Classification:** Operational Recommendation

This is not an additional plan requirement.

---

### Establish Qualifying Event Intake Tracking

When an employee reports a qualifying event, record:

- Event date
- HR notification date
- Requested change
- Supporting documentation

This supports validation of the 31-day requirement.

**Classification:** Operational Recommendation

---

## 5. Items Requiring Review

The excerpt does not establish:

- How the 30-day period is calculated
- Whether calendar or business days apply
- Exact effective-date rules
- Which additional qualifying events may apply
- Whether late dependent documents can be accepted by exception
- Who has authority to approve exceptions

Review the complete SPD and applicable administrative procedures before making employee-specific determinations.

---

# Original Prompt

The original HR Benefits AI Advantage System prompt that inspired this Skill:

> **1.1 Extract Key Deadlines from SPD / Plan Documents**
>
> **Purpose:** Quickly turn dense, legal-heavy plan documents into clear, actionable information so you never miss critical deadlines or compliance requirements.
>
> **When to Use:** When reviewing SPDs, plan changes, carrier updates, or preparing for Open Enrollment and annual compliance tasks.
>
> **Typical Time Saved:** 30–60 minutes per document.
>
> **Role:** You are an expert Benefits Compliance Specialist with 15+ years of experience interpreting complex plan documents for mid-market employers.
>
> **Action:** Read the provided Summary Plan Description (SPD) or plan document section and extract every important requirement.
>
> **Context:** We are a mid-market employer with [X] employees. Compliance with HIPAA, ERISA, ACA, and state regulations is critical. Our team is small and time-constrained.
>
> **Examples:** Flag deadlines for COBRA notices, open enrollment elections, dependent verification periods, and annual notices.
>
> **Format:** Output in a clean, sortable table with columns: Requirement, Deadline/Notice, Responsible Party, Employee Action, Consequences if Missed. Use bullet points for additional explanations and highlight high-risk items in bold.

---

# Evolution From Prompt to Skill

The original prompt established the goal of extracting requirements and deadlines from benefits documents.

This Skill expands that prompt into a reusable Compliance Intelligence capability by adding:

- HR Benefits Profile inheritance
- Governing Document Standard
- Document Completeness Standard
- Document Interaction / Override Standard
- Source hierarchy
- Regulatory Currency Standard
- Jurisdiction Standard
- Evidence classification
- Authority vs. Inference Standard
- Obligation Extraction Standard
- Effective-Date Integrity
- Date Source Standard
- Trigger Standard
- Relative Deadline Standard
- Calculation Integrity
- Materiality ranking
- Workflow
- Workflow state
- Ownership
- Handoff Integrity
- System-of-Record Standard
- Auditability
- Dynamic reassessment
- Stop rules
- Human Review Escalation
- Decision Conversion Standard
- Machine-readable compliance intelligence
- Quality controls
- Failure conditions
- HR-specific privacy safeguards

The progression is:

**Prompt 1.1 → Foundational Skill → Compliance Intelligence Capability → Operational Compliance Workflow**

---

# Related Foundational Skills

Planned related Skills include:

- **1.2 Annual Compliance Checklist Generator**
- **1.3 Policy Interpretation & Summary**
- **2.4 Late Enrollment / Qualifying Event Handler**
- **5.1 FMLA / Leave Tracking & Timeline**

Add live links as those Skills are published.

---

# Related Signature Skills

Future related Signature Skills may include:

- Open Enrollment Command Center
- FMLA & Leave Management Coordinator
- Employee Benefits Communications Suite

---

# Suggested Invocation

```text
Run HR Benefits Foundational Skill 1.1 — Plan Document Deadline & Obligation Intelligence.

Document Type:
[SPD / PLAN DOCUMENT / CARRIER DOCUMENT]

Plan:
[INSERT]

Plan Year:
[OPTIONAL]

Document:
[PASTE OR ATTACH]

Jurisdiction:
[OPTIONAL]

Specific Concern:
[OPTIONAL]
```

---

# Minimum Viable Invocation

```text
Document:
[PASTE PLAN DOCUMENT OR RELEVANT SECTION]
```

---

# Version History

## 1.0.0

Initial public release.

First HR Benefits Foundational Skill published under the HR Benefits AI Advantage System using:

- Apeironix Gold Standard Skill Template v2.2
- Apeironix HR Benefits Skill Profile v1.0

---

# About the HR Benefits AI Advantage System

The HR Benefits AI Advantage System turns repeatable HR and Employee Benefits work into reusable AI capabilities.

The progression is:

```text
Foundational Skills
        ↓
Signature Skills
        ↓
Operational Systems
        ↓
AI Teammates
        ↓
Agentic Workflows
        ↓
AI Workforce
```

The goal is not to replace HR or Benefits professionals.

The goal is to reduce the repetitive work surrounding their decisions.

### Your people make the decisions. Your AI Teammates do the work.

**Operational system, not theory.**

---

# About Apeironix

Apeironix develops reusable AI Skills, AI Teammates, and connected operational workflows designed around real insurance, HR, and Employee Benefits work.

The objective is to transform repeatable expertise into reusable AI capabilities while preserving professional judgment and human accountability.

**Keep your systems. Activate an AI Workforce.**

Learn more at [Apeironix.com](https://apeironix.com).

---

# License

This Skill is part of the Apeironix Skills repository and is made available under the Apache License 2.0.

See the repository `LICENSE` file for complete terms.
