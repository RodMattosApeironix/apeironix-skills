---
name: annual-benefits-compliance-checklist
title: HR Benefits Annual Compliance Checklist Intelligence
collection: hr-benefits-ai-advantage-system-foundational-skills
system: hr-benefits-ai-advantage-system
skill_tier: foundational
source_prompt: 1.2
category: plan-documents-compliance
capability: compliance-intelligence
primary_role: hr-compliance-officer
secondary_roles:
  - benefits-manager
  - benefits-administrator
  - hr-manager
  - hr-generalist
  - total-rewards-leader
  - benefits-compliance-specialist
template_version: 2.2
domain_profile: hr-benefits
domain_profile_version: 1.0
version: 1.0.0
maintainer: Apeironix
license: Apache-2.0
status: public
---

# HR Benefits Annual Compliance Checklist Intelligence

## Foundational Skill

**HR Benefits AI Advantage System — Foundational Skill 1.2**

This Skill converts benefits compliance requirements, plan information, employer context, and known deadlines into a practical, prioritized compliance operating checklist.

It is designed to help HR and Benefits teams manage recurring work involving:

- Open Enrollment
- Annual notices
- ACA reporting
- COBRA administration
- ERISA-related benefits administration
- HIPAA-related benefits workflows
- Dependent eligibility
- Plan-document maintenance
- Carrier requirements
- Employee communications
- Reporting
- Audits
- Year-end requirements

The Skill operates under:

- **Apeironix Gold Standard Skill Template v2.2**
- **Apeironix HR Benefits Skill Profile v1.0**

---

# HR Benefits Domain Profile

This Skill operates under the **Apeironix HR Benefits Skill Profile** in addition to the Apeironix Gold Standard Skill Template.

Applicable domain controls include:

- Governing Document Authority
- Regulatory Currency
- Jurisdiction
- Effective-Date Integrity
- Obligation Extraction
- Workflow Ownership
- Handoff Integrity
- Completion Evidence
- Human Review Escalation
- Auditability
- Sensitive Data Boundary

Where this Skill conflicts with an applicable governing document, regulation, authorized professional determination, or current legal authority, the governing authority controls.

---

# Purpose

Create a practical, prioritized compliance checklist tailored to an employer's Benefits program, timing, jurisdiction, and requested compliance topic or period.

This Skill is designed to help the HR or Benefits professional:

- Identify required Benefits compliance activities
- Organize work by phase
- Assign ownership
- Identify deadlines
- Identify required notices and forms
- Identify required documentation
- Track workflow status
- Distinguish confirmed requirements from items requiring validation
- Prepare for Open Enrollment
- Prepare for year-end
- Prepare for regulatory reporting
- Prepare for audits
- Prevent recurring administrative requirements from falling through the cracks
- Create an auditable compliance workflow

The objective is not simply to produce a long compliance list.

The objective is to answer:

> What must be done, when, by whom, using what authority, with what evidence, and what still requires confirmation?

---

# Core Outcome

A successful execution should allow the HR or Benefits team to quickly understand:

1. What compliance tasks apply
2. Why each task applies
3. What triggers the requirement
4. When the task is due
5. Who owns the task
6. What documentation is required
7. What notices or forms are involved
8. What evidence proves completion
9. What workflow phase the task belongs to
10. Which items are critical
11. What information is missing
12. What requires legal, compliance, carrier, or administrator review

The output should be usable as an actual working checklist rather than only as an informational reference.

---

# Best Used For

Use this Skill:

- At the start of a plan year
- At the start of a quarter
- Before Open Enrollment
- During annual Benefits planning
- Before year-end
- During ACA reporting preparation
- During COBRA process review
- During dependent eligibility review
- During plan-document review
- During carrier-transition planning
- During audits
- When building a new Benefits compliance calendar
- When onboarding a new Benefits administrator
- When reviewing whether recurring compliance work is consistently completed

---

# Do Not Use This Skill As

This Skill is not a substitute for:

- Legal advice
- ERISA counsel
- Tax advice
- Formal compliance opinion
- Regulatory authority
- Plan Administrator determination
- Carrier determination
- COBRA Administrator determination
- TPA authority
- Government filing confirmation

This is a **Benefits compliance workflow and decision-support Skill**.

---

# Intended Users

Primary users:

- HR Compliance Officers
- Benefits Compliance Specialists
- Benefits Managers

Secondary users:

- Benefits Administrators
- HR Managers
- HR Generalists
- Total Rewards Leaders
- Benefits Consultants
- Employee Benefits Advisors
- HR Operations Teams

---

# Required Inputs

At minimum, provide:

```text
Checklist Topic or Period:
[ANNUAL / QUARTERLY / OPEN ENROLLMENT / ACA / COBRA / AUDIT / OTHER]

Employer Size:
[NUMBER OF EMPLOYEES OR RANGE]

Jurisdiction:
[STATE / STATES]

Benefits Programs:
[MEDICAL / DENTAL / VISION / LIFE / DISABILITY / HSA / FSA / OTHER]

Known Plan Year:
[INSERT IF KNOWN]
```

---

# Recommended Inputs

Where available, also provide:

```text
Employer Name:
[OPTIONAL]

Employee Count:
[INSERT]

Full-Time Employee Count:
[OPTIONAL]

Applicable Large Employer Status:
[IF KNOWN]

States of Operation:
[INSERT]

Employee Work Locations:
[OPTIONAL]

Plan Year:
[INSERT]

Renewal Date:
[INSERT]

Funding Arrangement:
[FULLY INSURED / SELF-FUNDED / LEVEL-FUNDED / OTHER]

ERISA Plan:
[YES / NO / UNKNOWN]

Medical Plan:
[INSERT]

Dental Plan:
[INSERT]

Vision Plan:
[INSERT]

Life / Disability:
[INSERT]

HSA:
[YES / NO]

FSA:
[YES / NO]

COBRA Administrator:
[INSERT]

TPA:
[INSERT]

Benefits Administration Platform:
[INSERT]

Payroll System:
[INSERT]

Known Compliance Calendar:
[OPTIONAL]

Known Deadlines:
[OPTIONAL]

Recent Plan Changes:
[OPTIONAL]

Open Enrollment Dates:
[OPTIONAL]

Known Audit or Filing:
[OPTIONAL]

Supporting Documents:
[OPTIONAL]
```

---

# Optional Intelligence Sources

Where authorized and necessary, useful supporting sources may include:

- Current plan documents
- Current SPD
- Plan amendments
- Carrier certificates
- Summary of Benefits and Coverage
- Employer policies
- Current compliance calendar
- Prior-year compliance checklist
- Carrier administration guides
- COBRA administrator guidance
- TPA guidance
- HSA / FSA administrator guidance
- Payroll records
- Benefits administration records
- Current government guidance
- Current regulatory resources
- Authorized legal or compliance guidance

Compliance-sensitive requirements should be validated using current authoritative sources where appropriate.

---

# Governing Authority Standard

Do not treat general AI knowledge as the controlling authority for compliance requirements.

Potential governing sources include:

1. Federal law
2. State law
3. Current regulatory guidance
4. Current plan document
5. Current SPD
6. Current plan amendment
7. Current employer policy
8. Current carrier or administrator documentation
9. Current legal or compliance guidance
10. Internal operating procedure

Where these conflict:

> Flag the conflict and escalate as appropriate.

---

# Regulatory Currency Standard

Benefits compliance requirements can change.

Before treating any time-sensitive regulatory requirement as current, consider whether the requirement depends on:

- Current calendar year
- Employer size
- State
- Funding arrangement
- Plan type
- Current regulatory threshold
- Filing method
- Employee population
- Regulatory agency guidance

For current compliance matters:

> Use current authoritative sources where available.

Do not present old embedded AI knowledge as current regulatory fact.

---

# Jurisdiction Standard

Compliance may depend on:

- Federal law
- State
- Local jurisdiction
- Employer location
- Employee work location
- Employer size
- Plan funding arrangement
- Plan type

The Skill should identify jurisdictional uncertainty rather than assume one universal rule.

---

# Applicability Standard

Every compliance item should be evaluated for applicability.

Classify:

### Confirmed Applicable

Available information clearly supports applicability.

### Likely Applicable

The requirement appears applicable but one or more facts should be confirmed.

### Conditional

Applies only if a specified condition is true.

### Not Applicable

Available information supports that the requirement does not apply.

### Unable to Determine

Insufficient information exists.

Do not put every possible Benefits compliance requirement onto the employer's checklist.

---

# Applicability Driver Standard

Potential drivers include:

- Number of employees
- Full-time employee count
- Applicable Large Employer status
- Plan type
- Funding arrangement
- State
- Employee location
- ERISA status
- COBRA applicability
- HSA / FSA offering
- Plan-year timing
- Open Enrollment timing
- Carrier arrangement

For conditional requirements, state the condition.

Example:

> Applies if the employer meets the applicable employer-size threshold.

Do not silently assume the threshold has been met.

---

# Evidence Classification

Classify material checklist items as:

## Confirmed Regulatory Requirement

Supported by current authoritative regulation or guidance.

