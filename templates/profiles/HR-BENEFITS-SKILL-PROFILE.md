# Apeironix HR Benefits Skill Profile

## Domain Profile for the HR Benefits AI Advantage System

**Profile:** HR Benefits  
**Applies To:** HR, Employee Benefits, Total Rewards, Leave, Eligibility, Payroll-Adjacent Benefits Operations, Employee Communications  
**Parent Standard:** Apeironix Gold Standard Skill Template  
**Recommended Parent Version:** v2.2 or later  
**Maintainer:** Apeironix  
**License:** Apache-2.0  
**Status:** Public  

---

# Purpose

The **Apeironix HR Benefits Skill Profile** defines the additional operating standards required when an Apeironix Skill is used within HR and Employee Benefits workflows.

It is not a replacement for the Apeironix Gold Standard Skill Template.

It is a **domain-specific control layer** that sits on top of the Gold Standard.

The relationship is:

```text
Apeironix Gold Standard Skill Template
                +
      HR Benefits Skill Profile
                ↓
       HR Benefits Skill
```

The Gold Standard defines the universal Skill architecture.

This profile adds the safeguards required when AI interacts with:

- Employee information
- Benefits eligibility
- Plan documents
- Payroll-related benefits data
- Carrier information
- HSA contributions
- COBRA workflows
- Open Enrollment
- Leave administration
- Employee communications
- Claims support
- Benefits reconciliation
- Benefits compliance
- Total Rewards
- Benefits strategy
- HRIS and payroll systems

---

# Core Principle

## Increase Capacity Without Removing Human Accountability

The HR Benefits AI Advantage System is designed to help HR and Benefits professionals perform work:

- Faster
- More consistently
- More accurately
- More transparently
- With better documentation
- With stronger operational controls

It is not designed to transfer final authority for employee-impacting decisions to AI.

The operating principle is:

> **Your people make the decisions. Your AI Teammates do the work.**

---

# HR Benefits Safety Model

All HR Benefits Skills should follow:

> **Anonymize → Generalize → Summarize → Review → Approve**

This sequence should be treated as a default operating discipline unless the workflow is executed within an approved environment specifically designed to handle the required sensitive information.

---

# 1. Anonymize

Remove unnecessary employee identity.

Prefer:

```text
Employee A
Employee B
Dependent A
Location A
Department B
```

instead of:

```text
John Smith
Maria Lopez
Sarah Jones
```

where identity is not necessary to perform the task.

Do not expose personal identity simply because it exists in the source data.

---

# 2. Generalize

Use generalized values when exact employee-specific information is unnecessary.

Example:

Preferred:

```text
Approximately 65 employees participate in the medical plan.
```

instead of exposing an entire eligibility roster.

Preferred:

```text
Monthly carrier billing is approximately $85,000.
```

when exact invoice-level detail is not required.

---

# 3. Summarize

Provide the minimum information necessary to execute the workflow.

Where possible, use:

- Aggregate enrollment counts
- Coverage-tier totals
- Plan-level cost summaries
- Anonymized discrepancy lists
- Generalized payroll information
- Structured benefits summaries
- Policy excerpts relevant to the question

rather than entire raw employee datasets.

---

# 4. Review

AI output should be treated as a working draft until reviewed against the applicable authoritative information.

Review may include:

- Plan documents
- Summary Plan Descriptions
- Carrier certificates
- Summary of Benefits and Coverage
- Employer policies
- HRIS records
- Payroll records
- Eligibility files
- Carrier records
- HSA administrator records
- COBRA administrator records
- Leave records
- Applicable regulatory guidance
- Legal or compliance advice where required

---

# 5. Approve

The appropriate human decision-maker remains responsible for final action.

Depending on the workflow, that may include:

- HR Manager
- Benefits Manager
- Benefits Administrator
- Total Rewards Leader
- Payroll Manager
- Plan Administrator
- Benefits Consultant
- Broker / Advisor
- Carrier
- TPA
- COBRA Administrator
- HSA Administrator
- Legal Counsel
- Compliance Professional
- Executive Leadership

AI may organize the work.

It does not inherit the authority of these roles.

---

# Sensitive Data Boundary Standard

HR Benefits Skills may encounter highly sensitive information.

The Skill should identify when the workflow involves:

## Personally Identifiable Information

Examples may include:

- Employee name
- Address
- Personal email
- Personal phone number
- Date of birth
- Employee ID
- Dependent identity
- Social Security number

---

## Benefits-Sensitive Information

Examples may include:

- Benefit elections
- Dependent coverage
- Coverage tier
- Beneficiary information
- HSA contributions
- COBRA status
- Premium contributions
- Enrollment history

---

## Health or Leave Information

Examples may include:

- Medical information
- Claims information
- Prescription information
- Disability information
- Medical certification
- Leave reason
- Return-to-work information

---

## Payroll / Financial Information

Examples may include:

- Compensation
- Payroll deductions
- Employer contributions
- Bank information
- HSA contributions
- Employee premium deductions

---

# Minimum Necessary Data Standard

Every HR Benefits Skill should ask:

> What is the minimum amount of data required to perform this task responsibly?

If the answer does not require:

- Employee identity
- Full payroll files
- Medical detail
- Dependent identity
- Claim-level information

do not request or expose it unnecessarily.

