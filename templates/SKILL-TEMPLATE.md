---
name: skill-name
title: Human-Readable Skill Title
collection: collection-name
prompt_number: 0
category: category-name
capability: capability-name
primary_role: primary-user-role
secondary_roles:
  - secondary-role
template_version: 2.1
version: 1.0.0
maintainer: Apeironix
license: Apache-2.0
status: public
---

# Apeironix Gold Standard Skill Template

## Template Version

**Apeironix Gold Standard v2.1**

This template defines the recommended structure and operating standards for public Apeironix Skills.

Not every section or module applies to every Skill.

Include the modules that materially improve:

- Accuracy
- Safety
- Execution
- Auditability
- Decision quality
- Client communication
- Human accountability
- Reusability

Do not add sections merely for completeness.

---

# Template Usage Standard

An Apeironix Skill is more than a prompt.

It should define a reusable, operationally executable capability that can be used by:

- Insurance professionals
- AI assistants
- AI agents
- AI Teammates
- Orchestrated AI Workforces

Every Apeironix Skill should be:

- Insurance-specific
- Practical
- Workflow-based
- Clear about required inputs
- Explicit about assumptions
- Explicit about uncertainty
- Materiality-driven
- Evidence-aware
- Decision-oriented
- Non-fabricating
- Human-accountable
- Reusable across similar situations

Every Skill should address, where applicable:

1. Purpose
2. Core Outcome
3. Intended Use
4. Inputs
5. Evidence / Sources
6. Workflow
7. Decision Rules
8. Output Requirements
9. Quality Checks
10. Failure Conditions
11. Guardrails
12. Human Accountability

Operational Skills should additionally address, where relevant:

- Execution readiness
- Workflow state
- Ownership
- Timing
- Dependencies
- Completion criteria
- Escalation
- Update cadence

Analytical Skills should additionally address, where relevant:

- Data integrity
- Calculation integrity
- Comparison basis
- Governing authority
- Evidence classification
- Confidence

Client-facing Skills should additionally address, where relevant:

- Audience
- Internal vs. external information boundaries
- Plain-language translation
- Trade-offs
- Example integrity
- Human review requirements

---

# Skill Title

**[Human-Readable Skill Title]**

---

# Purpose

Explain the business purpose of the Skill.

Answer:

- What problem does this Skill solve?
- Who benefits from it?
- What work does it perform?
- What decision, workflow, or outcome does it support?

Avoid generic language.

A good Purpose section explains why the Skill exists in a real insurance workflow.

---

# Core Outcome

Describe what a successful execution should accomplish.

Answer:

- What should the user understand?
- What should the AI produce?
- What decision should become easier?
- What workflow should advance?

Define success in operational terms.

---

# Best Used For

List the situations where the Skill is most useful.

Examples:

- Prospect preparation
- Renewals
- Submissions
- Claims
- Coverage analysis
- Service workflows
- Proposal development
- Employee benefits
- Commercial P&C
- Personal lines
- Agency operations

Keep examples relevant to the Skill.

---

# Do Not Use This Skill As

Define important boundaries.

Examples:

- Legal advice
- Formal coverage determination
- Binding authority
- Carrier underwriting authority
- Regulatory interpretation
- Actuarial analysis
- Final claims determination
- Formal contract interpretation

This section should prevent misuse without becoming a generic disclaimer block.

---

# Intended Users

Identify the primary users.

Examples:

- Producer
- Account Executive
- Account Manager
- Coverage Analyst
- Placement Specialist
- Benefits Advisor
- Claims Advocate
- Service Specialist
- Agency Principal

---

# Required Inputs

Define the minimum information necessary to execute the Skill responsibly.

Use a recommended invocation structure.

Example:

```text
Client:
[INSERT]

Context:
[INSERT]

Relevant Data:
[INSERT]
```

Do not require information that is not actually necessary.

---

# Recommended Inputs

List additional information that materially improves the output.

Examples:

- Revenue
- Payroll
- Locations
- Current carrier
- Policy documents
- Loss history
- Employee count
- Coverage limits
- Renewal date
- Client priorities
- Prior decisions
- Historical data

---

# Optional Intelligence Sources

Include only when external or supplemental research may materially improve the Skill.

Potential sources:

- Current carrier guidance
- Public company information
- Industry reports
- Regulatory guidance
- Rating authority information
- Market intelligence
- Public filings
- Client systems
- Agency systems

