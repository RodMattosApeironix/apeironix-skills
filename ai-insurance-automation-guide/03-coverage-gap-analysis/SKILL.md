---
name: coverage-gap-analysis
title: Commercial Insurance Coverage Gap Analysis
collection: ai-insurance-automation-guide
prompt_number: 3
category: commercial-pc
capability: coverage-intelligence
primary_role: commercial-insurance-coverage-analyst
secondary_roles:
  - commercial-insurance-producer
  - commercial-account-executive
  - commercial-account-manager
  - risk-advisor
version: 1.0.0
maintainer: Apeironix
license: Apache-2.0
status: public
---

# Commercial Insurance Coverage Gap Analysis

## Purpose

Evaluate an existing commercial insurance program to identify material coverage gaps, structural weaknesses, inadequate limits, exclusions, operational exposures, and other issues that could leave the insured meaningfully exposed.

This Skill is designed to help an insurance professional determine:

- Which material coverages may be missing
- Where limits may be inadequate
- Where policy structure may not match the insured’s operations
- Which exclusions or limitations could materially affect protection
- Which operational exposures may not be adequately addressed
- Which issues deserve immediate attention
- Which issues are secondary or informational
- What should be confirmed before making a recommendation

The objective is **not** to produce a theoretical list of every coverage that could possibly exist.

The objective is to identify **realistic, material, and actionable coverage concerns based on the insured’s actual or reasonably inferred operations**.

---

# Core Outcome

A successful use of this Skill should help the insurance professional answer:

- What could materially hurt this insured that the current program may not adequately address?
- Which important coverages appear to be missing?
- Are any limits or sublimits potentially inadequate?
- Are the existing coverage structures aligned with the insured’s operations?
- Do exclusions create meaningful uninsured or underinsured exposures?
- Are there important operational risks that the current program does not appear to address?
- Which concerns should be prioritized first?
- What additional information is needed before reaching a final conclusion?
- What should the producer or Account Manager discuss with the client?

The final output should support a practical advisory conversation, not simply produce a list of policy observations.

---

# Best Used For

Use this Skill when reviewing:

- An existing commercial insurance program
- A prospect’s current insurance structure
- A renewal program
- A broker-of-record opportunity
- A pre-renewal coverage review
- A new-client onboarding review
- A policy summary
- A coverage schedule
- A proposal
- A statement of values
- A program overview
- A client-provided insurance summary
- A multi-line commercial account
- A cross-sell opportunity
- A stewardship review
- A due-diligence review
- A risk-management conversation

This Skill is particularly valuable when the goal is to determine **where advisory value may exist beyond price**.

---

# Do Not Use This Skill As

This Skill is not a substitute for:

- A legal opinion
- A formal coverage opinion
- A claim-coverage determination
- A carrier interpretation
- A binding recommendation
- A complete policy-form review when only summaries are available
- A regulatory opinion
- An underwriting decision
- A loss-control inspection
- A valuation appraisal
- A replacement-cost estimate
- A full actuarial analysis

This Skill is intended to support **coverage analysis and professional review**.

---

# Intended Users

This Skill is designed primarily for:

- Commercial Insurance Coverage Analysts
- Commercial Insurance Producers
- Commercial Account Executives
- Commercial Account Managers
- Risk Advisors
- Agency Principals
- Practice Leaders
- Quality-Control Reviewers
- Other authorized commercial insurance professionals

---

# Required Inputs

At minimum, provide:

1. **Policy summary, coverage schedule, proposal, or policy details**

Recommended input format:

```text
Policy Details:
[PASTE POLICY SUMMARY OR DETAILS]
```

The information may include:

- Coverage lines
- Carriers
- Policy periods
- Limits
- Deductibles
- Sublimits
- Endorsements
- Exclusions
- Locations
- Vehicles
- Payroll
- Property values
- Business income values
- Umbrella structure
- Cyber limits
- Executive-risk limits
- Other program details

If the supplied information is too incomplete to support a meaningful analysis, identify what is missing before reaching firm conclusions.

---

# Recommended Inputs