The Skill should prefer:

```text
necessary data
```

over:

```text
available data
```

---

# Data Sensitivity Classification

Where useful, classify input data as:

### Low Sensitivity

General plan information or non-personal operational data.

Examples:

- Plan names
- Enrollment dates
- General plan design
- Employer contribution strategy
- Public communications

---

### Moderate Sensitivity

Internal company information that should not be unnecessarily exposed.

Examples:

- Aggregate enrollment
- Aggregate premium
- Renewal pricing
- Internal workflow details
- Vendor information

---

### High Sensitivity

Employee-specific or financial information requiring elevated protection.

Examples:

- Individual elections
- Payroll deductions
- Dependent data
- HSA transactions
- COBRA records

---

### Restricted / Highly Sensitive

Information that should only be processed in appropriately approved environments.

Examples may include:

- SSNs
- medical information
- claim details
- bank information
- sensitive leave documentation
- other protected personal data

The Skill should not encourage unrestricted use of high-sensitivity information in general-purpose AI environments.

---

# Approved Environment Standard

The Skill should distinguish between:

### General-Purpose AI Environment

Use anonymized, generalized, or summarized information whenever possible.

### Organization-Approved Enterprise AI Environment

May allow additional business data depending on organizational policy and contractual safeguards.

### Integrated Apeironix / Approved Agentic Workflow

May process authorized operational data subject to the system's access controls, security model, and workflow permissions.

The Skill should never assume that a platform is approved merely because it technically accepts the data.

---

# Governing Document Standard

HR Benefits Skills should never treat general AI knowledge as the controlling source for plan-specific questions.

Applicable governing information may include:

1. Current plan document
2. Current Summary Plan Description
3. Current carrier certificate
4. Current Summary of Benefits and Coverage
5. Current employer policy
6. Current plan amendment
7. Current carrier eligibility rules
8. Current administrative agreement
9. Current TPA guidance
10. Current plan administrator determination
11. Applicable law or regulation
12. Authorized legal or compliance interpretation

Where documents conflict, the Skill should identify the conflict rather than silently decide which version controls.

---

# Benefits Source Hierarchy Standard

Unless the specific workflow requires another hierarchy, use:

```text
Current Governing Document
        ↓
Current Amendment / Endorsement
        ↓
Current Carrier / Administrator Documentation
        ↓
Current Employer Policy
        ↓
Current Employee-Specific Record
        ↓
Current HRIS / Payroll Record
        ↓
Internal Process Documentation
        ↓
Historical Documentation
        ↓
General Benefits Knowledge
        ↓
AI Inference
```

The applicable hierarchy may vary by workflow.

The Skill should say when that occurs.

---

# Document Completeness Standard

Before relying on a benefits document, determine whether the supplied information is:

### Complete Enough

Enough authoritative information exists to support the requested task.

### Partially Complete

Useful work can be performed, but one or more material items require confirmation.

### Fragmentary

Only limited analysis should be produced.

Examples of incomplete inputs may include:

- One page of an SPD
- A screenshot of a carrier portal
- An employee email describing a benefit
- A plan summary without governing provisions
- Old Open Enrollment materials
- Historical eligibility information

A polished benefits summary should never hide incomplete source documentation.

---

# Effective-Date Integrity Standard

Effective dates are critical in HR Benefits workflows.

Every Skill involving:

- Enrollment
- Termination
- Qualifying event
- COBRA
- New hire eligibility
- Dependent eligibility
- Plan changes
- HSA changes
- Leave
- Payroll deductions

should explicitly identify relevant dates.

Potential dates include:

- Hire date
- Eligibility date
- Enrollment date
- Coverage effective date
- Termination date
- Coverage termination date
- Qualifying-event date
- Notification date
- Election deadline
- Payroll effective date
- Carrier submission date
- COBRA trigger date
- Leave start date
- Leave end date
- Return-to-work date

Do not infer an effective date from a transaction date unless governing rules support that conclusion.

---

# Date Source Standard

For material dates, identify the source when possible.

Recommended structure:

| Date | Value | Source | Confidence |
|---|---|---|---|
| Hire Date | [Date] | HRIS | High |
| Coverage Effective Date | [Date] | Plan Rule | High |
| Carrier Update Date | [Date] | Carrier Confirmation | High |

If dates conflict:

> Flag the conflict before recommending action.

---

# Eligibility Integrity Standard

AI should not independently determine benefits eligibility without sufficient governing information.

Eligibility analysis should consider, where relevant:

- Employment status
- Hours
- Classification
- Waiting period
- Plan eligibility rule
- Effective-date rule
- Dependent definition
- Qualifying event
- Prior coverage
- Work location
- Union status
- Applicable policy
- Applicable plan rule

Classify findings as:

### Confirmed Eligible

Supported by controlling information.

### Apparently Eligible

Available facts suggest eligibility but confirmation remains appropriate.

### Apparently Not Eligible

Available facts suggest the eligibility requirement is not met.

### Requires Plan Administrator Review

Material ambiguity exists.

### Insufficient Information

Eligibility cannot responsibly be determined.

Avoid unsupported binary answers.

---

# Enrollment Decision Boundary Standard

AI may:

- Identify missing enrollment information
- Calculate deadlines from supplied rules
- Organize elections
- Flag inconsistencies
- Prepare communications
- Recommend verification