Do not use external information merely to create the appearance of depth.

---

# Preferred Source Documents

Where documents matter, rank the preferred source types.

Example:

1. Current authoritative document
2. Current endorsements or amendments
3. Current declarations / schedules
4. Current application or exposure data
5. Client-confirmed information
6. Agency-verified information
7. Historical documents
8. Professional inference

---

# Document Completeness Standard

**Use when the Skill depends materially on documents.**

Before drawing conclusions, determine whether the available document set is sufficiently complete.

Classify when useful:

### Complete Enough

The available documents reasonably support the requested analysis.

### Partially Complete

Useful analysis is possible, but important information is missing.

### Fragmentary

The available material is too limited for a reliable conclusion.

When documents are incomplete:

- State what was reviewed
- Identify what appears missing
- Limit conclusions to what the available material supports
- Do not imply that the entire document set has been reviewed

---

# Document Interaction / Override Standard

**Use when multiple documents may modify one another.**

Determine whether:

- Endorsements modify forms
- Amendments modify contracts
- Schedules modify limits
- Riders modify benefits
- Later documents supersede earlier documents
- One provision incorporates another

Do not interpret a document in isolation when another supplied document modifies it.

When multiple provisions interact:

1. Identify the base provision
2. Identify the modifying document
3. Explain what changed
4. Explain the practical effect
5. Flag unresolved conflicts

---

# Source Hierarchy

Define which sources control when information conflicts.

A typical hierarchy may include:

1. Current authoritative source
2. Governing document
3. Carrier-issued documentation
4. Client-confirmed information
5. Agency-verified information
6. Historical information
7. Professional inference

When sources conflict:

- Identify the conflict
- Do not silently choose a convenient answer
- Prefer the most authoritative current source
- Escalate material discrepancies when necessary

---

# Market Currency Standard

**Use when the Skill relies on time-sensitive external information.**

Current information should be used for claims involving:

- Carrier appetite
- Rates
- Pricing trends
- Regulations
- Laws
- Market conditions
- Capacity
- Reinsurance
- Vendor capabilities
- Product availability
- Program availability
- Minimum premiums
- Underwriting restrictions
- Technology capabilities

Do not present stale information as current.

Historical experience may be used as context, but should not automatically be treated as present-day fact.

When current validation is unavailable:

- State the limitation
- Label conclusions as provisional
- Recommend verification where material

---

# Jurisdiction / Governing Authority Standard

**Use when a conclusion depends on a governing authority.**

Identify the relevant authority before making definitive conclusions.

Potential authorities include:

- State law
- Rating bureau
- NCCI
- WCIRB
- Carrier underwriting rules
- Policy wording
- Plan document
- Contract
- Regulatory agency
- TPA rules
- Benefit plan terms
- Accounting rules

Do not assume that a rule used in one jurisdiction or system applies universally.

---

# Authority vs. Inference Standard

Distinguish between:

### Verified Source Fact

Supported directly by authoritative evidence.

### AI Analysis

A conclusion derived from the available information.

### Professional Recommendation

A recommended course of action based on analysis.

### Decision Authority

The person or organization authorized to make the final determination.

Examples of Decision Authorities may include:

- Carrier
- Rating bureau
- Regulator
- Claims professional
- Legal counsel
- Employer
- Plan administrator
- Authorized insurance professional

A strong analytical conclusion does not automatically equal authoritative approval.

---

# Evidence Classification

Define how statements should be categorized.

Potential classifications:

- Verified Fact
- Documented Finding
- Client-Confirmed Fact
- Calculated Observation
- Market-Supported Observation
- Professional Inference
- Recommendation
- Hypothesis
- Assumption
- Requires Confirmation
- Requires Authority Review

Use classifications appropriate to the Skill.

Never convert an inference into a fact.

---

# Confidence Classification

Where useful, classify findings:

### High Confidence

Strongly supported by authoritative or complete information.

### Moderate Confidence

Reasonably supported but dependent on one or more unresolved factors.

### Low Confidence

Significant uncertainty remains.

Confidence should reflect evidence quality, not writing style.

---

# Scope-of-Explanation Standard

**Use when the Skill explains laws, coverage, contracts, benefits, policies, or other governed concepts.**

Determine whether the task concerns:

### General Concept

A broad explanation of how something typically works.

or:

### Specific Instance

An explanation of a particular:

- Policy
- Contract
- Plan
- Endorsement
- Regulation
- Claim
- Quote
- Agreement

Do not silently substitute general knowledge for the user's actual governing document.

When only general information is available, identify the explanation as general.

---

# Context Interpretation Standard

Before analysis, classify important information when useful.

Possible categories:

- Known Fact
- Client Statement
- Producer Observation
- Industry Inference
- Open Question
- Proposed Action
- Pending Outcome

This prevents uncertainty from being hidden inside polished prose.

---

# Change / Drift Detection Standard

**Use when historical information may no longer reflect current conditions.**

Review whether the underlying situation has changed.

Potential drift includes:

- New operations
- New locations
- New employees
- New products
- New contracts
- Acquisitions
- New technology
- Changed carrier appetite
- Changed regulations
- Changed exposures
- Changed payroll
- Changed property values
- Changed cybersecurity controls
- Changed plan eligibility
- Changed claims experience

Historical information should be revalidated when material change has occurred.

---

# Core Principle

State the central operating philosophy of the Skill.

Examples:

> Identify real exposure, not theoretical defects.

> Every meeting needs a defined outcome.

> Do not default to remarketing.

> Explain the business decision, not just the insurance.

> Classify the work actually performed.

The Core Principle should shape the entire workflow.

---

# Execution Readiness Standard

**Use for Skills that recommend or execute actions.**

Before advancing the workflow, determine whether the available information is sufficient.

Classify when useful:

### Ready

The information and authority required to proceed are available.

### Conditionally Ready

Work can begin, but material dependencies or missing items remain.

### Not Ready

Critical information, authority, documentation, or prerequisites are missing.

Do not force execution simply because the Skill was invoked.

---

# Time Horizon / Execution Feasibility Standard

**Use when timing materially affects the recommendation.**

Determine:

- Effective date
- Renewal date
- Deadline
- Available lead time
- Required approval period
- External processing time
- Client decision window

Recommendations should reflect what can actually be executed within the available timeframe.

Do not recommend theoretically ideal actions that are no longer operationally feasible.

When useful, classify:

- Strategic / Long Horizon
- Normal Execution Window
- Compressed Timeline
- Urgent
- Too Late for Full Execution

---

# Workflow State Standard

**Use for operational or agentic Skills.**

Distinguish workflow states explicitly.

Potential states include:

1. Received
2. Validated
3. Ready
4. In Progress
5. Waiting on Client
6. Waiting on Carrier
7. Waiting on Third Party
8. Submitted
9. Under Review
10. Approved
11. Processed
12. Documentation Received
13. Completed
14. Escalated
15. Unable to Complete

Do not confuse:

> An action was initiated

with:

> The intended business outcome occurred.

Each Skill should use only the states relevant to its workflow.

---

# Workflow

Define the step-by-step execution logic.

Each step should answer:

- What should be done?
- Why does it matter?
- What evidence is needed?
- What decision follows?

Avoid vague workflow steps such as:

> Analyze the account.

Prefer:

> Compare current payroll by class code to the prior period and identify changes greater than the selected materiality threshold.

---

# Optional Workflow Modules

Include only when they materially improve execution.

Potential modules:

- Research
- Data validation
- Document review
- Calculation
- Comparison
- Client communication
- Carrier communication
- Negotiation
- Escalation
- Follow-up
- Quality control

---

# Data Integrity Standard

**Use when the Skill receives structured or unstructured data.**

Before analysis, assess:

- Missing values
- Duplicate records
- Conflicting totals
- Impossible values
- Stale information
- Inconsistent units
- Inconsistent periods
- Formatting problems
- Outliers
- Unreconciled totals

Do not silently repair material data problems.

Flag issues that could affect the conclusion.

---

# Data Normalization Standard

**Use when data must be standardized before analysis.**

Safe normalization may include:

- Standardizing dates
- Standardizing state names
- Standardizing labels
- Standardizing dollar formats
- Standardizing units
- Standardizing equivalent categories

Do not silently:

- Merge different entities
- Combine materially different exposures
- Delete records
- Reclassify data
- Fill missing values
- Override source information

when the change could alter the analysis.

---

# Calculation Integrity Standard

**Use when the Skill performs calculations.**

For every material calculation:

- Use documented values
- Identify the baseline
- Identify the denominator
- Use consistent periods
- Avoid fabricating missing values
- Avoid false precision
- Disclose when inputs are incomplete
- Distinguish calculated results from assumptions