The following inputs materially improve the analysis:

- Company name
- Industry
- Revenue
- Employee count
- Payroll
- Number of locations
- States of operation
- Property values
- Business personal property values
- Equipment values
- Inventory values
- Vehicle count
- Fleet type
- Driver count
- Customer types
- Use of subcontractors
- Contracts
- Major vendors
- Major customers
- Product or service description
- Professional services
- Cyber/data exposure
- International operations
- Claims history
- Loss runs
- Current renewal pricing
- Historical program structure
- Prior coverage changes
- Current or planned business changes
- M&A activity
- Construction activity
- Property ownership vs. leasing
- Risk-control information
- Disaster-recovery information
- Business-continuity information

---

# Preferred Source Documents

Where available, use actual policy documents rather than summaries.

Preferred order:

1. Full current policies
2. Current endorsements
3. Current declarations
4. Current schedules
5. Current proposals
6. Policy summaries
7. Agency Management System data
8. Client-provided summaries
9. Historical policies
10. Industry-based inference

The reliability of the analysis should reflect the reliability of the source.

---

# Source Hierarchy

When multiple sources conflict, prioritize:

1. Current policy form and endorsements
2. Current declarations and schedules
3. Carrier-issued documents
4. Agency-verified policy information
5. Client-provided information
6. Prior policy information
7. Proposal information
8. Industry norms and professional inference

When sources conflict:

- Identify the conflict
- Do not silently choose one value
- State which source appears more authoritative
- Flag the issue for human review

---

# Evidence Classification

Every material finding should be classified as one of the following.

## Documented Finding

Directly supported by the policy information provided.

Example:

> The program shows a $1,000,000 each-occurrence general liability limit.

---

## Likely Concern

A potential weakness suggested by the available information but not fully verified.

Example:

> Business-income coverage may be inadequate if the $500,000 limit is intended to support a multi-location operation with more than $20 million in annual revenue.

---

## Exposure-Dependent Concern

A coverage issue that matters only if a specific operational fact is confirmed.

Example:

> Hired and non-owned auto coverage should be confirmed if employees use personal vehicles for business purposes.

---

## Requires Policy-Form Review

An issue that cannot be responsibly resolved from a summary or declarations page alone.

Example:

> The scope of additional insured coverage cannot be determined without reviewing the applicable endorsement wording.

---

# Confidence Classification

Where useful, classify findings:

### High Confidence
Directly supported by policy documents or clear program information.

### Moderate Confidence
Strongly suggested by the available information but requires confirmation.

### Low Confidence
Possible concern based on limited information or industry norms.

Do not overstate certainty.

---

# Core Principle

## Identify Real Exposure, Not Theoretical Defects

Do not create a long list of missing endorsements or optional coverages merely because they exist.

A concern should be included only when there is a reasonable connection between:

1. The insured’s operations or likely operations, and
2. A potentially meaningful uninsured or underinsured loss.

Ask:

> If this coverage weakness were real, could it materially affect the insured?

If the answer is no, it should not be prioritized.

---

# Workflow

Follow the workflow in order unless the available information requires a different sequence.

---

## Step 1 — Establish What Is Actually Known

Review the supplied information and identify:

- Named insured
- Policy period
- Carrier
- Coverage lines
- Limits
- Deductibles
- Sublimits
- Retentions
- Locations
- Schedules
- Endorsements
- Exclusions
- Underlying policies
- Umbrella/excess structure
- Any missing lines or documents

Separate what is documented from what is assumed.

---

## Step 2 — Establish the Operating Context

Where business information is available, determine:

- What the insured does
- How revenue is generated
- Where operations occur
- What assets are critical
- What employees do
- Whether vehicles are used
- Whether products are manufactured or distributed
- Whether professional services are provided
- Whether subcontractors are used
- Whether contracts create obligations
- Whether data or technology is critical
- Whether operations are concentrated
- Whether catastrophe exposure is significant

Coverage cannot be evaluated correctly without understanding the operation it is intended to protect.

---

## Step 3 — Build the Coverage Map