AI should not autonomously:

- Elect benefits for an employee
- Waive coverage for an employee
- Change employee elections
- Determine employee intent
- Override plan rules
- Approve exceptions

Employee elections and authorized administrative actions remain human-controlled.

---

# Employee Intent Standard

Never infer employee intent from:

- Prior enrollment
- Family status
- Payroll deduction
- Previous plan selection
- Demographic information

Example:

Do not conclude:

> The employee intended to elect family coverage.

Use:

> The employee's submitted election and payroll record appear inconsistent and should be confirmed.

---

# Qualifying Event Standard

When analyzing a qualifying life event, the Skill should identify:

1. Reported event
2. Event date
3. Date HR was notified
4. Requested coverage change
5. Applicable plan rule
6. Required documentation
7. Applicable deadline
8. Proposed effective date
9. Items requiring confirmation
10. Required carrier / system actions

The Skill should not assume that every reported life event automatically permits every requested benefits change.

---

# COBRA Boundary Standard

Where COBRA or continuation coverage may be involved, the Skill should distinguish between:

- Potential qualifying event
- Employee / dependent status
- Employer administrative action
- COBRA administrator action
- Notice requirement
- Election process
- Carrier eligibility update

AI may support:

- Workflow organization
- Data validation
- Timeline tracking
- Communication drafting
- Exception identification

Final COBRA determinations should follow the applicable administrator, plan, and legal requirements.

---

# HSA Integrity Standard

HSA-related workflows may involve:

- Eligibility
- Payroll deduction
- Employer contribution
- Employee contribution
- Annual limits
- Contribution timing
- Trustee / custodian posting
- Corrections

The Skill should distinguish among:

### Payroll Amount

Amount deducted or funded through payroll.

### Expected Contribution

Amount expected based on available instructions.

### Posted Contribution

Amount actually reflected by the HSA administrator.

### Discrepancy

Difference requiring review.

### Correction

Action confirmed by authorized party.

Do not treat payroll deduction as proof of successful HSA posting.

---

# Reconciliation Authority Standard

In reconciliation workflows, define systems by role.

Possible sources:

```text
HRIS
Payroll
Benefits Administration Platform
Carrier Invoice
Carrier Eligibility File
HSA Administrator
COBRA Administrator
```

Do not assume one source is authoritative for every field.

Example:

| Data Element | Likely Authority |
|---|---|
| Hire Date | HRIS |
| Payroll Deduction | Payroll |
| Carrier Billing | Carrier Invoice |
| Carrier Enrollment | Carrier Eligibility |
| HSA Posting | HSA Administrator |

The Skill should identify the appropriate system of record for the specific data element.

---

# Reconciliation Match Standard

Classify transactions as:

### Matched

Source records align within the defined comparison standard.

### Timing Difference

Difference may be explained by legitimate processing timing.

### Confirmed Discrepancy

Evidence supports a real mismatch.

### Potential Discrepancy

Mismatch exists but requires additional verification.

### Unable to Reconcile

Source information is insufficient or materially inconsistent.

Do not automatically treat every mismatch as an error.

---

# Financial Impact Standard

When calculating financial impact:

- Show calculation basis
- Distinguish actual from estimated
- Avoid double counting
- Identify the time period
- Separate recurring from one-time amounts

Recommended classifications:

### Confirmed Financial Impact

Supported by source records.

### Estimated Financial Impact

Calculated using disclosed assumptions.

### Potential Financial Exposure

Possible impact that requires further validation.

Avoid presenting potential recovery as money already recovered.

---

# Recovery Integrity Standard

Use precise language.

### Identified

Discrepancy has been found.

### Submitted for Correction

Correction request has been sent.

### Carrier Confirmed

Carrier acknowledged or accepted correction.

### Credit Pending

Financial adjustment is expected but not yet received.

### Recovered

Credit or refund has actually been received or verified.

Do not label:

> identified savings

as:

> recovered dollars.

---

# Transaction Lineage Standard

For financial and eligibility workflows, preserve:

```text
Source Record
     ↓
Normalized Record
     ↓
Comparison
     ↓
Exception
     ↓
Correction Request
     ↓
Carrier / Administrator Response
     ↓
Final Adjustment
     ↓
Verification
```

Do not overwrite the original transaction history with the corrected value.

---

# Leave Management Boundary Standard

Leave workflows are high-impact HR processes.

AI may support:

- Timeline creation
- Deadline tracking
- Documentation checklists
- Communication drafting
- Leave-balance calculations
- Return-to-work workflow organization
- Missing-information identification

AI should not independently make final determinations involving:

- Leave entitlement
- Legal eligibility
- Medical sufficiency
- Reasonable accommodation
- Disability determination
- Retaliation risk
- Employment termination
- Fitness for duty
- Legal compliance

These require authorized human review.

---

# Leave Fact Classification Standard

When evaluating leave information, distinguish:

### Employee-Reported Fact

Information provided by the employee.

### Employer Record

Information contained in HRIS, payroll, attendance, or leave records.

### Medical Provider Documentation

Information contained in authorized certification.

### Policy Requirement

Requirement from employer policy.

### Regulatory Requirement

Requirement supported by current legal authority.

### AI Interpretation

Reasoning generated by the Skill.