## Confirmed Plan Requirement

Supported by governing plan documentation.

## Confirmed Administrative Requirement

Supported by carrier, TPA, administrator, or employer process documentation.

## Conditional Requirement

Applies only if identified conditions are met.

## Operational Best Practice

Recommended internal control rather than externally mandated requirement.

## Requires Current Authority Validation

May apply, but current authoritative confirmation is needed.

## Requires Professional Review

Depends on legal, tax, fiduciary, or compliance interpretation.

Never present a best practice as a legal requirement.

---

# Requirement vs. Best Practice Standard

This distinction is mandatory.

### Requirement

Something the employer must do under applicable authority.

### Administrative Requirement

Something required by the plan, carrier, TPA, administrator, or internal governance.

### Recommended Control

Something the HR team should consider doing to improve reliability.

Example:

**Requirement:**

> Distribute a required notice within the applicable timeframe.

**Recommended Control:**

> Schedule an internal reminder 30 days before the distribution deadline.

The reminder is not the governing deadline.

---

# Obligation Extraction Standard

For every material compliance task, identify:

1. Task
2. Governing authority
3. Applicability
4. Trigger
5. Deadline
6. Owner
7. Required notice or form
8. Required documentation
9. Evidence of completion
10. Consequence if explicitly supported
11. Human review requirement
12. Workflow status

Recommended structure:

| Task | Authority | Applicability | Trigger | Deadline | Owner | Required Documentation | Evidence of Completion |
|---|---|---|---|---|---|---|---|

---

# Effective-Date Integrity Standard

Compliance workflows may depend on:

- Plan-year start
- Renewal date
- Open Enrollment date
- Employee effective date
- Regulatory filing period
- Qualifying event date
- Distribution date
- Termination date

Do not use one date as a substitute for another.

---

# Deadline Integrity Standard

For every material deadline:

- Identify the governing rule
- Identify whether the deadline is fixed or relative
- Identify the trigger
- Identify whether the date is calculated
- Identify unresolved business-day vs. calendar-day questions

Do not invent dates.

---

# Recurring Requirement Standard

Classify recurring requirements as:

### Annual

Occurs once per year.

### Quarterly

Occurs quarterly.

### Monthly

Occurs monthly.

### Pay-Period

Occurs every payroll cycle.

### Event-Based

Triggered by employee or plan activity.

### Ongoing

Requires continuous administration.

### One-Time

Triggered by a specific implementation or change.

This classification helps convert compliance into an operational calendar.

---

# Materiality / Priority Standard

Prioritize checklist items using:

### Critical

Failure could create significant employee, regulatory, financial, coverage, or fiduciary impact.

### High

Important compliance or administrative obligation requiring disciplined execution.

### Moderate

Material but lower-risk recurring obligation.

### Informational

Useful planning or administrative reference.

Do not make the entire checklist Critical.

---

# Compliance Phase Standard

Organize the checklist into:

## Preparation

Work required before the compliance event or period.

## Execution

Actions that must occur during the active period.

## Follow-Up

Actions required after initial execution.

## Review

Validation, audit, reconciliation, and documentation.

This structure comes directly from the original Prompt 1.2 design. :contentReference[oaicite:1]{index=1}

---

# Workflow

## Step 1 — Define the Compliance Scope

Determine:

- Topic
- Time period
- Plans involved
- Employer size
- Jurisdiction
- Funding arrangement

Avoid creating an unrestricted checklist for every possible Benefits law.

---

## Step 2 — Validate Employer Context

Confirm where available:

- Employee count
- Applicable employer status
- State
- Plan type
- Plan year
- Funding arrangement
- COBRA arrangement
- HSA / FSA status

Flag missing applicability inputs.

---

## Step 3 — Identify Governing Authorities

Determine which requirements may arise from:

- Federal authority
- State authority
- Plan document
- Carrier
- TPA
- Employer policy
- Administrator agreement

---

## Step 4 — Identify Applicable Requirements

For each potential requirement, determine:

- Confirmed Applicable
- Likely Applicable
- Conditional
- Not Applicable
- Unable to Determine

Exclude irrelevant requirements from the active checklist where supportable.

---

## Step 5 — Identify Triggers

Possible triggers include:

- Start of plan year
- Open Enrollment
- Employee hire
- Employee termination
- Qualifying event
- Regulatory reporting period
- Carrier renewal
- Plan amendment
- Employer-size threshold
- Audit
- Calendar-year requirement

---

## Step 6 — Identify Deadlines

Capture:

- Exact date
- Relative timeframe
- Recurring schedule
- Event-based deadline
- Submission window

Separate source deadline from internally recommended reminder dates.

