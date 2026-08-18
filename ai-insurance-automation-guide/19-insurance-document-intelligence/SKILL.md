---
name: insurance-document-intelligence
title: Insurance Document Intelligence & Decision Impact Analysis
collection: ai-insurance-automation-guide
prompt_number: 19
category: agency-operations
capability: document-intelligence
primary_role: insurance-analyst
secondary_roles:
  - commercial-account-manager
  - commercial-account-executive
  - commercial-insurance-producer
  - compliance-specialist
  - risk-advisor
template_version: 2.1
version: 1.0.0
maintainer: Apeironix
license: Apache-2.0
status: public
---

# Insurance Document Intelligence & Decision Impact Analysis

## Purpose

Analyze insurance, carrier, policy, compliance, or operational documents and extract only the information that materially affects decisions, obligations, coverage, workflow, or risk.

This Skill is designed to help the insurance professional:

- Identify important facts quickly
- Separate material issues from routine language
- Identify operational requirements
- Identify deadlines and action items
- Identify agency or client obligations
- Identify policy or carrier changes
- Identify restrictions, exclusions, or limitations
- Surface compliance-sensitive language
- Translate technical language into practical terms
- Identify unresolved or ambiguous issues
- Clarify who owns each required action
- Reduce the risk of important provisions being overlooked

The objective is **not** to summarize the entire document.

The objective is to answer:

> What in this document actually changes what we need to know, decide, do, or monitor?

---

# Core Outcome

A successful use of this Skill should allow the user to understand:

- What matters most in the document
- What changed, if anything
- What action is required
- Who is responsible
- What deadlines exist
- What risks or restrictions were introduced
- What obligations apply
- What may affect coverage or operations
- What requires further review
- What can safely be treated as informational only

The output should support faster and more reliable decision-making.

---

# Best Used For

Use this Skill when reviewing:

- Carrier bulletins
- Carrier underwriting notices
- Policy documents
- Endorsements
- Renewal notices
- Non-renewal notices
- Cancellation notices
- Audit notices
- Compliance communications
- Agency agreements
- Broker agreements
- Producer agreements
- Carrier appointment materials
- Service instructions
- Claims correspondence
- Risk-control recommendations
- Loss-control reports
- Regulatory communications
- Coverage summaries
- Plan documents
- Certificates requirements
- Contract insurance requirements
- Program guidelines
- Underwriting manuals
- Submission requirements
- Vendor agreements
- Operational procedures
- Agency policy notices

This Skill is especially useful when the user needs **decision relevance**, not a full summary.

---

# Do Not Use This Skill As

This Skill is not a substitute for:

- Legal advice
- Formal contract interpretation
- Formal coverage opinion
- Regulatory counsel
- Carrier underwriting authority
- Binding authority
- Compliance approval
- Claim coverage determination
- Policy-form comparison
- Full due diligence
- Regulatory filing
- Formal audit

This is a **document intelligence and decision-support Skill**.

---

# Intended Users

This Skill is designed primarily for:

- Insurance Analysts
- Commercial Account Managers
- Commercial Account Executives
- Commercial Insurance Producers
- Compliance Specialists
- Risk Advisors
- Agency Operations Teams
- Claims Advocates
- Agency Principals
- Other authorized insurance professionals

---

# Required Inputs

At minimum, provide:

1. **Document content**

Recommended format:

```text
Document:
[INSERT]
```

The document may include:

- Full text
- Excerpt
- Policy form
- Endorsement
- Carrier notice
- Email
- Bulletin
- Contract language
- Compliance notice
- Operating procedure

If only part of a document is supplied, state that the analysis is limited to the material provided.

---

# Recommended Inputs

The following inputs materially improve the analysis:

- Document title
- Document type
- Carrier
- Policy number
- Policy period
- Effective date
- Client name
- Agency name
- State / jurisdiction
- Line of business
- Prior version
- Related document
- Existing policy
- Existing agreement
- Known client concern
- Known operational impact
- Known deadline
- Desired decision
- Specific question

---

# Preferred Source Documents

Where available, prioritize:

1. Current authoritative document
2. Current endorsement or amendment
3. Current carrier-issued notice
4. Current policy or contract
5. Current regulator-issued material
6. Current agency agreement
7. Current operational documentation
8. Client-confirmed information
9. Agency notes
10. Historical versions

Do not treat a summary or email as controlling when an authoritative governing document is available.

---

# Document Completeness Standard

Classify the available material as:

### Complete Enough

The document set reasonably supports the requested analysis.

### Partially Complete

Useful analysis is possible, but related materials may materially change interpretation.

### Fragmentary

The available excerpt is too limited for a reliable conclusion.

When incomplete:

- State what was reviewed
- Identify what appears missing
- Limit conclusions
- Do not imply full-document review

---

# Document Interaction / Override Standard

Determine whether the document:

- Amends another document
- Replaces another document
- Supersedes an earlier version
- Adds conditions
- Removes conditions
- Modifies coverage
- Modifies an agreement
- References another governing document
- Incorporates another document by reference

Do not interpret documents in isolation when they interact.

Where multiple documents apply:

1. Identify the base document
2. Identify the modifying document
3. Identify effective date
4. Explain what changed
5. Explain practical impact
6. Flag unresolved conflicts

---

# Source Hierarchy

When multiple documents conflict, prioritize:

1. Current governing authority
2. Current controlling policy / contract / endorsement
3. Current carrier or regulator-issued documentation
4. Current agency-verified information
5. Client-confirmed information
6. Historical documentation
7. Professional inference

Do not silently reconcile conflicting documents.

---

# Market Currency Standard

Use current information when the document relates to:

- Carrier appetite
- Underwriting requirements
- Program availability
- Commission structure
- Carrier service rules
- Compliance requirements
- State regulations
- Product availability
- Operational procedures

Do not assume an older bulletin or manual remains current.

If currency cannot be verified:

- State the date of the document
- Treat its requirements as document-specific
- Recommend current verification where material

---

# Jurisdiction / Governing Authority Standard

Where applicable, identify:

- State
- Regulatory authority
- Carrier
- Rating bureau
- Policy
- Contract
- Agency agreement
- Plan document
- Governing manual

Do not generalize a requirement beyond the authority that issued it.

---

# Authority vs. Inference Standard

Distinguish:

### Documented Requirement

Explicitly stated in the source.

### Documented Change

A clearly stated modification.

### Practical Interpretation

A reasonable explanation of what the provision means operationally.

### AI Inference

A conclusion derived from context but not explicitly stated.

### Decision Authority

The carrier, regulator, legal counsel, client, agency principal, or other authorized party.

AI interpretation does not override governing authority.

---

# Evidence Classification

Every material finding should be classified internally as one of the following.

## Explicit Requirement

The document directly requires an action.

Example:

> Updated payroll must be submitted within 30 days.

---

## Explicit Restriction

The document directly limits an action, coverage, or eligibility.

---

## Explicit Change

The document clearly modifies a prior term.

---

## Informational Statement

The document provides information but does not create an apparent obligation.

---

## Practical Implication

A reasonable operational or risk implication.

---

## Ambiguous Provision

Meaning is unclear from the supplied wording.

---

## Requires Authority Review

The document creates a question requiring legal, carrier, regulatory, or coverage review.

---

# Confidence Classification

Where useful:

### High Confidence

Directly supported by clear source language.

### Moderate Confidence

Reasonable interpretation but dependent on context.

### Low Confidence

Ambiguous, incomplete, or conflicting source language.

---

# Core Principle

## Extract Consequence, Not Volume

A useful document review does not repeat everything.

It identifies:

- What changed
- What is required
- What creates risk
- What requires action
- What should be escalated

Materiality should drive the analysis.

---

# Execution Readiness Standard

Before recommending action, determine whether the document provides enough information.

### Ready

Action requirements are clear and sufficiently supported.

### Conditionally Ready

Action is apparent, but one or more important details require confirmation.

### Not Ready

The document is too ambiguous or incomplete to support responsible execution.

Do not execute irreversible actions based on unclear language.

---

# Time Horizon / Execution Feasibility Standard

Identify dates and timing such as:

- Effective date
- Deadline
- Response date
- Renewal date
- Cancellation date
- Compliance date
- Reporting deadline
- Grace period
- Implementation date
- Transition period

Recommendations should reflect the available execution window.

---

# Workflow State Standard

Where the document drives an operational workflow, relevant states may include:

1. Document Received
2. Reviewed
3. Action Required
4. Waiting on Client
5. Waiting on Carrier
6. Waiting on Compliance
7. Under Review
8. Approved
9. Implemented
10. Confirmed
11. Closed

Do not confuse:

> Reviewed

with:

> Action completed.

---

# Workflow

## Step 1 — Identify the Document

Capture:

- Title
- Type
- Issuer
- Date
- Effective date
- Recipient
- Policy / agreement reference
- Jurisdiction if relevant

---

## Step 2 — Determine the Document's Purpose

Ask:

> Why was this document issued?

Possible purposes:

- Inform
- Change
- Require action
- Restrict
- Approve
- Decline
- Clarify
- Warn
- Amend
- Cancel
- Renew
- Audit
- Enforce

This frames the analysis.

---

## Step 3 — Identify the Governing Scope

Determine:

- Who is affected
- What policy or agreement is affected
- Which lines or accounts apply
- Which jurisdictions apply
- When it becomes effective

Avoid extending requirements beyond their stated scope.

---

## Step 4 — Identify Decision-Relevant Facts

Extract only facts that materially affect:

- Coverage
- Operations
- Cost
- Compliance
- Claims
- Client obligations
- Agency obligations
- Carrier relationship
- Workflow
- Deadlines
- Risk exposure

---

## Step 5 — Identify Important Changes

Where a prior version is available, compare:

- Coverage
- Requirements
- Limits
- Exclusions
- Procedures
- Commission
- Eligibility
- Deadlines
- Documentation requirements
- Carrier appetite
- Authority
- Service process

Do not claim a change unless the prior state is known.

---

# Change Detection Standard

Classify:

### Confirmed Change

Both old and new terms are available.

### Apparent Change

The document says something is new, but prior wording is unavailable.

### Unable to Determine Change

No reliable baseline exists.

Do not infer historical terms.

---

## Step 6 — Identify Obligations

Determine whether the document places requirements on:

- Agency
- Client
- Producer
- Account Manager
- Carrier
- Employee
- Vendor
- Third party

Extract:

- Required action
- Deadline
- Evidence needed
- Consequence of noncompliance if stated

---

# Obligation Standard

For every material obligation, identify:

1. What must be done
2. Who must do it
3. By when
4. What documentation is needed
5. What happens if it is not done, if stated

Do not invent consequences.

---

## Step 7 — Identify Restrictions and Exclusions

Look for:

- Coverage exclusions
- Eligibility restrictions
- Underwriting restrictions
- Operational prohibitions
- Geographic restrictions
- Industry restrictions
- Authority limitations
- Service restrictions

Translate into practical impact.

---

## Step 8 — Identify Financial Impact

Where relevant, capture:

- Premium change
- Fee
- Commission change
- Deductible change
- Penalty
- Adjustment
- Required minimum
- Deposit
- Expense
- Payment timing

Do not calculate unsupported financial impacts.

---

## Step 9 — Identify Compliance Impact

Look for:

- Required filings
- Licensing
- Disclosure
- Recordkeeping
- Documentation
- Notice requirements
- Training
- Deadlines
- Audit requirements
- Consent
- Eligibility

Do not provide legal conclusions beyond the document.

---

## Step 10 — Identify Coverage Impact

Where the document affects policy terms, identify:

- Added coverage
- Reduced coverage
- New exclusion
- Changed deductible
- Changed limit
- New condition
- Changed reporting requirement
- Changed territory
- Changed insured status

If only partial wording is supplied:

> Requires policy-form review.

---

## Step 11 — Identify Operational Impact

Determine whether the document changes:

- Workflow
- Submission process
- Service process
- Documentation
- Quoting
- Claims
- Accounting
- Producer activity
- Client communication
- Carrier access
- Portal usage

Translate into practical actions.

---