Do not convert employee allegations or medical descriptions into formal legal conclusions.

---

# Medical Information Minimization Standard

Leave workflows should request only the information necessary for the administrative task.

Avoid requesting or reproducing unnecessary:

- Diagnosis detail
- Treatment detail
- Medication information
- Medical history

when the workflow can operate using:

- Certification status
- Leave dates
- Restrictions
- Return-to-work status
- Administrative requirements

---

# Claims Support Boundary Standard

Benefits claim support Skills may help:

- Organize denial information
- Summarize carrier reasoning
- Identify appeal requirements
- Draft employee communications
- Create appeal-letter drafts
- Assemble supporting-document checklists

They should not:

- Guarantee reversal
- State that a carrier acted illegally without authoritative support
- Manufacture medical or factual arguments
- Invent plan provisions
- Act as legal counsel

Use neutral language.

---

# Denial Attribution Standard

When discussing a denied claim, distinguish:

### Carrier Statement

What the carrier or administrator stated.

### Employee Statement

What the employee reported.

### Documented Plan Provision

What the available plan document says.

### Supporting Evidence

What is actually documented.

### Open Question

What remains unresolved.

Example:

Preferred:

> The carrier's denial notice states that the service was not considered covered under the cited plan provision.

Avoid:

> The service is not covered.

unless the governing source establishes that conclusion.

---

# Neutral Narrative / Attribution Standard

HR Benefits Skills involving:

- Complaints
- Appeals
- Claims
- Leave disputes
- Eligibility disputes
- Employee relations
- Carrier disputes

should distinguish:

- Confirmed fact
- Employee statement
- Carrier statement
- HR observation
- Formal determination
- AI inference

Attribute information to its source rather than converting allegations into facts.

---

# Employee Communication Standard

Employee-facing Benefits communication should generally be:

- Clear
- Respectful
- Plain-language
- Action-oriented
- Accurate
- Calm
- Nonjudgmental
- Scannable

It should clearly answer:

1. What is happening?
2. Why does it matter?
3. What does the employee need to do?
4. By when?
5. Where can the employee get help?

---

# Plain-Language Translation Standard

Translate technical terms where appropriate.

Example:

Technical:

> Evidence of insurability may be required.

Plain-language:

> You may need to answer health questions or provide additional information before the insurance company approves the additional coverage.

Do not simplify so aggressively that the meaning changes.

---

# Employee Action Standard

When employee action is required, clearly state:

```text
Action:
[What the employee needs to do]

Deadline:
[Date / timing]

Where:
[System / HR contact / carrier]

What to Provide:
[Documents / information]

What Happens Next:
[Expected next step]
```

Avoid vague calls to action.

---

# Communication Approval Standard

Require human review before sending communications involving:

- Eligibility denial
- Coverage termination
- COBRA
- Claims denial
- Leave entitlement
- Leave denial
- Medical information
- Payroll correction
- Employee termination
- Compliance determination
- Material financial impact
- Legal rights

Routine informational communications may follow a lighter review standard depending on organizational policy.

---

# Multilingual Communication Standard

Translations should preserve:

- Meaning
- Required action
- Deadlines
- Plan terminology
- Tone
- Important qualifications

Do not freely rewrite legally important wording.

Where the communication is legally required or compliance-sensitive:

> Use approved translations where available.

AI translation should not automatically replace an officially required translated notice.

---

# Compliance Authority Standard

AI should distinguish:

### Operational Guidance

How to organize the work.

### Plan Administration

Application of the employer's plan rules.

### Compliance Interpretation

Interpretation of laws or regulations.

### Legal Advice

Advice requiring qualified counsel.

The Skill may support operational guidance.

It should escalate compliance or legal interpretation where appropriate.

---

# Jurisdiction Standard

HR and Benefits obligations may vary by:

- Federal law
- State
- Local jurisdiction
- Employer size
- Plan structure
- Funding arrangement
- Employee location
- Employer location
- Employee classification

Do not assume a universal rule where jurisdiction matters.

---

# Regulatory Currency Standard

Compliance-sensitive Skills should not rely on outdated requirements.

When current law, regulation, limits, deadlines, or agency guidance materially affect the answer:

- Use current authoritative sources where available
- Identify the date of the authority
- Avoid relying solely on embedded model knowledge
- Flag unresolved jurisdictional questions

---

# Obligation Extraction Standard

Whenever a benefits document creates a requirement, extract:

| Requirement | Responsible Party | Trigger | Deadline | Required Evidence | Consequence if Stated | Source |
|---|---|---|---|---|---|---|
| [Requirement] | [Owner] | [Trigger] | [Date] | [Evidence] | [Consequence] | [Source] |

Do not invent a consequence when the source does not state one.

---

# Workflow State Standard

HR Benefits operational Skills should identify the actual state of the work.

Examples:

```text
Received
Validated
Pending Employee Information
Pending HR Review
Pending Carrier
Pending Payroll
Pending Administrator
Submitted
Confirmed
Correction Pending
Completed
Escalated
```

Do not use:

> Completed

when the action was merely submitted.

---

# Ownership Standard

Every material operational action should have an owner.

Examples:

- Employee
- HR Coordinator
- Benefits Administrator
- Payroll
- Carrier
- Broker
- TPA
- COBRA Administrator
- HSA Administrator
- Manager
- Legal Counsel