Identify all known coverage lines.

Potential categories include:

- Commercial Property
- Business Income
- General Liability
- Products / Completed Operations
- Commercial Auto
- Workers’ Compensation
- Employers Liability
- Umbrella
- Excess Liability
- Cyber Liability
- Technology E&O
- Professional Liability
- Employment Practices Liability
- Directors & Officers Liability
- Fiduciary Liability
- Crime
- Inland Marine
- Equipment Breakdown
- Builders Risk
- Pollution Liability
- Contractors Pollution
- Product Recall
- Cargo
- Ocean Marine
- International
- Surety
- Specialty program coverage

Do not assume coverage exists because it would normally be expected.

---

## Step 4 — Identify Missing or Overlooked Coverages

Evaluate whether material exposure appears to exist without corresponding protection.

Examples may include:

- Hired/non-owned auto
- Cyber liability
- Social engineering
- Funds-transfer fraud
- EPLI
- D&O
- Fiduciary
- Pollution
- Professional liability
- Product recall
- Inland marine
- Equipment breakdown
- Ordinance or law
- Utility services
- Contingent business interruption
- International coverage
- Crime
- Contractors pollution
- Employment-related coverage
- Property of others
- Transit exposure

For each potential missing coverage:

### Exposure
What creates the need?

### Why It Matters
What loss could occur?

### Evidence
What supports the concern?

### What to Confirm
What additional information is needed?

Do not recommend coverage merely because it is commonly sold.

---

## Step 5 — Evaluate Limit Adequacy

Review whether existing limits appear reasonable relative to the exposure.

Potential areas:

- Property
- Business income
- General liability
- Auto
- Umbrella
- Cyber
- EPLI
- D&O
- Crime
- Professional liability
- Product liability
- Pollution
- Inland marine
- Cargo

Do not state that a limit is definitively inadequate without sufficient information.

Use language such as:

> The limit may be inadequate relative to the known exposure and should be validated.

or:

> The program shows a $1 million umbrella, which may warrant review if the insured operates a significant commercial fleet or has high-severity products exposure.

---

## Step 6 — Evaluate Program Structure

Coverage amount alone may not determine adequacy.

Review structural issues such as:

- Primary vs. excess placement
- Underlying limits
- Attachment points
- Deductibles
- Self-insured retentions
- Claims-made vs. occurrence
- Retroactive dates
- Extended reporting periods
- Shared limits
- Aggregate limits
- Per-location limits
- Blanket vs. scheduled coverage
- Sublimits
- Coinsurance
- Margin clauses
- Named insured structure
- Additional insured structure
- Cross-liability
- Separation of insureds
- Defense inside vs. outside limits
- Layering
- Carrier continuity

Ask:

> Does the structure actually respond in a way that matches the insured’s loss potential?

---

## Step 7 — Evaluate Property Adequacy

Where property exposure exists, review:

- Building values
- Business personal property
- Inventory
- Equipment
- Stock
- Tenant improvements
- Property of others
- Outdoor property
- Mobile property
- Property in transit
- Replacement cost
- Actual cash value
- Coinsurance
- Margin clauses
- Blanket limits
- Catastrophe deductibles
- Wind/hail
- Earthquake
- Flood
- Water damage
- Equipment breakdown
- Ordinance or law

Flag valuation concerns where values appear old, incomplete, or inconsistent with the operation.

Do not independently calculate replacement cost unless sufficient valuation data is provided.

---

## Step 8 — Evaluate Business Income / Extra Expense

Where applicable, evaluate:

- Business-income limit
- Actual-loss-sustained treatment
- Coinsurance
- Period of restoration
- Extended period of indemnity
- Extra expense
- Waiting periods
- Dependent properties
- Utility interruption
- Civil authority
- Ingress/egress
- Equipment lead times
- Supply-chain dependency
- Customer concentration
- Location concentration

Ask:

> If the insured’s most important operation stopped tomorrow, would the current program reasonably support the time and cost required to recover?

---

## Step 9 — Evaluate Liability Coverage

Review:

- General liability limits
- Aggregate limits
- Products/completed operations
- Contractual liability
- Additional insured treatment
- Primary/noncontributory wording
- Waiver of subrogation
- Professional services exclusions
- Pollution exclusions
- Residential exclusions
- Height limitations
- Classification limitations
- Assault and battery
- Abuse/molestation
- Liquor liability
- Cyber/privacy exclusions
- Employment-related exclusions
- Designated operations exclusions

Only include limitations relevant to the insured.

---

## Step 10 — Evaluate Commercial Auto

Where auto exposure exists, review:

- Liability limits
- Symbol structure
- Hired auto
- Non-owned auto
- Any-auto coverage
- Physical damage
- Uninsured/underinsured motorist
- Medical payments
- Cargo
- Towing
- Rental reimbursement
- Drive-other-car
- Employees as insureds
- MCS-90 or transportation-specific filings where applicable

Consider severity exposure where fleet size, vehicle type, or radius suggests catastrophic loss potential.

---

## Step 11 — Evaluate Workers’ Compensation

Review:

- Covered states
- Employers liability limits
- Payroll classifications
- Experience modification
- Stop-gap coverage where relevant
- Other-states coverage
- USL&H
- Jones Act
- Foreign voluntary workers’ compensation
- Executive officer treatment
- Waivers of subrogation
- Alternate employer endorsements

Do not infer classification accuracy without payroll and operational information.

---

## Step 12 — Evaluate Umbrella / Excess Structure

Review:

- Total limits
- Attachment points
- Follow-form status
- Underlying policies
- Gaps between primary and excess
- Aggregate treatment
- Auto exposure
- Products exposure
- Catastrophic premises exposure
- Contractual requirements
- Carrier layering

Flag situations where severity appears materially larger than available limits.

---

## Step 13 — Evaluate Cyber and Crime

Where relevant, review:

- Cyber liability
- Ransomware
- Privacy liability
- Business interruption
- Dependent business interruption
- Social engineering
- Funds-transfer fraud
- Computer fraud
- Invoice manipulation
- Bricking
- Cybercrime
- Incident response
- Notification costs
- Regulatory coverage
- Technology E&O

Do not assume cyber insurance includes crime or social engineering.

---

## Step 14 — Evaluate Executive and Employment Risk

Where applicable, review:

- EPLI
- Wage/hour sublimits
- D&O
- Entity coverage
- Fiduciary liability
- Crime
- Kidnap/ransom
- Employed lawyers
- Workplace violence
- Third-party EPLI

Tie the review to workforce size, ownership structure, board/investor exposure, and employment practices.

---

## Step 15 — Evaluate Specialized Exposures

Where relevant, review:

- Pollution
- Professional liability
- E&O
- Product recall
- Product contamination
- Inland marine
- Installation floater
- Builders risk
- Contractor’s equipment
- Ocean cargo
- Motor truck cargo
- Warehouse legal liability
- International
- Surety
- Aviation
- Marine
- Specialty programs

Do not include specialty coverage unless the insured’s operations support the exposure.

---

## Step 16 — Evaluate Exclusions and Limitations

Identify exclusions or limitations that could materially change protection.

Prioritize exclusions that intersect directly with the insured’s operations.

For each:

### Limitation
[Exclusion or restriction]

### Exposure Connection
[Why it matters to this insured]

### Potential Consequence
[What could be uninsured]

### Review Needed
[Document, endorsement, or fact to confirm]

Do not infer policy wording that has not been provided.

If actual forms are unavailable, state:

> Requires policy-form review.

---

## Step 17 — Identify Operational Risks Not Adequately Addressed

Coverage alone may not solve the exposure.

Identify risk-management issues such as:

- Poor fleet controls
- Weak contract review
- Inadequate subcontractor controls
- No formal business continuity plan
- Cybersecurity weakness
- Lack of MFA
- Weak backups
- No return-to-work program
- Incomplete safety program
- Poor claims reporting
- Concentrated supply chain
- Poor certificate management
- Inadequate property protection
- Incomplete valuation process

Where relevant, identify whether the issue requires:

- Coverage improvement
- Risk control
- Contractual change
- Operational change
- Carrier engagement
- Additional information

---

## Step 18 — Identify Program Coordination Issues

Review whether lines interact properly.

Potential issues:

- Umbrella not following underlying coverage
- Professional liability outside umbrella
- Cyber vs. crime gaps
- Auto vs. umbrella gap
- Pollution exclusions across multiple policies
- EPLI vs. D&O overlap
- Property vs. inland marine overlap
- Product liability vs. professional liability gap
- Builders risk vs. property conflict
- Contractual obligations exceeding available limits

Program gaps frequently occur **between policies**, not only within them.

---

## Step 19 — Identify Named Insured and Entity Issues

Where information is available, confirm:

- Correct legal entities
- Subsidiaries
- DBAs
- Joint ventures
- Partnerships
- Property-owning entities
- Management companies
- Newly acquired entities
- Former entities
- Trusts
- LLCs

Flag entity mismatches because they can materially affect coverage.

---

## Step 20 — Prioritize the Findings

Rank findings based on potential client impact.

Use:

### Priority 1 — Critical

Potential for severe uninsured or underinsured loss, significant operational disruption, or material coverage failure.

### Priority 2 — High

Meaningful exposure that should be addressed during the current review or renewal.

### Priority 3 — Moderate

Important but not immediately threatening.

### Priority 4 — Informational

Worth noting but unlikely to materially affect the current program.

Do not make every concern “critical.”

---

# Materiality Framework

When ranking concerns, consider:

| Factor | Question |
|---|---|
| Severity | How large could the loss be? |
| Frequency | How likely is the event? |
| Coverage Certainty | How likely is the program to respond? |
| Financial Impact | Could the loss materially affect the insured? |
| Operational Impact | Could the event materially disrupt operations? |
| Contractual Impact | Could the insured be obligated beyond coverage? |
| Urgency | Does this need attention before renewal or immediately? |
| Evidence | How strongly is the concern supported? |

Use professional judgment rather than artificial scoring unless requested.

---

# Decision Rules

## Material Exposure Before Technical Detail

Prioritize a real uninsured million-dollar exposure over a technical wording issue with limited practical impact.

---

## Do Not Manufacture Gaps

A coverage is not automatically a gap simply because it is absent.

First establish whether the corresponding exposure exists.

---

## Do Not Assume More Insurance Is Always Better

Recommendations should consider:

- Risk tolerance
- Exposure severity
- Cost
- Existing controls
- Contractual requirements
- Carrier appetite
- Client priorities

The answer is not always “buy more insurance.”

---

## Distinguish Coverage From Risk Control

Some problems are better addressed operationally.

Example:

A poor fleet safety program may require both:

- Appropriate insurance, and
- Better driver controls

Do not treat insurance as a substitute for risk management.

---

## Do Not Infer Policy Language

If actual policy wording is unavailable, do not state that a specific exclusion applies.

Use:

> The summary does not provide enough information to determine whether [issue] is covered. Review the applicable policy form and endorsement.

---

## Current Documents Take Priority

Do not rely on prior-year terms when current terms are available.

---

## Severity Over Volume

The output should prioritize the issues that could actually matter.

Five strong findings are better than twenty speculative findings.

---

# Output Requirements

Use the following structure unless the user requests another format.

---

# Commercial Coverage Gap Analysis

## Program Snapshot

**Insured:** [If known]  
**Industry:** [If known]  
**Policy Period:** [If known]  
**Prepared For:** Coverage Adequacy Review

### Information Reviewed

List the policy information and documents reviewed.

### Analysis Limitation

Clearly identify any major missing information.

---

# 1. Executive Coverage Perspective

Provide a concise senior-level summary answering:

- Overall, how well does the known program appear to match the insured’s operations?
- Where does the greatest potential exposure appear to exist?
- Which issue should receive immediate attention?
- What information is still needed before firm recommendations can be made?

Keep this section focused on the highest-impact issues.

---

# 2. Priority Concerns

Rank all material findings.