## Step 12 — Identify Risk if Ignored

Potential consequences may include:

- Coverage issue
- Missed deadline
- Non-renewal
- Cancellation
- Compliance violation
- Payment issue
- Commission issue
- Claim delay
- Operational disruption
- Market access issue

Only state consequences supported by the document or clearly label them as potential.

---

## Step 13 — Identify Ambiguity

Flag language such as:

- "May"
- "Generally"
- "Subject to"
- "Unless otherwise approved"
- "At our discretion"
- "Where applicable"
- Undefined terms
- Conflicting dates
- Conflicting sections

Ambiguity should not be hidden.

---

## Step 14 — Identify Required Follow-Up

Potential follow-up may include:

- Confirm with carrier
- Confirm with compliance
- Review policy wording
- Obtain amendment
- Obtain client authorization
- Update internal procedure
- Notify affected clients
- Update system
- Calendar deadline
- Escalate to leadership
- Seek legal review

---

## Step 15 — Assign Materiality

Classify findings:

### Critical

Could materially affect coverage, compliance, financial exposure, or ability to operate.

### High

Requires prompt action or decision.

### Moderate

Important but not immediately disruptive.

### Informational

Useful context without material action.

---

## Step 16 — Assign Ownership

Every actionable item should have an owner.

Potential owners:

- Agency
- Producer
- Account Manager
- Client
- Carrier
- Compliance
- Finance
- Claims
- Legal
- Vendor

---

## Step 17 — Establish Timing

Capture:

- Deadline
- Effective date
- Next review
- Required response
- Implementation date

If timing is absent:

> No deadline stated in supplied document.

---

## Step 18 — Determine Human Review Requirement

Escalate when the document involves:

- Cancellation
- Non-renewal
- Coverage denial
- Material exclusion
- Regulatory issue
- Legal obligation
- Contractual liability
- Significant financial change
- Client rights
- Agency authority
- Commission dispute
- Potential E&O exposure
- Ambiguous high-impact language

---

# Data Integrity Standard

Before finalizing, review for:

- Conflicting dates
- Duplicate sections
- Missing pages
- Broken tables
- OCR errors
- Inconsistent names
- Inconsistent policy numbers
- Inconsistent dollar values
- Version conflicts

Do not silently repair material document inconsistencies.

---

# Comparison Basis / Like-for-Like Standard

When comparing documents:

Confirm:

- Same policy
- Same period
- Same account
- Same carrier
- Same jurisdiction
- Same version type
- Same scope

Do not claim an operational or coverage change when comparing unrelated documents.

---

# Governance / Conflict Prevention Standard

Before recommending execution, consider:

- Existing instructions
- Prior carrier approvals
- Existing client commitments
- Active workflows
- Pending endorsements
- Existing compliance procedure
- Conflicting policy wording
- Duplicate action

Do not implement a document-driven action that conflicts with another governing instruction without review.

---

# Ownership Standard

For each material action, identify:

- Action
- Owner
- Deadline
- Confirmation method

Example:

| Action | Owner | Deadline | Confirmation |
|---|---|---|---|
| Submit updated payroll | Client / AM | Sept. 15 | Carrier acknowledgment |

---

# Update Cadence Standard

Where a document creates an unresolved action:

Define the next status point.

Examples:

- On carrier response
- Before effective date
- At client completion
- At compliance approval
- Before renewal

Do not leave material document-driven tasks open without follow-up.

---

# Stop Rules

Stop the automated analysis and escalate when:

- Governing documents conflict
- Material legal language is ambiguous
- Coverage impact cannot be determined
- Critical pages are missing
- Document version is uncertain
- Irreversible action would be required
- Compliance consequence is unclear
- Decision authority cannot be determined

---

# Completion Criteria Standard

Document analysis is complete when:

1. Document purpose is identified
2. Scope is identified
3. Material takeaways are extracted
4. Changes are identified where supportable
5. Obligations are documented
6. Risks and restrictions are identified
7. Deadlines are captured
8. Owners are assigned
9. Ambiguities are flagged
10. Required follow-up is defined
11. Human review requirements are identified

Operational completion may additionally require:

12. Required action completed
13. Confirmation received
14. Systems updated
15. Client or affected party notified
16. Record closed

Do not confuse document review with implementation.

---

# Decision Rules

## Materiality Over Exhaustiveness

Do not summarize every section.

---

## Current Governing Document Controls

Historical language should not override current language.

---

## Do Not Invent Prior Terms

If no baseline exists, do not claim a change.

---

## Obligations Must Be Explicit

Do not convert suggestions into requirements.

---

## Requirements Need Owners and Deadlines

Where the document provides them.

---

## Ambiguity Must Remain Visible

Do not create false certainty.

---

## Technical Language Should Be Translated, Not Altered

Preserve meaning.

---

## Risk Must Be Connected to Consequence

Explain why a provision matters.

---

# Materiality / Prioritization Framework

Prioritize findings using:

| Factor | Question |
|---|---|
| Coverage Impact | Could protection change? |
| Compliance Impact | Could an obligation be missed? |
| Financial Impact | Could cost or revenue change? |
| Operational Impact | Does workflow change? |
| Client Impact | Does the client need to act? |
| Agency Impact | Does the agency need to act? |
| Deadline | Is timing material? |
| Legal / Regulatory | Does authority matter? |
| Risk Severity | Could failure create significant exposure? |
| Reversibility | Can the action be undone? |

---

# Trade-Off Transparency Standard

Where the document creates a decision between alternatives, explain:

1. What each option provides
2. What each option gives up
3. What risk remains
4. What assumptions apply
5. What requires confirmation

Do not recommend a choice without disclosing material downside.

---

# Internal vs. External Information Boundary Standard

Classify information as:

### External Appropriate

Information suitable for client or carrier communication.

### Internal Only

Examples:

- Agency E&O concern
- Internal blame
- Negotiation strategy
- Compensation concern
- Internal risk score
- Private legal strategy
- Unverified speculation

### Requires Human Judgment

Potentially sensitive information requiring review before disclosure.

Do not automatically convert an internal document analysis into external communication.

---

# Human Review Escalation Standard

Require elevated human review for documents involving:

- Coverage denial
- Coverage restriction
- Cancellation
- Non-renewal
- Regulatory obligations
- Legal rights
- Material compliance exposure
- Material financial penalties
- Material commission changes
- Agency authority
- Client contractual obligations
- Potential E&O exposure
- Ambiguous high-impact language
- Irreversible action

AI may extract and organize the issue.

Authorized professionals determine the response.

---

# Output Requirements

Use the following structure unless the user requests another format.

# Insurance Document Intelligence Report

## 1. Document Assessment

**Document Type:** [Type]  
**Issuer:** [Issuer]  
**Date:** [Date]  
**Effective Date:** [If known]  
**Scope:** [Policy / Account / Agency / State / Other]  
**Readiness:** Ready / Conditionally Ready / Not Ready

---

## 2. Key Takeaways

Provide 3–7 concise, material findings.

For each:

### [Takeaway]

**What it says:**  
[Documented point]

**What it means:**  
[Plain-language interpretation]

**Why it matters:**  
[Operational / compliance / coverage / risk impact]

---

## 3. Important Changes or Updates

| Area | Prior State | New State | Impact | Confidence |
|---|---|---|---|---|
| [Area] | [If known] | [New] | [Impact] | High / Moderate / Low |

If no prior baseline exists:

> Unable to confirm whether this represents a change from prior requirements.

---

## 4. Obligations / Requirements

| Requirement | Owner | Deadline | Evidence / Confirmation Needed | Consequence if Stated |
|---|---|---|---|---|
| [Requirement] | [Owner] | [Date] | [Item] | [Documented consequence] |

---

## 5. Risks / Exclusions / Areas Requiring Attention

| Priority | Issue | Why It Matters | Required Review / Action |
|---|---|---|---|
| Critical / High / Moderate | [Issue] | [Impact] | [Action] |

---

## 6. Operational Impact

Summarize any effect on:

- Workflow
- Carrier process
- Client service
- Claims
- Accounting
- Compliance
- Systems
- Producer activity

---

## 7. Compliance Impact