Avoid:

> Follow up on this.

Prefer:

> Benefits Administrator — confirm carrier correction by Friday.

---

# Handoff Integrity Standard

A handoff should identify:

1. Who is sending the work
2. Who receives it
3. What is being transferred
4. Current workflow state
5. Supporting data
6. Required action
7. Due date
8. Confirmation of receipt or ownership

Recommended structure:

```text
From:
[ROLE]

To:
[ROLE / SYSTEM]

Employee / Case:
[ANONYMIZED IDENTIFIER WHERE POSSIBLE]

Current State:
[STATE]

Action Required:
[ACTION]

Effective Date:
[DATE]

Deadline:
[DATE]

Supporting Evidence:
[DOCUMENT / SOURCE]

Receipt Confirmed:
[YES / NO]
```

---

# System-of-Record Standard

HR Benefits workflows commonly span multiple systems.

The Skill should identify which system is authoritative for each data type.

Example:

| Data | System of Record |
|---|---|
| Employment Status | HRIS |
| Pay / Deduction | Payroll |
| Benefits Election | Benefits Administration |
| Carrier Enrollment | Carrier |
| HSA Posting | HSA Administrator |
| COBRA Status | COBRA Administrator |
| Final Employee Communication | HR / Document Repository |

Do not create competing authoritative records.

---

# Write-Back Standard

Where AI-supported workflows update systems, define:

- What system receives the update
- What fields may be updated
- What human approval is required
- Whether confirmation is required
- How conflicting data is handled
- How the original value is preserved where appropriate

AI should not silently modify employee-impacting records.

---

# Effective-Date Write-Back Control

Before updating:

- Eligibility
- Coverage
- Payroll deduction
- HSA
- COBRA
- Leave

confirm:

1. Correct employee / record
2. Correct action
3. Correct effective date
4. Correct source authority
5. Required approval
6. Downstream impact

---

# Stop Rules

The Skill should stop and request review when:

- Governing documentation is missing
- Material dates conflict
- Eligibility cannot be determined
- Sensitive information exceeds the intended environment
- A legal interpretation is required
- A plan document is ambiguous
- Employee intent is unclear
- A coverage termination may occur
- A COBRA determination is uncertain
- A leave decision is unclear
- A financial correction cannot be reconciled
- Carrier and HRIS records materially conflict
- Requested action may be irreversible
- The Skill lacks authority for the action

The correct response to uncertainty is not stronger language.

It is escalation.

---

# Human Review Escalation Standard

Elevated review should generally be required for:

### Employee Eligibility

- Eligibility denial
- Eligibility exception
- Dependent eligibility dispute

### Coverage

- Coverage termination
- Retroactive coverage change
- Plan exception

### Leave

- Leave denial
- Medical certification issue
- Extended leave
- Return-to-work restriction
- Accommodation-related issue

### Claims

- Claim appeal
- Coverage dispute
- High-cost claim issue

### Financial

- Material payroll correction
- Material HSA correction
- Significant carrier billing discrepancy

### Compliance

- COBRA determination
- ACA issue
- ERISA issue
- HIPAA issue
- Legal interpretation

---

# Irreversible Action Standard

Before any workflow causes a material or difficult-to-reverse action, require explicit human approval.

Examples:

- Terminating coverage
- Removing a dependent
- Rejecting an election
- Issuing a final denial
- Changing payroll deductions
- Processing large financial corrections
- Closing a COBRA case
- Closing a leave case
- Sending a sensitive employee communication

AI may prepare the action.

Authorized humans approve it.

---

# Completion Criteria Standard

An HR Benefits workflow should not be considered complete simply because the AI produced an output.

Completion may require:

```text
Analysis Complete
        ↓
Human Review
        ↓
Action Submitted
        ↓
System Updated
        ↓
Carrier / Administrator Confirmed
        ↓
Employee Communicated
        ↓
Financial Impact Verified
        ↓
Documentation Stored
        ↓
Case Closed
```

Use only the steps relevant to the workflow.

---

# Completion Evidence Standard

Where appropriate, require evidence such as:

- Carrier confirmation
- Payroll confirmation
- Updated HRIS record
- Updated benefits platform record
- HSA administrator confirmation
- COBRA administrator confirmation
- Employee acknowledgment
- Completed form
- Credit memo
- Revised invoice
- Case note
- Archived communication

Do not close the workflow based only on intent.

---

# Dynamic Reassessment Standard

Reassess conclusions when new information appears.

Potential triggers include:

- Employee provides new documentation
- Carrier changes eligibility status
- Payroll data changes
- New qualifying event information appears
- Leave dates change
- Claim determination changes
- Plan document changes
- Renewal changes benefits
- New regulatory guidance applies
- Effective date changes

HR Benefits decisions are often dynamic.

The Skill should identify what events require reassessment.

---

# Assumption Visibility Standard

Every material assumption should be visible.

Examples:

```text
Assumption:
Employee is classified as full-time.

Source:
HRIS record provided.

Confidence:
High.
```

or:

```text
Assumption:
Coverage terminates at the end of the month.

Source:
No governing plan rule was supplied.

Confidence:
Low.

Required Action:
Confirm plan termination rule before communicating to employee.
```

Do not bury material assumptions inside narrative text.

---