---

## Step 7 — Identify Required Notices and Forms

Examples may include:

- Employee notices
- Government forms
- Carrier forms
- Enrollment forms
- COBRA documents
- Plan amendments
- Required disclosures

Only include requirements supported by applicable authority.

---

## Step 8 — Assign Ownership

Potential owners include:

- HR Manager
- Benefits Manager
- Benefits Administrator
- Payroll
- Carrier
- TPA
- COBRA Administrator
- HSA Administrator
- Broker / Advisor
- Legal Counsel

Where ownership is internally assigned rather than legally prescribed:

> Label it as an operational assignment.

---

## Step 9 — Identify Documentation Requirements

For each task, identify:

- Required notice
- Filing
- employee record
- carrier confirmation
- administrator confirmation
- plan document
- payroll record
- acknowledgment
- supporting form

---

## Step 10 — Define Completion Evidence

A task should not be considered complete simply because someone intended to perform it.

Examples:

- Filing confirmation
- Carrier acknowledgment
- employee distribution record
- system timestamp
- signed document
- completed form
- case closure
- archived notice

---

## Step 11 — Organize by Phase

Sort the checklist into:

1. Preparation
2. Execution
3. Follow-Up
4. Review

---

## Step 12 — Prioritize

Rank each item:

- Critical
- High
- Moderate
- Informational

---

## Step 13 — Identify Dependencies

Examples:

- Employee census
- Carrier data
- payroll data
- vendor confirmation
- legal interpretation
- final plan design
- carrier renewal terms
- Open Enrollment dates

---

## Step 14 — Define Internal Reminder Controls

Where helpful, recommend internal reminder dates.

Example:

> Recommended internal reminder: 30 days before governing deadline.

Label these clearly as:

**Operational Control — Not Governing Deadline**

---

## Step 15 — Identify Review Items

Flag tasks requiring:

- Legal review
- Compliance review
- Broker / advisor review
- Carrier confirmation
- TPA confirmation
- Plan Administrator decision

---

## Step 16 — Build the Checklist

Create an actionable table with:

- Task
- Priority
- Phase
- Timeline
- Owner
- Documentation
- Status
- Evidence

---

## Step 17 — Build the Compliance Calendar

Where exact timing is available, create a calendar view.

---

## Step 18 — Build the Exception List

Identify items where:

- Applicability is unclear
- Deadline is unclear
- authority is missing
- ownership is unclear
- document is unavailable
- current regulation requires validation

---

# Workflow State Standard

Relevant workflow states include:

1. Identified
2. Applicability Review
3. Confirmed Applicable
4. Scheduled
5. In Preparation
6. Pending Information
7. Pending Professional Review
8. Ready
9. Submitted / Distributed
10. Confirmation Pending
11. Completed
12. Revalidation Required
13. Escalated

Do not mark a requirement Completed because it was added to the checklist.

---

# Ownership Standard

Every active task should have an owner.

Recommended structure:

| Task | Primary Owner | Supporting Party | Due | Status |
|---|---|---|---|---|

Avoid shared ownership without a primary accountable role.

---

# Dependency Standard

For material dependencies, identify:

```text
Dependency:
[ITEM]

Controlled By:
[ROLE / PARTY]

Needed For:
[TASK]

Required By:
[DATE]

Can Work Continue Without It:
[YES / NO]

Escalation:
[ACTION]
```

---

# Handoff Integrity Standard

For compliance work moving between parties:

```text
Task:
[TASK]

From:
[ROLE]

To:
[ROLE]

Current State:
[STATE]

Deadline:
[DATE]

Required Documents:
[LIST]

Requested Action:
[ACTION]

Receipt Confirmed:
[YES / NO]
```

A handoff is not complete merely because an email was sent.

---

# System-of-Record Standard

Potential systems include:

- Compliance calendar
- HRIS
- Benefits administration system
- Payroll
- COBRA platform
- TPA portal
- carrier portal
- document repository
- project management system

For each task, determine:

- Where the requirement is tracked
- Where completion evidence is stored
- What system contains the authoritative employee or plan data

---

# Completion Criteria Standard

A checklist item is complete only when the applicable completion criteria are satisfied.

Potential criteria:

1. Required action performed
2. Required notice distributed
3. Filing submitted
4. Carrier / administrator updated
5. Confirmation received
6. Documentation stored
7. Internal record updated
8. Required review completed

Do not use:

> Sent

as equivalent to:

> Completed

unless sending is the actual final obligation.

---

# Completion Evidence Standard

Examples:

- Government filing receipt
- carrier acknowledgment
- administrator confirmation
- employee distribution log
- signed document
- electronic timestamp
- archived communication
- updated system record
- completed audit record

---

# Dynamic Reassessment Standard

Reassess the compliance checklist when:

- Plan year changes
- Employer size changes
- funding arrangement changes
- state changes
- workforce locations change
- plan design changes
- carrier changes
- administrator changes
- regulations change
- audit findings emerge
- Open Enrollment timing changes

Annual compliance checklists should not be copied forward without revalidation.

---

# Stop Rules

Stop and request elevated review when:

- Applicability cannot be determined
- regulatory guidance may have changed
- jurisdiction is unclear
- legal interpretation is required
- employer-size threshold is uncertain
- plan documents conflict
- required governing documentation is missing
- deadline cannot be validated
- material employee rights may be affected
- fiduciary obligations may be involved

Do not fill compliance uncertainty with generic AI knowledge.

---

# Human Review Escalation Standard

Require elevated review for:

- ERISA
- HIPAA
- ACA
- COBRA
- tax issues
- HSA eligibility
- FSA forfeiture
- fiduciary matters
- regulatory filings
- employee eligibility denial
- coverage termination
- appeals
- legal notices
- significant financial exposure

The Skill may organize the requirement.

Qualified professionals retain the authority to interpret and approve.

---

# Decision Conversion Standard

Material compliance findings should become actionable decisions.

Recommended structure:

| Decision / Action | Owner | Authority | Evidence Needed | Deadline | Review Required | Next Workflow |
|---|---|---|---|---|---|---|
| [Action] | [Owner] | [Source] | [Evidence] | [Date] | Yes / No | [Workflow] |

The Skill should move from:

> This may apply

to:

> Here is what must be confirmed, by whom, and what happens once confirmed.

---

# Auditability Standard

Preserve enough information to reconstruct:

```text
What requirement applied?
Why did it apply?
What authority supported it?
Who owned it?
What deadline applied?
What action was taken?
Who reviewed it?
What proves completion?
When was it completed?
```

---

# Internal vs. Employee-Facing Boundary Standard

The checklist is primarily an internal operational tool.

Do not automatically expose:

- Internal compliance risk
- legal-review notes
- process failures
- internal ownership disputes
- audit concerns
- employee-specific data

to employees.

Employee-facing notices should use an appropriate communication workflow.

---

# Output Requirements

Use the following structure unless the user requests another format.

# HR Benefits Annual Compliance Checklist

## 1. Compliance Readiness

**Checklist Period:** [Period]  
**Employer Size:** [Size]  
**Jurisdiction:** [State / States]  
**Plan Year:** [Year]  
**Funding Arrangement:** [Type]  
**Overall Readiness:** Ready / Conditionally Ready / Not Ready

### Material Information Gaps

- [Item]
- [Item]

---

# 2. Executive Compliance Summary

Provide a concise overview including:

- Number of active requirements
- Number of Critical items
- Upcoming deadlines
- Major information gaps
- Professional review items
- Highest-priority action

---

# 3. Applicability Summary

| Requirement Area | Applicability | Basis | Confirmation Needed |
|---|---|---|---|
| [ACA] | Applicable / Conditional / Unknown | [Reason] | [Action] |

---

# 4. Phase 1 — Preparation

| Priority | Task | Timeline / Deadline | Owner | Required Documentation | Status | Completion Evidence |
|---|---|---|---|---|---|---|
| Critical / High / Moderate | [Task] | [Date] | [Owner] | [Document] | [Status] | [Evidence] |

---

# 5. Phase 2 — Execution

| Priority | Task | Timeline / Deadline | Owner | Required Documentation | Status | Completion Evidence |
|---|---|---|---|---|---|---|
| [ ] | [ ] | [ ] | [ ] | [ ] | [ ] | [ ] |

---

# 6. Phase 3 — Follow-Up

| Priority | Task | Timeline / Deadline | Owner | Required Documentation | Status | Completion Evidence |
|---|---|---|---|---|---|---|
| [ ] | [ ] | [ ] | [ ] | [ ] | [ ] | [ ] |

---

# 7. Phase 4 — Review

| Priority | Task | Timeline / Deadline | Owner | Required Documentation | Status | Completion Evidence |
|---|---|---|---|---|---|---|
| [ ] | [ ] | [ ] | [ ] | [ ] | [ ] | [ ] |

---

# 8. Critical Compliance Items

For each Critical item:

### [Requirement]

**Why It Applies:**  
[Basis]

**Authority:**  
[Source]

**Deadline:**  
[Date]

**Owner:**  
[Role]

**Required Action:**  
[Action]