| Priority | Concern | Potential Impact | Confidence | Recommended Action |
|---|---|---|---|---|
| Critical / High / Moderate / Informational | [Issue] | [Impact] | High / Moderate / Low | [Action] |

Order from highest to lowest impact.

---

# 3. Missing or Overlooked Coverages

For each:

## [Coverage]

**Exposure:**  
[What creates the need]

**Current evidence:**  
[What the program shows]

**Potential gap:**  
[Concern]

**Potential consequence:**  
[Impact]

**What to confirm:**  
[Needed information]

**Priority:**  
Critical / High / Moderate / Informational

---

# 4. Limit and Program-Structure Concerns

Use a table where useful.

| Coverage / Structure | Current | Concern | Potential Impact | Review Needed |
|---|---|---|---|---|
| [Coverage] | [Known limit/structure] | [Concern] | [Impact] | [Action] |

---

# 5. Exclusions or Policy Limitations

For each:

## [Exclusion / Limitation]

**Documented or suspected:**  
[Documented / Requires form review]

**Why it matters:**  
[Explanation]

**Potential uninsured exposure:**  
[Explanation]

**Recommended review:**  
[Action]

Do not present unverified exclusions as fact.

---

# 6. Operational Risks Not Adequately Addressed

| Operational Risk | Current Program Concern | Risk-Control Opportunity | Recommended Action |
|---|---|---|---|
| [Risk] | [Coverage issue] | [Control] | [Action] |

---

# 7. Program Coordination Issues

Identify gaps between policies.

Examples:

- Primary/excess mismatch
- Cyber/crime gap
- GL/professional gap
- Property/inland marine gap
- D&O/EPLI overlap
- Pollution exclusions
- Contractual requirements exceeding limits

---

# 8. Information Required to Complete the Review

List missing information by priority.

### Required

Information necessary before making a final recommendation.

### Helpful

Information that would improve the analysis.

---

# 9. Recommended Next Steps

Provide specific actions in order.

Example:

1. Obtain complete current policy forms and endorsements.
2. Confirm business-income calculation.
3. Review umbrella attachment points.
4. Confirm hired/non-owned auto exposure.
5. Review representative customer contracts.
6. Validate cyber/social-engineering limits.
7. Discuss priority findings with the client.

---

# 10. Advisor Conversation Priorities

Provide:

### Top 3 Issues to Discuss With the Client

1. [Issue]
2. [Issue]
3. [Issue]

### Highest-Impact Coverage Concern

**[Concern]**

### Highest-Impact Operational Concern

**[Concern]**

### Best Immediate Advisory Opportunity

**[Opportunity]**

---

# Assumptions & Items Requiring Confirmation

This section is mandatory whenever inference is used.

Use:

| Assumption | Basis | Confidence | Confirmation Needed |
|---|---|---|---|
| [Assumption] | [Reason] | High / Moderate / Low | [Action] |

---

# Quality Checks

Before completing the Skill, verify:

- [ ] Correct insured/program was reviewed
- [ ] Policy period is identified when available
- [ ] Source documents are identified
- [ ] Current documents are prioritized
- [ ] Documented findings are distinguished from inference
- [ ] Missing information is clearly disclosed
- [ ] Missing coverage recommendations are exposure-driven
- [ ] Limit concerns are tied to actual or likely exposure
- [ ] No unsupported policy wording is invented
- [ ] Exclusions are verified or clearly labeled as requiring form review
- [ ] Program coordination issues are considered
- [ ] Named insured/entity issues are considered when relevant
- [ ] Operational risk is evaluated separately from coverage
- [ ] Severity is prioritized over minor technical issues
- [ ] Findings are ranked from highest to lowest impact
- [ ] Recommendations are practical and actionable
- [ ] No binding or claim-coverage conclusions are made
- [ ] Assumptions are disclosed
- [ ] The final output prioritizes insight over volume

---

# Failure Conditions

The Skill should not be considered complete if:

- Findings consist primarily of generic coverage suggestions
- Missing coverage is recommended without identifying the exposure
- Policy wording is invented
- Limits are declared inadequate without supporting context
- Every issue is ranked high or critical
- Material severity exposures are ignored
- Assumptions are presented as facts
- Program coordination is not considered
- Operational risk is ignored
- No actionable next steps are provided
- The analysis suggests certainty unsupported by the source information

If any failure condition exists, revise before finalizing.

---

# Guardrails

## Do Not Fabricate Coverage

Never invent:

- Limits
- Deductibles
- Endorsements
- Exclusions
- Sublimits
- Retentions
- Forms
- Carriers
- Policy provisions
- Covered locations
- Covered entities

---

## Do Not Guarantee Coverage

Never state:

- A claim is covered
- A claim is excluded
- Coverage definitely applies
- A policy will respond
- A carrier will accept the exposure
- A limit is definitively sufficient

unless supported by authoritative information and appropriate professional review.

---

## Do Not Treat a Summary as a Full Policy

A summary may omit:

- Conditions
- Definitions
- Endorsements
- Exclusions
- Sublimits
- Aggregate provisions
- Territory
- Reporting requirements
- Retroactive dates

When necessary, state:

> Full policy-form review is required.

---

## No Legal Advice

Contractual or legal issues may be identified.

Do not provide legal conclusions.

Recommend qualified legal review where appropriate.

---

## Preserve Human Accountability

This Skill supports the insurance professional.

The authorized insurance professional remains responsible for:

- Coverage interpretation
- Recommendations
- Client communication
- Policy placement
- Carrier interaction
- Compliance
- Binding decisions

### Your people make the decisions. Your AI Teammates do the work.

---

# Professional Tone Standard

Write like a senior commercial coverage analyst.

The tone should be:

- Direct
- Specific
- Practical
- Insurance-specific
- Analytical
- Client-centered
- Non-alarmist
- Actionable

Avoid:

- Generic disclaimers repeated throughout the analysis
- Long theoretical coverage lists
- Fear-based language
- Technical jargon without explanation
- Overstating uncertainty
- False precision
- Product dumping

The objective is to surface the issues that actually matter.

---

# Example

## Example Request

```text
Policy Details:

General Liability:
$1,000,000 Each Occurrence
$2,000,000 General Aggregate
$2,000,000 Products/Completed Operations

Commercial Auto:
$1,000,000 CSL
12 owned vehicles

Workers' Compensation:
Statutory
Employers Liability $1,000,000

Umbrella:
$1,000,000

Property:
Building $4,000,000
Business Personal Property $1,500,000
Business Income $500,000

Business:
Regional food distributor
Annual Revenue: $35,000,000
40 delivery vehicles are actually operated, but only 12 appear on the auto summary.
```

---

## Example Output Excerpt

### Executive Coverage Perspective

The most significant concern is the discrepancy between the stated operation and the commercial auto schedule. The business reportedly operates approximately 40 delivery vehicles, while the supplied program summary shows only 12 owned vehicles.

This requires immediate clarification before any broader coverage conclusions are made.

A second concern is the $500,000 business-income limit. For a $35 million revenue distributor dependent on physical distribution operations, the limit may be materially inadequate if it is intended to cover a prolonged interruption.

The $1 million umbrella also warrants review given the commercial fleet exposure and potential catastrophic auto severity.

---

### Priority Concerns

| Priority | Concern | Potential Impact | Confidence | Recommended Action |
|---|---|---|---|---|
| Critical | Vehicle schedule discrepancy | Potential uninsured auto exposure | High | Reconcile all owned, leased, hired, and scheduled vehicles immediately |
| High | Business-income limit | Potential inability to fund prolonged interruption | Moderate | Complete business-income worksheet and recovery-time analysis |
| High | Umbrella limit | Catastrophic fleet loss may exceed available excess limits | Moderate | Evaluate severity exposure and contractual requirements |

---

### Missing or Overlooked Coverage

## Hired and Non-Owned Auto

**Exposure:**  
Employees or operations may involve rented vehicles or personal vehicles used for business.

**Current evidence:**  
The supplied summary does not confirm hired or non-owned auto coverage.