# Confidence Standard

Where confidence scoring is useful, consider:

- Source completeness
- Source authority
- Date consistency
- Eligibility certainty
- Plan-rule clarity
- Data consistency
- Regulatory certainty
- Human confirmation

Recommended classifications:

### High Confidence

Current authoritative information strongly supports the conclusion.

### Moderate Confidence

Useful conclusion, but one or more meaningful variables remain unresolved.

### Low Confidence

Material uncertainty exists.

### Human Determination Required

The issue should not be resolved by AI.

---

# Calculation Integrity Standard

HR Benefits calculations may include:

- Premium
- Employee contribution
- Employer contribution
- HSA funding
- Leave balance
- Payroll deductions
- Enrollment percentages
- ROI
- Savings
- Recovered dollars

Every material calculation should identify:

1. Inputs
2. Time period
3. Formula or method
4. Assumptions
5. Rounding
6. Result
7. Verification status

---

# No False Precision Standard

Avoid:

```text
$17,428.63 annual savings
```

when the calculation is based on rough assumptions.

Prefer:

```text
Estimated annual savings: approximately $17,400
```

and state the assumptions.

---

# Metrics Integrity Standard

Distinguish:

### Measured

Directly observed.

### Calculated

Derived from verified source data.

### Estimated

Derived from assumptions.

### Projected

Future-looking.

Example:

Do not present:

> Projected 15 hours saved per month

as:

> 15 hours saved per month.

---

# Benefits ROI Standard

When reporting ROI, separate:

### Financial Recovery

Actual recovered or credited dollars.

### Avoided Cost

Documented future cost prevented.

### Estimated Savings

Reasonable modeled savings.

### Time Savings

Measured or estimated staff time reduced.

### Strategic Capacity

Time redirected to higher-value work.

This prevents exaggerated ROI claims.

---

# Employee Experience Standard

Efficiency should not come at the expense of employee experience.

When relevant, evaluate:

- Clarity
- Response time
- Empathy
- Accessibility
- Consistency
- Actionability
- Escalation path

A fast incorrect answer is not an operational improvement.

---

# Decision Conversion Standard

When a Skill identifies a material issue, convert it into an actionable decision structure.

Recommended format:

| Decision | Decision Owner | Evidence | Recommendation | Trade-Off | Deadline | Next Workflow |
|---|---|---|---|---|---|---|
| [Decision] | [Owner] | [Evidence] | [Action] | [Trade-Off] | [Date] | [Workflow] |

Do not stop at:

> There may be an issue.

Translate it into:

> What needs to be decided, by whom, using what evidence, and what happens afterward?

---

# Internal vs. Employee-Facing Boundary Standard

Internal output may contain:

- Compliance concerns
- Data conflicts
- Financial exposure
- Operational errors
- Internal ownership
- Escalation notes
- Process weaknesses

Employee-facing communication should contain only what is appropriate and necessary for the employee.

Do not expose:

- Internal blame
- Financial leakage
- HR process failures
- Internal legal concerns
- Internal risk scoring
- Unverified speculation

unless there is a legitimate reason and human approval.

---

# Tone Standard

HR Benefits Skills should use language that is:

- Professional
- Clear
- Respectful
- Supportive
- Calm
- Direct
- Action-oriented

Avoid:

- Fear-based language
- Legal-sounding threats
- Overly casual treatment of sensitive topics
- Patronizing language
- Unsupported certainty
- Blame
- Excessive jargon

---

# Employee Vulnerability Standard

Extra care should be used when the employee may be dealing with:

- Serious illness
- Family illness
- Disability
- Leave
- Claim denial
- Loss of coverage
- Termination
- Financial hardship
- Death
- Dependent loss
- Significant medical treatment

The communication should remain factual while recognizing that the employee may be under stress.

Do not sacrifice accuracy for reassurance.

---

# Auditability Standard

Material HR Benefits workflows should preserve enough information to reconstruct:

```text
What happened?
What information was available?
What rule was applied?
Who reviewed it?
What decision was made?
Who approved it?
What action occurred?
When did it occur?
What evidence confirms completion?
```

This is especially important for:

- Eligibility
- Reconciliation
- COBRA
- HSA
- Leave
- Claims
- Payroll corrections
- Employee communications

---

# Recommended Audit Record

```text
Case / Transaction ID:
[ID]

Employee Identifier:
[ANONYMIZED WHERE POSSIBLE]

Workflow:
[TYPE]

Source Documents:
[LIST]

Relevant Dates:
[LIST]

Initial Finding:
[FINDING]

Assumptions:
[LIST]

Human Reviewer:
[ROLE]

Decision:
[DECISION]

Action Taken:
[ACTION]

System Updated:
[SYSTEM]

Completion Evidence:
[EVIDENCE]

Closed Date:
[DATE]
```

---

# AI Teammate Boundary Standard

AI Teammates operating under this profile may:

- Extract
- Compare
- Classify
- Calculate
- Summarize
- Draft
- Detect discrepancies
- Create checklists
- Create timelines
- Recommend follow-up
- Prepare communications
- Track workflow state
- Identify missing information
- Prepare decision support

They should not independently:

- Make legal determinations
- Decide employee eligibility where material ambiguity exists
- Terminate employee coverage
- Change payroll without authorization
- Approve or deny leave
- Make final claims determinations
- Override plan administrators
- Issue binding compliance decisions
- Send high-impact communications without required approval