Example:

Prefer:

> Based on the supplied schedule, Location A represents 42% of reported TIV.

rather than:

> Location A represents 42% of the company's total property exposure.

unless completeness is known.

---

# Comparison Basis / Like-for-Like Standard

**Use when comparing periods, policies, options, vendors, plans, quotes, or datasets.**

Before drawing conclusions, determine whether the inputs are comparable.

Check for differences in:

- Time period
- Exposure
- Scope
- Population
- Limits
- Deductibles
- Retentions
- Coverage
- Geography
- Dataset completeness
- Program structure
- Carrier
- Benefit design

If inputs are not comparable:

- Normalize where appropriate
- Explain the difference
- Avoid misleading percentage comparisons
- Do not call a total cost change a pure rate change without evidence

---

# Decision Rules

Define insurance-specific rules that govern the analysis.

Examples:

- Do not manufacture coverage gaps.
- Do not recommend the lowest-cost option solely because it is cheapest.
- Do not infer policy wording.
- Do not infer carrier appetite without current support.
- Do not treat historical data as current without validation.
- Do not make assumptions silently.
- Prioritize material issues over theoretical concerns.

Decision Rules should prevent predictable failure modes.

---

# Materiality / Prioritization Framework

Define how findings should be ranked.

Potential factors:

- Financial Impact
- Severity
- Frequency
- Coverage Impact
- Operational Impact
- Contractual Impact
- Urgency
- Client Priority
- Evidence Strength
- Underwriting Impact
- Execution Feasibility

Potential priority labels:

- Critical
- High
- Moderate
- Informational
- Requires Validation

Do not create long lists where all findings appear equally important.

---

# Trade-Off Transparency Standard

**Use whenever the Skill recommends one option over another.**

For every material recommendation, identify:

1. What the user gains
2. What the user gives up
3. What risk remains
4. What assumption supports the recommendation
5. What should be confirmed

Do not hide disadvantages simply because one option is preferred.

A trusted advisor explains both sides.

---

# Governance / Conflict Prevention Standard

**Use when actions can create duplicate, conflicting, exclusive, or irreversible effects.**

Before execution, consider:

- Duplicate actions
- Market blocking
- Conflicting instructions
- Existing ownership
- Exclusivity
- Duplicate submissions
- Overlapping workflows
- Pending requests
- Existing approvals
- Regulatory conflicts
- System-of-record conflicts

Do not execute an action simply because it is individually valid if it creates a downstream workflow conflict.

---

# Ownership Standard

**Use for operational Skills.**

Every material action should have an owner.

Potential owners:

- Client
- Agency
- Producer
- Account Manager
- Carrier
- Underwriter
- Claims Adjuster
- TPA
- Vendor
- Regulator
- Legal Counsel
- AI Teammate
- Other party

Avoid:

> This needs to be completed.

Prefer:

> The Account Manager will submit the request to the carrier after the client provides the signed authorization.

Ownership should be explicit enough to support execution and auditability.

---

# Dependency Standard

**Use when completion depends on another person, system, or event.**

Identify:

- What the dependency is
- Who controls it
- Whether work can continue without it
- What happens if it is delayed
- Whether escalation is appropriate

Do not imply control over third parties.

---

# Update Cadence Standard

**Use for unresolved material workflows.**

If the workflow remains open, define when the user or client should receive another update.

Examples:

- Upon material status change
- No later than a specified date
- After carrier review
- Within an established service window

When completion timing is uncertain, provide a **next-update commitment**.

Users should not need to chase the workflow for status.

---

# Stop Rules

**Use for iterative, research, marketing, negotiation, or repeated workflows.**

Define when the Skill should:

- Stop
- Escalate
- Move to the next phase
- Activate a contingency
- Request human intervention

Examples:

- Sufficient credible quotes have been obtained
- No additional market is likely to improve outcome
- Required information cannot be obtained
- Material inconsistency remains unresolved
- Deadline no longer permits the preferred strategy
- Authorized limit of AI action has been reached

More activity is not automatically better.

---

# Completion Criteria Standard

**Use for operational Skills.**

Define what must be true before the workflow is considered complete.

Do not equate:

- Submitted
- Requested
- Sent
- Reviewed

with:

- Completed

unless those events actually satisfy the intended business outcome.

Example:

A policy-change workflow may not be complete until:

1. Carrier approves the change
2. Carrier processes the endorsement
3. Revised documentation is received
4. Client receives confirmation
5. Internal systems are updated