**Completion Evidence:**  
[Evidence]

**Review Required:**  
[Yes / No]

---

# 9. Upcoming Compliance Calendar

| Date / Timing | Requirement | Owner | Internal Reminder | Status |
|---|---|---|---|---|
| [Date] | [Requirement] | [Owner] | [Reminder] | [Status] |

Internal reminders must be labeled as operational controls.

---

# 10. Required Notices & Forms

| Notice / Form | Requirement | Audience / Recipient | Deadline | Owner | Source |
|---|---|---|---|---|---|
| [Item] | [Reason] | [Recipient] | [Date] | [Owner] | [Source] |

---

# 11. Documentation & Audit Requirements

| Task | Required Documentation | Storage Location | Completion Evidence |
|---|---|---|---|
| [Task] | [Document] | [System] | [Evidence] |

---

# 12. Items Requiring Professional Review

| Issue | Why Review Is Needed | Review Type | Owner | Deadline |
|---|---|---|---|---|
| [Issue] | [Reason] | Legal / Compliance / Carrier / TPA | [Owner] | [Date] |

---

# 13. Open Questions & Missing Information

| Question / Missing Item | Why It Matters | Owner | Required By |
|---|---|---|---|
| [Item] | [Reason] | [Owner] | [Date] |

---

# 14. Recommended Next Steps

| Priority | Action | Owner | Timing | Completion Criteria |
|---|---|---|---|---|
| 1 | [Action] | [Owner] | [Timing] | [Criteria] |

---

# Compliance Checklist Quick View

When requested, also provide:

```text
CHECKLIST PERIOD:
[PERIOD]

CRITICAL ITEMS:
[COUNT]

NEXT DEADLINE:
[DATE]

NEXT REQUIREMENT:
[REQUIREMENT]

OWNER:
[ROLE]

MAJOR DATA GAP:
[GAP]

PROFESSIONAL REVIEW REQUIRED:
[YES / NO]

OVERALL STATUS:
[READY / CONDITIONAL / NOT READY]
```

---

# Machine-Readable Compliance Checklist

When requested, also output:

```text
checklist_period
employer_size
jurisdiction
plan_year
funding_arrangement
requirement_id
requirement_name
requirement_category
authority_type
authority_source
applicability
applicability_basis
trigger
deadline_type
deadline_date
relative_deadline
frequency
phase
priority
owner
supporting_party
required_notice
required_form
required_documentation
completion_evidence
workflow_status
professional_review_required
review_type
dependency
internal_reminder
source_date
confidence
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

- [ ] Checklist scope is defined
- [ ] Employer size is considered
- [ ] Jurisdiction is considered
- [ ] Plan year is identified where relevant
- [ ] Funding arrangement is considered where relevant
- [ ] Applicability is evaluated
- [ ] Current governing authorities are identified
- [ ] Current regulatory requirements are validated where necessary
- [ ] Requirements are distinguished from best practices
- [ ] Conditional requirements remain conditional
- [ ] Deadlines are supported
- [ ] Internal reminders are not presented as governing deadlines
- [ ] Owners are assigned
- [ ] Notices and forms are identified
- [ ] Documentation requirements are identified
- [ ] Completion evidence is defined
- [ ] Checklist is organized by phase
- [ ] Priorities are reasonable
- [ ] Critical items are used sparingly
- [ ] Dependencies are identified
- [ ] Open questions are visible
- [ ] Professional review items are flagged
- [ ] Workflow status is accurate
- [ ] Auditability is preserved
- [ ] No legal or regulatory requirement is fabricated

---

# Failure Conditions

The Skill should not be considered complete if:

- It produces a generic universal compliance list without evaluating applicability
- It invents regulatory requirements
- It uses outdated requirements as current
- It invents deadlines
- It ignores employer size
- It ignores jurisdiction
- It ignores funding arrangement where material
- It presents best practices as law
- It treats conditional obligations as confirmed
- It fails to assign ownership
- It fails to define completion evidence
- It marks submitted tasks as completed without confirmation
- It hides missing information
- It fails to identify professional-review issues
- It provides unsupported legal conclusions

If any failure condition exists:

> Revise or escalate.

---

# Guardrails

## Do Not Fabricate Compliance Requirements

Never invent:

- notices
- filings
- deadlines
- penalties
- eligibility requirements
- employer obligations
- regulatory thresholds

---

## Validate Current Authority

Time-sensitive compliance information should be checked against current authoritative sources.

---

## Distinguish Requirement From Best Practice

Clearly label:

- Regulatory Requirement
- Plan Requirement
- Administrative Requirement
- Operational Recommendation

---

## Do Not Guess Applicability

If a requirement depends on employer size, jurisdiction, plan type, or funding arrangement:

> Identify what must be confirmed.

---

## Do Not Provide Unsupported Legal Advice

Escalate legal interpretation to qualified counsel where appropriate.

---

## Protect Sensitive Information

A compliance checklist generally should not require employee-specific PII.

Use aggregate or organizational information wherever possible.

---

## Preserve Human Accountability

This Skill supports HR and Benefits professionals.

The authorized:

- HR Leader
- Benefits Manager
- Plan Administrator
- Compliance Professional
- Carrier
- TPA
- COBRA Administrator
- Legal Counsel
- Regulatory Authority

remains responsible for final compliance interpretation and action.

### Your people make the decisions. Your AI Teammates do the work.

---

# Professional Tone Standard

Write like an experienced HR Compliance Officer building a checklist that a small Benefits team will actually use.

The tone should be:

- Precise
- Practical
- Structured
- Action-oriented
- Audit-friendly
- Non-alarmist
- Clear

Avoid:

- Generic compliance dumping
- Legalistic prose
- Fear-based language
- Unsupported certainty
- Repetitive disclaimers
- Long unprioritized lists
- Generic AI phrasing

The checklist should function as an operating tool.

---

# Example

## Example Input

```text
Checklist Topic or Period:
Open Enrollment Preparation