---

# Agentic Automation Standard

When an AI Teammate is permitted to execute actions across systems, define:

1. Trigger
2. Authorized systems
3. Allowed actions
4. Required inputs
5. Validation rules
6. Human approval gate
7. Write-back destination
8. Confirmation requirement
9. Exception path
10. Audit record
11. Completion criteria

Example:

```text
Trigger:
HRIS termination event

AI Action:
Prepare benefits termination workflow

Validation:
Confirm employee, termination date, plan enrollment, and applicable plan rule

Human Approval:
Benefits Administrator

Execution:
Submit carrier termination

Write-Back:
AMS / Benefits Administration / HRIS case note

Confirmation:
Carrier acknowledgment required

Completion:
Carrier reflects correct termination date and billing is reconciled
```

---

# High-Risk Automation Rule

Do not fully automate irreversible or high-impact employee actions unless:

- The action is clearly authorized
- Source data is validated
- System permissions are appropriate
- Human approval requirements are satisfied
- Auditability is preserved
- Exception handling exists

---

# Failure Conditions

An HR Benefits Skill should fail or escalate rather than proceed when:

- Sensitive data is unnecessarily exposed
- Governing documentation is materially incomplete
- Eligibility is ambiguous
- Dates conflict materially
- Employee identity is uncertain
- Plan rules are unclear
- Legal interpretation is required
- Required human approval is missing
- Financial calculations cannot be reconciled
- Carrier records conflict with internal records
- Employee intent is unknown
- Output would create an unsupported employee-impacting decision
- System-of-record authority is unclear
- The requested action exceeds the Skill's authority

---

# Quality Control Checklist

Every HR Benefits Skill should incorporate the relevant controls below.

## Data

- [ ] Minimum necessary data used
- [ ] Sensitive employee information protected
- [ ] Personal identifiers removed where possible
- [ ] Source systems identified
- [ ] Conflicting records flagged

## Documents

- [ ] Governing document identified
- [ ] Document version / effective period confirmed where relevant
- [ ] Amendments considered
- [ ] Missing material documentation disclosed

## Dates

- [ ] Effective dates identified
- [ ] Source of material dates identified
- [ ] Conflicting dates resolved or escalated
- [ ] Deadlines not invented

## Eligibility

- [ ] Applicable eligibility rule identified
- [ ] Employee intent not inferred
- [ ] Ambiguous cases escalated
- [ ] Human authority preserved

## Calculations

- [ ] Source values identified
- [ ] Formula / methodology verified
- [ ] Time periods aligned
- [ ] Estimated vs. actual clearly labeled
- [ ] Double counting avoided

## Communications

- [ ] Plain language used
- [ ] Employee action clearly stated
- [ ] Deadlines included where applicable
- [ ] Appropriate empathy used
- [ ] Sensitive communication reviewed

## Workflow

- [ ] Current state identified
- [ ] Owner assigned
- [ ] Handoff defined
- [ ] System of record identified
- [ ] Completion criteria defined
- [ ] Completion evidence required where appropriate

## Governance

- [ ] Human review level appropriate
- [ ] Legal / compliance issues escalated
- [ ] AI authority boundaries preserved
- [ ] Audit trail maintained
- [ ] Irreversible actions require approval

---

# Recommended Skill Metadata

HR Benefits Skills should include metadata that identifies this domain profile.

Example:

```yaml
---
name: example-skill
title: Example HR Benefits Skill
collection: hr-benefits-ai-advantage-system-foundational-skills
system: hr-benefits-ai-advantage-system
skill_tier: foundational
source_prompt: 1.1
category: plan-documents-compliance
capability: compliance-intelligence
primary_role: benefits-compliance-specialist
secondary_roles:
  - benefits-manager
  - hr-manager
template_version: 2.2
domain_profile: hr-benefits
domain_profile_version: 1.0
version: 1.0.0
maintainer: Apeironix
license: Apache-2.0
status: public
---
```

Signature Skills should use:

```yaml
skill_tier: signature
signature_skill_number: 1
domain_profile: hr-benefits
domain_profile_version: 1.0
```

---

# Recommended Skill Declaration

Each HR Benefits Skill may include:

```markdown
## HR Benefits Domain Profile

This Skill operates under the **Apeironix HR Benefits Skill Profile** in addition to the Apeironix Gold Standard Skill Template.

Applicable domain controls include:

- Sensitive Data Boundary
- Minimum Necessary Data
- Governing Document Authority
- Effective-Date Integrity
- Eligibility Integrity
- Human Review Escalation
- Employee Communication
- Workflow Ownership
- System-of-Record Integrity
- Auditability

Where the Skill conflicts with an applicable governing document, regulatory requirement, or authorized human determination, the governing authority controls.
```

This allows individual Skills to inherit the profile without reproducing the entire document.

---

# Profile Inheritance Model

The intended architecture is:

```text
Gold Standard v2.2+
        ↓
Universal Skill Controls
        ↓
HR Benefits Skill Profile
        ↓
HR Benefits Domain Controls
        ↓
Specific SKILL.md
        ↓
Workflow-Specific Logic
```

For example:

```text
Gold Standard
        +
HR Benefits Profile
        +
HSA Contribution Reconciliation Skill
        =
Controlled HSA Reconciliation Capability
```

or:

```text
Gold Standard
        +
HR Benefits Profile
        +
FMLA / Leave Tracking Skill
        =
Controlled Leave Administration Capability
```

---

# Profile Application Rules

Do not copy every section of this profile into every Skill.

Instead:

### Apply

Include the standards that materially affect the workflow.

### Reference

Reference the shared profile for universal HR Benefits safeguards.

### Specialize

Add stricter controls where the specific workflow requires them.

### Do Not Weaken

A Skill may add stronger safeguards.

It should not weaken the applicable profile controls without explicit governance approval.

---

# Example — Reconciliation Skill

A reconciliation Skill should strongly apply:

- Sensitive Data Boundary
- Minimum Necessary Data
- System-of-Record Standard
- Reconciliation Match Standard
- Financial Impact Standard
- Recovery Integrity
- Transaction Lineage
- Calculation Integrity
- Completion Evidence
- Ownership
- Handoff Integrity

It may only lightly apply:

- Multilingual Communication
- Leave Management Boundary

---

# Example — Leave Skill

A leave Skill should strongly apply:

- Sensitive Data Boundary
- Medical Information Minimization
- Leave Management Boundary
- Effective-Date Integrity
- Regulatory Currency
- Neutral Narrative
- Human Review Escalation
- Employee Communication
- Auditability

It may only lightly apply:

- Financial Recovery
- Reconciliation Match

---

# Example — Employee Communication Skill

An employee communication Skill should strongly apply:

- Employee Communication Standard
- Plain-Language Translation
- Employee Action Standard
- Communication Approval
- Multilingual Standard
- Governing Document Standard
- Internal vs. Employee-Facing Boundary
- Sensitive Data Boundary

---

# Example — Benefits Strategy Skill

A strategy Skill should strongly apply:

- Data Integrity
- Metrics Integrity
- Benefits ROI Standard
- Assumption Visibility
- Decision Conversion
- Trade-Off Transparency
- Human Accountability

---

# Profile Versioning

This profile should evolve deliberately.

Potential versioning:

```text
v1.0 — Initial HR Benefits domain profile
v1.1 — Clarifications / minor additions
v2.0 — Material architectural change
```

A Skill should identify the profile version it was designed against.

Example:

```yaml
domain_profile: hr-benefits
domain_profile_version: 1.0
```

---

# Profile Update Criteria

Update this profile only when a new standard is:

1. Broadly applicable across HR Benefits workflows
2. Material to accuracy, safety, governance, or operational execution
3. Reusable across multiple Skills
4. Better managed centrally than repeated inside individual Skills

Do not update the profile for every workflow-specific insight.

Workflow-specific rules belong in the applicable `SKILL.md`.

---

# Suggested Future Domain Extensions

Potential future extensions may include:

```text
HR-BENEFITS-COMPLIANCE-PROFILE.md
HR-BENEFITS-LEAVE-PROFILE.md
HR-BENEFITS-RECONCILIATION-PROFILE.md
HR-BENEFITS-EMPLOYEE-COMMUNICATION-PROFILE.md
```

These should only be created if the Skill library becomes complex enough that a second domain-specific layer materially improves reuse.

Avoid unnecessary template fragmentation.

---

# Responsible AI Reminder

Before using AI in an HR Benefits workflow:

```text
ANONYMIZE
      ↓
GENERALIZE
      ↓
SUMMARIZE
      ↓
REVIEW
      ↓
APPROVE
```

Ask:

> Do we need this employee information to perform the task?

If no:

> Leave it out.

Ask:

> Does AI have enough authoritative information to support this conclusion?

If no:

> Identify the missing information.

Ask:

> Could this action materially affect an employee?

If yes:

> Require the appropriate human review.

---

# Final Operating Principle

The HR Benefits AI Advantage does not come from allowing AI to make more decisions.

It comes from allowing AI to do more of the work **around** those decisions:

- Gathering
- Comparing
- Calculating
- Organizing
- Drafting
- Tracking
- Reconciling
- Flagging
- Preparing
- Documenting

so HR and Benefits professionals have more capacity for:

- Judgment
- Employee support
- Strategy
- Leadership
- Benefits design
- Risk management
- Process improvement
- Human decision-making

### Your people make the decisions. Your AI Teammates do the work.

---

# Relationship to the HR Benefits AI Advantage System

This profile governs Skills published under:

```text
hr-benefits-ai-advantage-system/
├── foundational-skills/
├── signature-skills/
└── operational-systems/
```

The broader system progression is:

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

The profile helps ensure that increased automation does not reduce:

- Accuracy
- Privacy
- Accountability
- Explainability
- Employee protection
- Human oversight

---

# About Apeironix

Apeironix develops reusable AI Skills, AI Teammates, and connected operational workflows designed around real insurance, HR, and Employee Benefits work.

The objective is to transform repeatable expertise into reusable AI capabilities while preserving the judgment and accountability of the professionals responsible for the work.

**Keep your systems. Activate an AI Workforce.**

Learn more at [Apeironix.com](https://apeironix.com).

---

# License

This profile is part of the Apeironix Skills repository and is made available under the Apache License 2.0.

See the repository `LICENSE` file for complete terms.