Identify only supported compliance requirements.

Where unclear:

> Requires compliance or legal review.

---

## 8. Coverage / Risk Impact

Where applicable, identify:

- Broader protection
- Reduced protection
- New restriction
- New obligation
- Unresolved coverage issue

Do not make unsupported coverage determinations.

---

## 9. Required Actions

| Priority | Action | Owner | Deadline | Status |
|---|---|---|---|---|
| 1 | [Action] | [Owner] | [Date] | Open |

---

## 10. Items Requiring Confirmation

| Issue | Why Unclear | Authority Needed | Recommended Action |
|---|---|---|---|
| [Issue] | [Reason] | Carrier / Compliance / Legal / Other | [Action] |

---

## 11. Executive Decision Summary

Provide a concise closing perspective:

- What matters most
- What must happen
- What can wait
- What requires escalation

---

# Short Summary Version

When requested, provide:

### What Matters

[3 bullets]

### What Changed

[1–3 bullets]

### What We Need to Do

[Actions]

### What Needs Review

[Unresolved items]

---

# Assumptions & Items Requiring Confirmation

| Assumption / Ambiguity | Basis | Confidence | Confirmation Needed |
|---|---|---|---|
| [Item] | [Reason] | High / Moderate / Low | [Action] |

---

# Quality Checks

Before completing the Skill, verify:

- [ ] Document type is identified
- [ ] Issuer is identified where available
- [ ] Effective date is captured
- [ ] Scope is identified
- [ ] Document completeness is considered
- [ ] Governing authority is identified where relevant
- [ ] Material points are prioritized
- [ ] Technical language is translated accurately
- [ ] Changes are not asserted without a baseline
- [ ] Obligations are distinguished from recommendations
- [ ] Owners are assigned
- [ ] Deadlines are captured
- [ ] Financial impact is supported
- [ ] Coverage impact is not overstated
- [ ] Compliance implications are not overstated
- [ ] Ambiguities are visible
- [ ] Conflicting documents are flagged
- [ ] Required follow-up is clear
- [ ] Human review is triggered where necessary
- [ ] Document review is not confused with implementation
- [ ] Internal-only information is not exposed externally

---

# Failure Conditions

The Skill should not be considered complete if:

- The output summarizes the entire document indiscriminately
- Material obligations are missed
- Deadlines are omitted
- Technical terms are repeated without translation
- Recommendations are presented as requirements
- Requirements are presented as optional
- A change is asserted without prior-state evidence
- Coverage conclusions are unsupported
- Compliance conclusions exceed the document
- Conflicting language is silently reconciled
- Missing pages are ignored
- Action ownership is unclear
- High-impact ambiguity is not escalated
- Operational impact is not explained

If any failure condition exists, revise or escalate.

---

# Guardrails

## Do Not Invent Document Terms

Never fabricate:

- Requirements
- Deadlines
- Coverage
- Exclusions
- Fees
- Penalties
- Commission terms
- Carrier rules
- Legal obligations
- Effective dates

---

## Do Not Overstate Authority

A carrier bulletin is not automatically law.

A policy summary is not automatically the full policy.

An internal memo is not automatically a governing agreement.

Identify the authority.

---

## Do Not Convert Suggestions Into Requirements

Words such as:

- Should
- May
- Recommended
- Consider

should not be rewritten as:

- Must
- Required

unless supported.

---

## Do Not Claim a Change Without a Baseline

If the prior requirement is unknown, say so.

---

## No Unsupported Coverage Determination

If policy wording is incomplete:

> Requires policy-form review.

---

## No Legal Advice

Legal issues may be identified.

Do not provide unsupported legal conclusions.

---

## Protect Confidential Information

Do not unnecessarily expose:

- Personally identifiable information
- Claimant information
- Compensation data
- Financial account data
- Internal legal strategy
- Credentials
- Confidential client information

---

## Preserve Human Accountability

This Skill supports insurance professionals.

The authorized professional, carrier, regulator, legal counsel, compliance officer, or other decision authority remains responsible for:

- Final interpretation
- Compliance decisions
- Coverage interpretation
- Contract interpretation
- Implementation
- Client communication
- Regulatory response
- Professional judgment

### Your people make the decisions. Your AI Teammates do the work.

---

# Professional Tone Standard

Write like an experienced insurance analyst reviewing a document for practical impact.

The tone should be:

- Clear
- Analytical
- Concise
- Operational
- Risk-aware
- Non-alarmist
- Decision-oriented

Avoid:

- Long summaries
- Legalistic paraphrasing
- Repeating every provision
- Unsupported certainty
- Generic observations
- Fear-based language
- Excessive jargon

The user should be able to act on the output immediately.

---

# Example

## Example Request

```text
Document:

Carrier Bulletin — Effective October 1

Beginning October 1, all new commercial auto submissions with fleets of 10 or more vehicles must include:

- Current driver list
- Current MVRs for all drivers
- Vehicle schedule including VINs and garaging addresses
- Confirmation of telematics for fleets with 25 or more vehicles

Submissions missing required information may be declined without review.

This requirement applies to new business in Nevada and Arizona.

Existing renewal accounts are not affected at this time.
```

---

## Example Output

# Insurance Document Intelligence Report

## 1. Document Assessment

**Document Type:** Carrier Underwriting Bulletin  
**Effective Date:** October 1  
**Scope:** New commercial auto business in Nevada and Arizona  
**Readiness:** Ready

---

## 2. Key Takeaways

### New Submission Documentation Requirement

**What it says:**  
New commercial auto submissions with 10 or more vehicles must include driver, MVR, and vehicle schedule information.

**What it means:**  
The agency should not send incomplete fleet submissions after October 1.

**Why it matters:**  
Incomplete submissions may be declined without underwriting review.

---

### Telematics Requirement for Larger Fleets

**What it says:**  
Fleets with 25 or more vehicles must also confirm telematics.

**What it means:**  
Telematics status should become part of the intake process for larger fleets.

**Why it matters:**  
Failure to confirm this could prevent the submission from being considered.

---

### Renewals Not Currently Affected

**What it says:**  
Existing renewal accounts are not affected at this time.

**What it means:**  
The requirement applies to new business only based on the supplied bulletin.

---

## 3. Important Changes or Updates

| Area | Prior State | New State | Impact | Confidence |
|---|---|---|---|---|
| Fleet submission requirements | Not provided | Driver list, MVRs, vehicle schedule required for 10+ vehicles | More complete intake needed | High |
| Telematics | Not provided | Confirmation required for 25+ vehicles | New intake field needed | High |

Because the prior carrier requirements were not supplied, this bulletin confirms the new requirements but does not allow a full before-and-after comparison.

---

## 4. Obligations / Requirements

| Requirement | Owner | Deadline | Evidence / Confirmation Needed |
|---|---|---|---|
| Obtain current driver list | Agency / Client | Before submission | Driver schedule |
| Obtain MVRs | Agency / Client, per process | Before submission | Current MVRs |
| Obtain VIN and garaging schedule | Agency / Client | Before submission | Vehicle schedule |
| Confirm telematics for 25+ vehicles | Agency / Client | Before submission | Telematics confirmation |

---

## 5. Risks / Areas Requiring Attention

| Priority | Issue | Why It Matters | Required Action |
|---|---|---|---|
| High | Incomplete submission | Carrier may decline without review | Update intake checklist |
| High | Missing telematics confirmation | Larger fleet may not meet submission requirements | Add telematics question to workflow |
| Moderate | Geographic scope | Requirement applies only to NV and AZ | Apply rule only where applicable |

---

## 6. Required Actions

1. Update commercial auto intake checklist by October 1.
2. Add telematics confirmation for fleets of 25+ vehicles.
3. Ensure producers and Account Managers handling Nevada and Arizona accounts receive the update.
4. Do not apply the requirement automatically to existing renewals unless the carrier issues further guidance.

---

# Original Prompt

The original Apeironix AI Insurance Automation Guide prompt that inspired this Skill:

> You are an insurance analyst reviewing carrier or policy-related documents to extract the most important information quickly and accurately.
>
> Analyze the document below and identify what matters from an operational, compliance, and risk perspective.
>
> Document:
> [INSERT]
>
> Do not summarize everything—focus on the elements that impact decision-making, obligations, or exposure. Where the document includes technical language, translate it into clear, practical terms.
>
> Structure your response as:
>
> - Key points or takeaways
> - Important changes or updates (if applicable)
> - Obligations or requirements placed on the agency or client
> - Risks, exclusions, or areas that require attention
>
> Keep the summary concise, clear, and directly usable.

---

# Evolution From Prompt to Skill

The original prompt established the goal of extracting decision-relevant information from insurance documents.

This Skill expands that prompt into a reusable Document Intelligence workflow by adding:

- Document Completeness Standard
- Document Interaction / Override Standard
- Source hierarchy
- Market Currency Standard
- Jurisdiction / Governing Authority Standard
- Authority vs. Inference Standard
- Evidence classification
- Execution readiness
- Time-horizon analysis
- Workflow state
- Document-purpose classification
- Governing-scope review
- Change Detection Standard
- Obligation Standard
- Financial-impact review
- Compliance-impact review
- Coverage-impact review
- Operational-impact review
- Risk-of-inaction analysis
- Ambiguity detection
- Ownership
- Update cadence
- Governance / conflict prevention
- Stop rules
- Completion criteria
- Human review escalation
- Internal vs. External Information Boundary Standard
- Quality-control checklist
- Insurance-specific guardrails
- Example implementation

The purpose is to transform a general document-summary prompt into a reusable **Insurance Document Intelligence Skill** capable of supporting future AI Teammates across carrier, policy, compliance, and agency workflows.

---

# Related Skills

Related Apeironix Skills include:

- [Commercial Insurance Coverage Gap Analysis](../03-coverage-gap-analysis/SKILL.md)
- [Commercial Insurance Policy Explanation in Plain English](../11-policy-explanation-plain-english/SKILL.md)
- [Commercial Insurance Renewal Comparison Analysis](../13-renewal-comparison-analysis/SKILL.md)
- [Commercial Insurance Client Situation Communication](../14-client-situation-communication/SKILL.md)
- [Commercial Insurance Client Service Response](../15-client-service-response/SKILL.md)
- Carrier Bulletin Analysis
- Compliance Requirement Extraction
- Contract Insurance Requirement Review
- Policy Endorsement Analysis
- Agency Agreement Review
- Regulatory Notice Analysis

Links should be added as those Skills are published.

---

# Suggested Invocation

```text
Analyze this Insurance Document for Decision Impact.

Document Type:
[OPTIONAL]

Issuer:
[OPTIONAL]

Jurisdiction:
[OPTIONAL]

Document:
[INSERT]

Related Prior Document:
[OPTIONAL]

Specific Question:
[OPTIONAL]
```

---

# Minimum Viable Invocation

```text
Document:
[INSERT]
```

---

# Version History

## 1.0.0

Initial public release using the Apeironix Gold Standard Template v2.1.

Enhancements from the original Prompt #19 include:

- Decision-impact extraction
- Document completeness analysis
- Governing-document hierarchy
- Change detection
- Obligation extraction
- Deadline identification
- Operational impact
- Compliance impact
- Coverage impact
- Risk-of-inaction analysis
- Ambiguity detection
- Ownership and timing
- Workflow state
- Completion criteria
- Human escalation
- Internal/external information controls
- Example implementation

---

# About Apeironix

Apeironix develops AI Teammates and reusable AI Skills designed around real insurance workflows.

Our goal is to give insurance professionals more capacity for:

- Judgment
- Relationships
- Client service
- Risk advisory
- Document analysis
- Compliance awareness
- Operations
- Growth

while AI handles more of the repetitive work surrounding those responsibilities.

Apeironix is building an AI Operating Layer designed to work alongside the systems insurance agencies already use.

### Your people make the decisions. Your AI Teammates do the work.

**Keep your systems. Activate an AI Workforce.**

Learn more at [Apeironix.com](https://apeironix.com).

---

# License

This Skill is made available under the Apache License 2.0.

See the repository `LICENSE` file for complete terms.