Define completion from the intended outcome backward.

---

# Human Review Escalation Standard

Identify conditions requiring elevated human review before external release or execution.

Potential triggers:

- Coverage denial
- Potential uninsured loss
- Legal dispute
- Regulatory issue
- Cancellation
- Non-renewal
- Material financial harm
- Major claim
- Admission of fault
- E&O concern
- Binding or cancellation instruction
- Ambiguous governing authority
- High-impact policy interpretation
- Unsupported or low-confidence conclusion
- Client-sensitive communication
- Irreversible action

The AI may assist with analysis or drafting.

An authorized professional retains responsibility for the final decision or external action.

---

# Internal vs. External Information Boundary Standard

**Use when the Skill generates client-, carrier-, employee-, regulator-, or public-facing output.**

Classify information as:

### External Appropriate

Information necessary for the recipient to understand or act.

### Internal Only

Examples:

- Sales strategy
- E&O concerns
- Private hypotheses
- Internal blame
- Negotiation tactics
- Sensitive notes
- Compensation information
- Internal scoring
- Unverified speculation

### Requires Human Judgment

Information that may need disclosure but should be reviewed before release.

Do not leak internal reasoning into external communications.

---

# Audience Standard

Identify who will receive the output.

Potential audiences:

- Business Owner
- CEO
- CFO
- HR Leader
- Client
- Underwriter
- Claims Professional
- Account Manager
- Producer
- Employee
- Regulator

Adjust:

- Terminology
- Detail
- Tone
- Context
- Technical depth

without changing the underlying facts.

---

# Risk → Solution → Example → Limitation Framework

**Use primarily for educational or explanatory Skills.**

A useful client-facing sequence is:

### Risk

What real-world business problem exists?

### Solution

What insurance coverage, process, or strategy is designed to address it?

### Example

What realistic scenario makes the concept understandable?

### Limitation

What condition, exclusion, dependency, or uncertainty should the user understand?

This framework should improve clarity without turning education into product promotion.

---

# Example Integrity Standard

Whenever examples or hypothetical scenarios are used:

- Keep them consistent with the available evidence
- Clearly identify them as illustrative
- Do not imply guaranteed outcomes
- Do not broaden coverage or authority
- Do not add facts that materially change the scenario
- State what could change the result when relevant

Examples should clarify the rule, not silently rewrite it.

---

# Output Requirements

Define the required output structure.

A strong output specification should identify:

- Title
- Executive summary
- Tables
- Findings
- Recommendations
- Questions
- Assumptions
- Next actions

Avoid leaving the output completely open-ended.

---

# Output Tables

Where tables improve clarity, define them.

Example:

| Priority | Finding | Evidence | Impact | Recommended Action |
|---|---|---|---|---|

or:

| Action | Owner | Due | Status |
|---|---|---|---|

Do not force tables when narrative is more useful.

---

# Assumptions & Items Requiring Confirmation

Use when assumptions materially affect conclusions.

Recommended format:

| Assumption | Basis | Confidence | Confirmation Needed |
|---|---|---|---|
| [Assumption] | [Reason] | High / Moderate / Low | [Action] |

Never allow assumptions to disappear inside polished output.

---

# Quality Checks

Before finalizing, verify the Skill-specific requirements.

Every Skill should consider:

- [ ] Required inputs are present
- [ ] Important missing information is disclosed
- [ ] Facts are distinguished from inference
- [ ] Current information is used when required
- [ ] Governing authority is identified where relevant
- [ ] Material data is internally consistent
- [ ] Calculations are supportable
- [ ] Comparisons are like-for-like where applicable
- [ ] Recommendations disclose trade-offs
- [ ] Workflow state is accurate
- [ ] Ownership is clear
- [ ] Dependencies are identified
- [ ] Timing is realistic
- [ ] Completion criteria are defined when operational
- [ ] Human escalation requirements are respected
- [ ] Internal information is not leaked externally
- [ ] Output prioritizes materiality over volume
- [ ] No facts, coverage, terms, or outcomes were fabricated

Add Skill-specific checks beyond these.

---

# Failure Conditions

Define what makes the output unacceptable.

Common failure conditions include:

- Fabricating facts
- Silent assumptions
- Ignoring missing data
- Using stale information as current
- Ignoring governing authority
- Confusing analysis with approval
- Misleading calculations
- Non-comparable comparisons
- Generic recommendations
- Hidden trade-offs
- Premature execution
- Premature completion
- Undefined ownership
- Undefined next step
- Leaking internal strategy
- Unsupported guarantees
- Ignoring human-review requirements

If a failure condition exists, revise before finalizing or escalate appropriately.

---

# Guardrails

## Accuracy Over Completion

It is better to state that information is unavailable than to invent an answer.

---

## Never Fabricate Insurance Facts

Never invent:

- Coverage
- Limits
- Premium
- Deductibles
- Endorsements
- Exclusions
- Claims
- Revenue
- Payroll
- Employee counts
- Locations
- Policy provisions
- Carrier requirements
- Client facts
- Regulatory requirements

---

## No Silent Assumptions

When assumptions materially affect the outcome:

- Label them
- Explain their basis
- Identify what would confirm them

---

## No Unsupported Coverage Guarantees

Do not guarantee that:

- A policy responds
- A claim is covered
- A carrier must pay
- A limit is adequate

without appropriate authority.

---

## No Unauthorized Binding or Policy Changes

Do not:

- Bind coverage
- Alter coverage
- Cancel coverage
- Confirm policy changes

without appropriate authority and workflow execution.

---

## Governing Documents Control

Summaries and AI explanations do not replace:

- Policies
- Endorsements
- Contracts
- Plan documents
- Carrier rules
- Applicable law
- Regulatory authority

---

## No Legal Advice

Legal issues may be identified.

Do not provide unsupported legal conclusions.

---

## Protect Confidential Information

Do not unnecessarily expose:

- Personally identifiable information
- Claimant data
- Employee-sensitive data
- Financial account information
- Credentials
- Proprietary client information
- Internal agency strategy

Use aggregated information where appropriate.

---

## Preserve Human Accountability

The Skill supports the insurance professional.

The authorized professional remains responsible for:

- Final decisions
- Coverage recommendations
- Client communication
- Carrier communication
- Claims decisions
- Binding
- Cancellation
- Compliance
- Legal escalation
- Professional judgment

### Your people make the decisions. Your AI Teammates do the work.

---

# Professional Tone Standard

Define tone appropriate to the workflow.

Default Apeironix tone should be:

- Practical
- Insurance-specific
- Analytical
- Clear
- Concise
- Client-centered where applicable
- Commercially aware
- Non-alarmist
- Actionable

Avoid:

- Generic AI language
- Insurance clichés
- Fear-based selling
- Excessive jargon
- Unsupported certainty
- Product dumping
- Long unprioritized lists
- Artificial caution
- Empty reassurance

---

# Example

Provide a concise fictional example showing how the Skill should be used.

The example should demonstrate:

- Inputs
- Reasoning structure
- Output format
- Materiality
- Appropriate uncertainty
- Guardrails

Examples must comply with the **Example Integrity Standard**.

---

# Original Prompt

Preserve the original prompt that inspired the Skill.

> [INSERT ORIGINAL PROMPT EXACTLY]

Do not silently rewrite the original source prompt.

---

# Evolution From Prompt to Skill

Explain how the original prompt became a reusable operational Skill.

Potential additions include:

- Structured inputs
- Source hierarchy
- Evidence classification
- Decision rules
- Workflow
- Materiality
- Execution readiness
- Governance
- Output standards
- Quality controls
- Guardrails
- Human accountability

This section should demonstrate the evolution:

> Prompt → Skill → AI Teammate Capability

---

# Related Skills

List related Apeironix Skills.

Use live links only for published Skills.

Example:

- [Related Skill](../related-skill/SKILL.md)

For unpublished Skills, list the title without a link.

---

# Suggested Invocation

Provide a detailed invocation.

Example:

```text
Run [Skill Name].

Client:
[INSERT]

Context:
[INSERT]

Relevant Documents:
[INSERT]

Additional Information:
[OPTIONAL]
```

---

# Minimum Viable Invocation

Provide the smallest usable invocation.

Example:

```text
Context:
[INSERT]
```

---

# Version History

## 1.0.0

Initial public release.

List meaningful additions from the original prompt.

Future revisions should use semantic versioning.

---

# About Apeironix

Apeironix develops AI Teammates and reusable AI Skills designed around real insurance workflows.

Our goal is to give insurance professionals more capacity for:

- Judgment
- Relationships
- Client service
- Risk advisory
- Analysis
- Communication
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