**Potential gap:**  
The insured may have liability exposure for vehicles not owned or scheduled on the commercial auto policy.

**What to confirm:**  
Whether employees use personal vehicles, rental vehicles, or temporary replacement vehicles for company business.

**Priority:**  
High if exposure exists.

---

# Original Prompt

The original Apeironix AI Insurance Automation Guide prompt that inspired this Skill:

> You are a commercial insurance coverage analyst reviewing an existing program to identify meaningful risk and advisory opportunities. Your objective is to surface real coverage gaps, not theoretical issues.
>
> Review the policy information below and evaluate it as if you are advising a client on how well their current program protects their operations.
>
> Policy Details: [PASTE POLICY SUMMARY OR DETAILS]
>
> Focus on practical exposure analysis. Where information is incomplete, clearly label assumptions and base your conclusions on typical industry risk profiles.
>
> Structure your response as:
>
> - Missing or overlooked coverages that should be considered
> - Areas where limits or structures may be insufficient
> - Exclusions or policy limitations that could create real exposure
> - Operational risks that are not adequately addressed by the current program
> - A ranked list of priority concerns (highest to lowest impact)
>
> Be specific, realistic, and actionable. Avoid generic or overly cautious language.

---

# Evolution From Prompt to Skill

The original prompt established the goal of identifying meaningful coverage gaps.

This Skill expands that prompt into a repeatable coverage-intelligence workflow by adding:

- Required inputs
- Recommended inputs
- Preferred source documents
- Source hierarchy
- Evidence classification
- Confidence classification
- Exposure-based coverage analysis
- Limit adequacy framework
- Program-structure review
- Property review
- Business-income review
- Liability review
- Auto review
- Workers’ compensation review
- Umbrella/excess review
- Cyber/crime review
- Executive-risk review
- Specialized coverage review
- Exclusion analysis
- Operational-risk analysis
- Program-coordination review
- Named-insured/entity review
- Materiality framework
- Priority ranking
- Output standards
- Quality-control checklist
- Failure conditions
- Insurance-specific guardrails
- Example implementation

The purpose is to transform a coverage-review prompt into a reusable **Coverage Intelligence Skill**.

---

# Related Skills

Related Apeironix Skills may include:

- Commercial Prospect Intelligence Brief
- Commercial Insurance Meeting Strategy Builder
- Commercial Policy Comparison
- Commercial Renewal Preparation
- Business Income Analysis
- Contractual Risk Transfer Review
- Loss Run Analysis
- Umbrella Adequacy Review
- Cyber Coverage Review
- Property Valuation Review

Links should be added as those Skills are published.

---

# Suggested Invocation

```text
Perform a Commercial Insurance Coverage Gap Analysis.

Company: [OPTIONAL]
Industry: [OPTIONAL]
Location: [OPTIONAL]

Policy Details:
[PASTE POLICY SUMMARY, DECLARATIONS, PROPOSAL, OR POLICY INFORMATION]

Known Operations:
[OPTIONAL]

Known Concerns:
[OPTIONAL]
```

---

# Minimum Viable Invocation

```text
Policy Details:
[PASTE POLICY SUMMARY OR DETAILS]
```

---

# Version History

## 1.0.0

Initial public release.

Enhancements from the original Prompt #3 include:

- Structured coverage-gap workflow
- Preferred-source hierarchy
- Evidence classification
- Confidence classification
- Materiality framework
- Limit-adequacy review
- Program-structure analysis
- Multi-line coverage review
- Exclusion and limitation framework
- Operational-risk analysis
- Program-coordination analysis
- Named-insured review
- Priority-ranking framework
- Information-gap disclosure
- Advisor conversation priorities
- Quality-control standards
- Failure conditions
- Insurance-specific guardrails
- Example implementation

---

# About Apeironix

Apeironix develops AI Teammates and reusable AI Skills designed around real insurance workflows.

Our goal is to give insurance professionals more capacity for:

- Judgment
- Relationships
- Client service
- Risk advisory
- Coverage analysis
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