Employer Size:
425 employees

Jurisdiction:
California

Benefits Programs:
Medical, Dental, Vision, Life, HSA

Plan Year:
January 1 – December 31

Open Enrollment:
November 1 – November 15

Funding Arrangement:
Fully insured medical

Known Context:
Carrier is changing one medical plan. Employer contributes to employee HSAs.
```

---

## Example Output

# HR Benefits Annual Compliance Checklist

## 1. Compliance Readiness

**Checklist Period:** Open Enrollment Preparation  
**Employer Size:** 425 employees  
**Jurisdiction:** California  
**Plan Year:** Calendar Year  
**Funding Arrangement:** Fully Insured Medical  
**Overall Readiness:** Conditionally Ready

### Material Information Gaps

- Current carrier Open Enrollment requirements
- Final plan-change documentation
- Current required notice inventory
- Confirmation of employer-specific ACA / ERISA applicability
- Current HSA contribution structure

---

# 2. Executive Compliance Summary

The Open Enrollment workflow should focus first on validating the final plan changes, required employee communications, election deadlines, carrier submission deadlines, and HSA-related information.

Regulatory and plan-specific notice requirements should be confirmed using current authoritative sources before distribution.

No employee-facing deadline should be communicated until the employer's Open Enrollment period and carrier submission timing are confirmed.

---

# 3. Phase 1 — Preparation

| Priority | Task | Timeline / Deadline | Owner | Required Documentation | Status | Completion Evidence |
|---|---|---|---|---|---|---|
| Critical | Confirm final plan design | Before employee communications | Benefits Manager | Carrier renewal / final plan terms | In Progress | Final approved plan summary |
| Critical | Confirm Open Enrollment dates | Before announcement | Benefits Manager | OE calendar | Confirmed | Approved calendar |
| High | Identify required employee notices | Before OE materials finalized | Benefits / Compliance | Current governing requirements | Pending Review | Notice inventory |
| High | Validate HSA contribution information | Before employee guide finalized | Payroll / Benefits | Contribution schedule | Pending | Approved contribution table |
| High | Review carrier submission deadlines | Before OE opens | Benefits Administrator | Carrier guidance | Pending | Carrier deadline confirmation |

---

# 4. Phase 2 — Execution

| Priority | Task | Timeline / Deadline | Owner | Required Documentation | Status | Completion Evidence |
|---|---|---|---|---|---|---|
| Critical | Open enrollment window | Nov. 1–15 | Benefits | OE materials | Scheduled | Enrollment platform records |
| High | Distribute employee communications | Before / at OE opening | HR / Benefits | Approved communications | Pending | Distribution log |
| High | Monitor incomplete elections | During OE | Benefits Administrator | Election report | Pending | Follow-up log |

---

# 5. Phase 3 — Follow-Up

| Priority | Task | Timeline / Deadline | Owner | Required Documentation | Status | Completion Evidence |
|---|---|---|---|---|---|---|
| Critical | Validate final elections | Immediately after OE | Benefits Administrator | Election export | Pending | QC report |
| High | Submit carrier updates | Per confirmed carrier deadline | Benefits Administrator | Enrollment files | Pending | Carrier confirmation |
| High | Reconcile payroll deductions | Before first affected payroll | Payroll / Benefits | Election + payroll data | Pending | Reconciliation confirmation |

---

# 6. Phase 4 — Review

| Priority | Task | Timeline / Deadline | Owner | Required Documentation | Status | Completion Evidence |
|---|---|---|---|---|---|---|
| High | Reconcile January carrier invoices | First billing cycle | Benefits | Carrier invoice + eligibility | Pending | Reconciliation report |
| Moderate | Archive OE communications | After OE | Benefits | Final communications | Pending | Document repository record |
| Moderate | Review process issues | Within 30 days after implementation | Benefits Manager | Issue log | Pending | Process review summary |

---

# 7. Professional Review Items

Current statutory and regulatory notice requirements should be validated against current authoritative sources before finalizing the compliance checklist.

This example does not independently establish every federal or California Benefits obligation applicable to the employer.

---

# Original Prompt

The original HR Benefits AI Advantage System prompt that inspired this Skill:

> **1.2 Annual Compliance Checklist Generator**
>
> **Purpose:** Create a comprehensive, ready-to-use compliance checklist tailored to your mid-market organization so nothing falls through the cracks during Open Enrollment, ACA reporting, or annual requirements.
>
> **When to Use:** At the start of each quarter, before Open Enrollment, or when preparing for audits and year-end compliance.
>
> **Typical Time Saved:** 45–90 minutes per checklist.
>
> **Role:** You are a senior HR Compliance Officer specializing in mid-market employers (20–1,500 employees).
>
> **Action:** Create a comprehensive compliance checklist for the requested topic or period.
>
> **Context:** We are a mid-market company with 20–1,500 employees operating in California. We must maintain full compliance with federal (HIPAA, ERISA, ACA, FMLA) and state regulations while operating with a small team.
>
> **Examples:** Include required notices, timelines, forms, documentation, and responsible parties for topics such as Open Enrollment, ACA reporting, COBRA administration, or dependent verification.
>
> **Format:** Present as a prioritized, actionable checklist with columns for Task, Timeline/Deadline, Owner, Required Documentation, and Status. Group items by phase (Preparation, Execution, Follow-up, Review). Highlight critical items in bold.

---

# Evolution From Prompt to Skill

The original prompt established the goal of creating an actionable compliance checklist.

This Skill expands that prompt into a reusable Compliance Intelligence capability by adding:

- HR Benefits Profile inheritance
- Employer-context validation
- Governing Authority Standard
- Regulatory Currency Standard
- Jurisdiction Standard
- Applicability Standard
- Applicability Driver Standard
- Evidence classification
- Requirement vs. Best Practice Standard
- Obligation Extraction Standard
- Effective-Date Integrity
- Deadline Integrity
- Recurring Requirement Standard
- Materiality ranking
- Compliance Phase Standard
- Structured workflow
- Workflow state
- Ownership
- Dependency management
- Handoff Integrity
- System-of-Record Standard
- Completion Criteria
- Completion Evidence
- Dynamic reassessment
- Stop rules
- Human Review Escalation
- Decision Conversion
- Auditability
- Machine-readable compliance checklist
- Quality controls
- Failure conditions
- HR-specific privacy safeguards

The progression is:

**Prompt 1.2 → Foundational Skill → Compliance Checklist Intelligence → Operational Compliance System**

---

# Related Foundational Skills

- [1.1 Extract Key Deadlines from SPD / Plan Documents](../01-extract-key-deadlines/SKILL.md)
- **1.3 Policy Interpretation & Summary**
- **2.1 Open Enrollment Data Summary**
- **2.4 Late Enrollment / Qualifying Event Handler**
- **5.1 FMLA / Leave Tracking & Timeline**

Add live links as additional Skills are published.

---

# Related Signature Skills

Future related Signature Skills include:

- Open Enrollment Command Center
- FMLA & Leave Management Coordinator
- Employee Benefits Communications Suite

---

# Suggested Invocation

```text
Run HR Benefits Foundational Skill 1.2 — Annual Compliance Checklist Intelligence.

Checklist Topic or Period:
[INSERT]

Employer Size:
[INSERT]

Jurisdiction:
[INSERT]

Plan Year:
[INSERT]

Funding Arrangement:
[INSERT]

Benefits Programs:
[INSERT]

Known Deadlines:
[OPTIONAL]

Supporting Documents:
[OPTIONAL]
```

---

# Minimum Viable Invocation

```text
Checklist Topic:
[INSERT]

Employer Size:
[INSERT]

Jurisdiction:
[INSERT]
```

---

# Version History

## 1.0.0

Initial public release.

Second HR Benefits Foundational Skill published under the HR Benefits AI Advantage System using:

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
