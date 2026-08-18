---
name: renewal-comparison-analysis
title: Commercial Insurance Renewal Comparison Analysis
collection: ai-insurance-automation-guide
prompt_number: 13
category: commercial-pc
capability: renewal-intelligence
primary_role: commercial-insurance-advisor
secondary_roles:
  - commercial-insurance-producer
  - commercial-account-executive
  - commercial-account-manager
  - coverage-analyst
  - risk-advisor
version: 1.0.0
maintainer: Apeironix
license: Apache-2.0
status: public
---

# Commercial Insurance Renewal Comparison Analysis

## Purpose

Compare an expiring commercial insurance program against renewal terms and translate the differences into a clear, decision-ready client analysis.

This Skill is designed to help the insurance professional:

- Identify what changed from expiring to renewal
- Separate premium change from exposure change
- Identify changes in limits, deductibles, retentions, exclusions, endorsements, and structure
- Explain whether protection improved, declined, or remained materially unchanged
- Identify new risk being retained by the client
- Identify risks that have been reduced
- Identify risks that remain unresolved
- Clarify what is driving cost changes
- Prioritize the changes that should influence the client’s decision
- Recommend practical actions before binding

The objective is **not** to create a line-by-line technical redline of the policies.

The objective is to create a concise **Renewal Comparison Analysis** that answers:

> What changed, why does it matter, and what should the client do about it?

---

# Core Outcome

A successful use of this Skill should allow the client to understand:

- How much the renewal cost changed
- What is actually driving that cost change
- Which coverage terms improved
- Which coverage terms became more restrictive
- Whether deductibles or retained risk increased
- Whether limits increased or decreased
- Whether new exclusions or sublimits were added
- Whether important risks remain unchanged
- Which changes are material versus administrative
- What should be negotiated, clarified, or accepted
- What decision the client needs to make

The final output should help the client evaluate the renewal based on both **cost and protection**.

---

# Best Used For

Use this Skill when comparing:

- Expiring policy vs. renewal policy
- Expiring proposal vs. renewal proposal
- Incumbent renewal terms
- Renewal indication vs. prior-year program
- Renewal terms after negotiation
- Multi-line commercial renewals
- Property renewals
- General Liability renewals
- Commercial Auto renewals
- Workers' Compensation renewals
- Umbrella / Excess renewals
- Cyber renewals
- Executive-risk renewals
- Professional Liability renewals
- Specialty coverage renewals
- Renewal presentations
- Stewardship meetings
- Client decision meetings

This Skill is especially useful when the client wants to know whether a premium increase reflects:

- Higher rates
- Increased exposures
- Broader coverage
- Reduced coverage
- Higher retained risk
- A combination of factors

---

# Do Not Use This Skill As

This Skill is not a substitute for:

- A complete policy-form comparison
- Legal interpretation
- Claim-coverage determination
- Binding confirmation
- Carrier underwriting authority
- A formal valuation analysis
- Actuarial analysis
- Regulatory advice
- A complete coverage-gap review
- Final client authorization

This is a **renewal comparison and decision-support Skill**.

---

# Intended Users

This Skill is designed primarily for:

- Commercial Insurance Advisors
- Commercial Insurance Producers
- Commercial Account Executives
- Commercial Account Managers
- Coverage Analysts
- Risk Advisors
- Renewal Specialists
- Agency Principals
- Other authorized insurance professionals

---

# Required Inputs

At minimum, provide:

1. Expiring policy or program information
2. Renewal policy or program information

Recommended format:

```text
Expiring:
[PASTE]

Renewal:
[PASTE]
```

The information may include:

- Premium
- Limits
- Deductibles
- Retentions
- Sublimits
- Endorsements
- Exclusions
- Exposure values
- Policy structure
- Carrier
- Coverage lines
- Renewal notes

If either side is incomplete, identify the limitation before drawing firm conclusions.

---

# Recommended Inputs

The following inputs materially improve the analysis:

- Client name
- Industry
- Renewal date
- Expiring carrier
- Renewal carrier
- Expiring premium
- Renewal premium
- Expiring exposure basis
- Renewal exposure basis
- Revenue
- Payroll
- Vehicle count
- Property values
- Business-income values
- Employee count
- Locations
- Limits
- Deductibles
- Retentions
- Sublimits
- Endorsements
- Exclusions
- Loss history
- Renewal rate indication
- Underwriter explanation
- Market feedback
- Client priorities
- Client risk tolerance
- Contractual requirements
- Negotiation history
- Proposed alternatives

---

# Preferred Source Documents

Where available, prioritize:

1. Current renewal quote or proposal
2. Current renewal endorsements
3. Current renewal declarations
4. Expiring policy
5. Expiring endorsements
6. Expiring declarations
7. Current exposure schedules
8. Prior-year exposure schedules
9. Carrier renewal letter
10. Agency comparison worksheet
11. Client-confirmed information
12. Producer notes

Do not compare summary-level terms as though they represent the full policies when detailed documents are unavailable.

---

# Source Hierarchy

When information conflicts, prioritize:

1. Current renewal carrier-issued documents
2. Expiring carrier-issued policy documents
3. Current endorsements
4. Current declarations and schedules
5. Agency-verified information
6. Client-provided information
7. Internal notes

When sources conflict:

- Identify the discrepancy
- Do not silently select a value
- Use the most authoritative current source where appropriate
- Flag material differences for review

---

# Comparison Basis Standard

Before comparing renewal terms, establish whether the comparison is truly like-for-like.

Confirm whether there were changes in:

- Revenue
- Payroll
- Property values
- Vehicle count
- Employees
- Locations
- Limits
- Deductibles
- Retentions
- Coverage structure
- Carrier
- Exposure period
- Policy term

A premium increase may not reflect a rate increase if the exposure basis also increased.

Do not compare total premium alone without considering exposure changes.

---

# Evidence Classification

Every material comparison finding should be treated as one of the following.

## Documented Change

Directly supported by expiring and renewal documents.

Example:

> The property deductible increased from $10,000 to $25,000.

---

## Calculated Change

Derived from supplied values.

Example:

> Total premium increased approximately 11.8%.

---

## Likely Driver

A reasonable explanation for a change based on the supplied information.

Example:

> Part of the property premium increase appears exposure-driven because reported values increased 9%.

---

## Coverage Impact Observation

A professional interpretation of what the change means.

Example:

> The higher deductible shifts an additional $15,000 of first-dollar property loss back to the client.

---

## Requires Form Review

A difference cannot be fully evaluated without policy wording.

Example:

> The renewal summary references a new exclusion, but the endorsement wording is required to determine its full effect.

---

# Confidence Classification

Where useful, classify findings:

### High Confidence

Supported directly by comparable expiring and renewal information.

### Moderate Confidence

Strongly suggested by the supplied information but dependent on one or more unresolved details.

### Low Confidence

Possible but requires meaningful policy or exposure confirmation.

Do not overstate certainty.

---

# Core Principle

## Compare the Decision, Not Just the Documents

A renewal comparison is valuable only if it helps the client understand the practical decision.

For every material change, ask:

1. What changed?
2. Why did it change?
3. What does it cost?
4. What does it do to protection?
5. What risk does the client now retain?
6. What should the client do about it?

---

# Workflow

Follow the workflow in order unless circumstances clearly require another sequence.

---

## Step 1 — Establish the Comparison Scope

Identify:

- Client
- Policy period
- Expiring carrier
- Renewal carrier
- Lines being compared
- Documents reviewed
- Whether the comparison is complete or partial

Do not imply a full-program comparison if only one line is supplied.

---

## Step 2 — Establish the Baseline

For the expiring program, identify:

- Premium
- Coverage lines
- Limits
- Deductibles
- Retentions
- Sublimits
- Major endorsements
- Major exclusions
- Exposure basis
- Carrier
- Program structure

This becomes the comparison baseline.

---

## Step 3 — Capture Renewal Terms

For the renewal, identify the same fields.

Use consistent categories so differences are visible.

---

## Step 4 — Reconcile Exposure Changes

Compare:

- Revenue
- Payroll
- Property values
- Vehicles
- Employees
- Locations
- Sales
- Subcontractor costs
- Other rating bases

Calculate material changes when possible.

---

# Exposure Change Standard

When premium changes, separate:

### Exposure Change

Change caused by growth or contraction in the underlying business.

### Rate Change

Change in price per unit of exposure.

### Coverage Change

Change caused by adding, removing, broadening, or restricting coverage.

### Structure Change

Change caused by deductible, retention, layer, limit, or program design.

### Market Change

Change related to carrier appetite, catastrophe load, reinsurance, or market conditions.

Do not attribute the entire premium difference to “rate” unless supported.

---

## Step 5 — Calculate Premium Change

Where data permits, calculate:

- Dollar change
- Percentage change
- Premium by line
- Premium contribution by line

Use:

```text
Premium Change = Renewal Premium - Expiring Premium
```

and:

```text
Premium Change % = (Renewal Premium - Expiring Premium) / Expiring Premium
```

If exposure changed materially, explain that the raw premium percentage is not the same as a pure rate change.

---

# Calculation Integrity Standard

When calculating renewal changes:

- Use documented values
- Identify the baseline
- State the denominator
- Avoid false precision
- Do not calculate rate change without the underlying exposure basis
- Distinguish premium change from rate change

---

## Step 6 — Identify Limit Changes

Compare:

- Per-occurrence limits
- Aggregate limits
- Property limits
- Business-income limits
- Auto limits
- Umbrella / excess limits
- Cyber limits
- Professional liability limits
- Sublimits

Classify each change as:

- Improved
- Reduced
- Unchanged
- Requires Review

---

## Step 7 — Identify Deductible and Retention Changes

Compare:

- Property deductible
- Auto physical damage deductible
- Cyber retention
- Professional liability retention
- Wind/hail deductible
- Named storm deductible
- Self-insured retention
- Waiting period

Explain the additional amount of risk retained by the client when supportable.

---

## Step 8 — Identify Coverage Enhancements

Look for improvements such as:

- Higher limits
- Lower deductibles
- Broader endorsements
- New coverage
- Improved sublimits
- Added locations
- Improved business-income terms
- Broader cyber protection
- Better umbrella structure
- Reduced exclusions
- Improved contractual coverage

Do not characterize a change as an enhancement without support.

---

## Step 9 — Identify Coverage Reductions

Look for:

- Lower limits
- Higher deductibles
- Higher retentions
- New exclusions
- Reduced sublimits
- Narrower territory
- New warranties
- New protective safeguards
- Reduced business-income protection
- Restricted endorsements
- Reduced umbrella scope

These should be clearly distinguished from cost increases.

---

## Step 10 — Identify New Exclusions or Limitations

Review renewal terms for new:

- Exclusions
- Sublimits
- Conditions
- Reporting requirements
- Deductibles
- Protective safeguards
- Coinsurance requirements
- Coverage restrictions

Where exact wording is unavailable, classify as:

> Requires form review.

---

## Step 11 — Identify Removed Restrictions

Also look for improvements where:

- An exclusion was removed
- A restriction was broadened
- A sublimit increased
- A waiting period decreased
- A deductible decreased
- Coverage territory expanded

Do not focus only on negative changes.

---

## Step 12 — Identify Program Structure Changes

Evaluate changes involving:

- Carrier
- Package vs. monoline
- Primary vs. excess
- Layering
- Attachment points
- Deductible structure
- Retention structure
- Claims-made vs. occurrence
- Shared limits
- Aggregate structure
- Multi-line placement

Explain the practical effect.

---

## Step 13 — Identify Cost Drivers

Determine which factors appear to be contributing to the renewal cost.

Potential drivers:

- Exposure growth
- Rate increase
- Loss history
- Large claims
- Catastrophe pricing
- Higher limits
- Broader coverage
- Carrier change
- Reduced deductible
- Increased payroll
- Increased vehicle count
- Increased property values
- New locations

Only identify drivers supported by the available information.

---

## Step 14 — Separate Controllable and External Drivers

Where useful, distinguish:

### Controllable / Influencable

- Deductibles
- Limits
- Risk controls
- Claims management
- Exposure accuracy
- Program structure
- Market strategy

### Less Controllable

- Market conditions
- Catastrophe load
- Reinsurance
- Industry loss trends
- Regulatory changes

This helps guide negotiation.

---

## Step 15 — Evaluate Protection Impact

For each material change, determine whether protection:

### Improved

The client transfers more risk or gains broader protection.

### Reduced

The client retains more risk or loses protection.

### Unchanged

No material change identified.

### Unclear

Further policy review required.

---

# Protection Impact Standard

Do not classify protection based solely on premium.

A higher premium may accompany:

- Better protection
- Worse protection
- Similar protection

The client decision should consider both.

---

## Step 16 — Identify Risks Introduced

Examples:

- Higher retained property loss
- New exclusion
- Reduced umbrella
- Lower cyber sublimit
- More restrictive reporting requirement
- Higher catastrophe deductible
- New coverage gap between primary and excess

Explain the business consequence.

---

## Step 17 — Identify Risks Reduced

Examples:

- Higher umbrella limits
- Broader business-income protection
- New cyber coverage
- Lower deductible
- Broader equipment coverage
- Improved HNOA protection
- Removed exclusion

Explain the improvement.

---

## Step 18 — Identify Risks That Remain Unchanged

Some material exposures may remain exactly as before.

Examples:

- Umbrella remains low
- Business-income limit remains unchanged despite revenue growth
- Cyber remains absent
- Pollution exclusion remains
- Property valuation concern remains

Unchanged does not mean adequate.

Avoid implying that continuation automatically means sufficiency.

---

## Step 19 — Identify Decision-Critical Changes

Not every change belongs in the executive summary.

Prioritize items that materially affect:

- Cost
- Protection
- Retained risk
- Contract compliance
- Operational resilience
- Claim outcomes
- Client priorities

---

## Step 20 — Identify Negotiation Opportunities

Where supported, identify opportunities such as:

- Reduce increase
- Restore expiring wording
- Remove new exclusion
- Improve deductible
- Increase sublimit
- Add endorsement
- Clarify wording
- Obtain alternate deductible
- Obtain alternate limit
- Request incumbent reconsideration

Do not assume carriers will agree.

---

## Step 21 — Identify Client Decision Options

Where useful, frame choices.

Example:

### Option A — Accept Renewal as Presented

Benefit:
[Benefit]

Trade-off:
[Trade-off]

### Option B — Increase Deductible

Benefit:
Potential premium relief.

Trade-off:
Higher retained risk.

### Option C — Restore Coverage

Benefit:
Stronger protection.

Trade-off:
Potential additional premium.

Only include realistic alternatives.

---

## Step 22 — Determine Comparison Readiness

Classify the information.

### Comparison Ready

Expiring and renewal information are sufficiently complete and comparable.

### Conditionally Ready

Useful comparison is possible, but material terms or exposures remain unresolved.

### Not Ready

The information is too incomplete or non-comparable to support a reliable analysis.

Do not force a firm conclusion from incomplete summaries.

---

# Trade-Off Transparency Standard

For each recommendation or major change, identify:

1. What the client gains
2. What the client gives up
3. What risk remains
4. What must be confirmed

This is especially important when cost-saving options reduce protection.

---

# Materiality / Prioritization Framework

Prioritize findings using:

| Factor | Question |
|---|---|
| Premium Impact | How much does it change cost? |
| Coverage Impact | Does it materially change protection? |
| Retained Risk | Is the client taking on more loss? |
| Severity | Could the change affect a major claim? |
| Frequency | Could the issue arise regularly? |
| Contractual Impact | Could it affect client obligations? |
| Operational Impact | Could it affect business continuity? |
| Decision Relevance | Does the client need this to decide? |
| Confidence | How well supported is the finding? |

Use professional judgment.

---

# Decision Rules

## Compare Like for Like

Do not present premium changes as meaningful without considering exposure differences.

---

## Premium Change Is Not Rate Change

Never use the terms interchangeably without support.

---

## Coverage Improvements and Reductions Must Be Explicit

Do not bury material protection changes.

---

## Unchanged Does Not Mean Adequate

A weak expiring term may remain weak at renewal.

---

## Do Not Infer Policy Wording

If full endorsements are unavailable, say:

> Requires form review.

---

## Cost Savings Need Trade-Off Disclosure

If a recommendation reduces premium by increasing retained risk or reducing protection, disclose it clearly.

---

## Materiality Over Exhaustiveness

Focus on the differences that should influence the client’s decision.

---

# Output Requirements

Use the following structure unless the user requests another format.

---

# Commercial Renewal Comparison

## Renewal Snapshot

**Client:** [Client]  
**Expiring Carrier:** [Carrier]  
**Renewal Carrier:** [Carrier]  
**Renewal Date:** [Date]

**Expiring Premium:** [Amount]  
**Renewal Premium:** [Amount]  
**Dollar Change:** [Amount]  
**Percentage Change:** [Percentage]

---

# 1. Comparison Readiness

**Status:** Comparison Ready / Conditionally Ready / Not Ready

### Information Reviewed

[List]

### Material Gaps

[List]

---

# 2. Executive Renewal Perspective

Provide a concise summary answering:

- How much did cost change?
- What appears to drive the change?
- Did protection improve or decline?
- What is the most important issue?
- What should the client consider before accepting renewal?

---

# 3. Key Changes

Use a table.

| Area | Expiring | Renewal | Change | Client Impact |
|---|---|---|---|---|
| [Area] | [Old] | [New] | Improved / Reduced / Changed / Same | [Impact] |

Prioritize material changes.

---

# 4. Cost Comparison

## Total Premium

**Expiring:** [Amount]  
**Renewal:** [Amount]  
**Change:** [Amount / Percentage]

## Apparent Cost Drivers

| Driver | Impact | Evidence |
|---|---|---|
| Exposure growth | [Impact] | [Evidence] |
| Rate change | [Impact] | [Evidence] |
| Coverage change | [Impact] | [Evidence] |

Do not call something a rate change without sufficient support.

---

# 5. Coverage Improvements

For each material improvement:

## [Improvement]

**Expiring:**  
[Old]

**Renewal:**  
[New]

**Why it matters:**  
[Impact]

---

# 6. Coverage Reductions / Increased Retained Risk

For each:

## [Change]

**Expiring:**  
[Old]

**Renewal:**  
[New]

**Client impact:**  
[Impact]

**Potential action:**  
[Action]

---

# 7. New Exclusions, Sublimits, or Conditions

| Change | Potential Impact | Review Needed |
|---|---|---|
| [Issue] | [Impact] | [Action] |

If wording is unavailable, say so.

---

# 8. Risk Impact Summary

## Risks Introduced

- [Risk]

## Risks Reduced

- [Risk]

## Risks Unchanged

- [Risk]

## Risks Requiring Further Review

- [Risk]

---

# 9. Decision-Critical Issues

Rank the most important issues.

| Priority | Issue | Why It Matters | Recommended Action |
|---|---|---|---|
| 1 | [Issue] | [Impact] | [Action] |

---

# 10. Recommended Actions

Provide practical actions in order.

Examples:

1. Request deductible alternatives.
2. Obtain wording for the new exclusion.
3. Confirm business-income limit.
4. Negotiate restoration of expiring endorsement.
5. Validate exposure changes.
6. Decide whether premium relief justifies additional retained risk.

---

# 11. Client Decision Framework

Where useful:

| Option | Cost | Protection | Retained Risk | Key Trade-Off |
|---|---|---|---|---|
| Accept Renewal | [ ] | [ ] | [ ] | [ ] |
| Alternative 1 | [ ] | [ ] | [ ] | [ ] |
| Alternative 2 | [ ] | [ ] | [ ] | [ ] |

---

# 12. Recommended Renewal Decision

### Recommended Approach

[Recommendation]

### Why

[Reason]

### What the Client Gains

[Benefit]

### What the Client Gives Up / Retains

[Trade-off]

### What Still Needs Confirmation

[Issue]

---

# Assumptions & Items Requiring Confirmation

Use whenever inference affects the comparison.

| Assumption | Basis | Confidence | Confirmation Needed |
|---|---|---|---|
| [Assumption] | [Reason] | High / Moderate / Low | [Action] |

---

# Quality Checks

Before completing the Skill, verify:

- [ ] Expiring and renewal periods are correctly identified
- [ ] Expiring and renewal carriers are correctly identified
- [ ] Premium values are supported
- [ ] Dollar and percentage changes are calculated correctly
- [ ] Exposure changes are considered
- [ ] Premium change is distinguished from rate change
- [ ] Limits are compared
- [ ] Deductibles and retentions are compared
- [ ] Sublimits are compared
- [ ] Endorsements are considered
- [ ] New exclusions are identified where available
- [ ] Removed restrictions are identified
- [ ] Program structure changes are considered
- [ ] Cost drivers are evidence-based
- [ ] Protection improvements are identified
- [ ] Protection reductions are identified
- [ ] Increased retained risk is disclosed
- [ ] Unchanged risks are considered
- [ ] Unchanged does not imply adequate
- [ ] Decision-critical issues are prioritized
- [ ] Recommendations identify trade-offs
- [ ] No unsupported policy wording is invented
- [ ] Comparison readiness is stated
- [ ] Final output is understandable to a business owner

---

# Failure Conditions

The Skill should not be considered complete if:

- The output merely lists expiring and renewal terms
- Premium change is automatically described as rate change
- Exposure changes are ignored
- Material coverage reductions are buried
- Improvements are ignored
- Deductible changes are not translated into retained risk
- New exclusions are asserted without wording
- Unchanged coverage is automatically treated as adequate
- Material cost drivers are unsupported
- Client decision implications are unclear
- Recommendations do not disclose trade-offs
- No practical next steps are provided
- Incomplete comparison data is presented as complete

If any failure condition exists, revise before finalizing.

---

# Guardrails

## Do Not Fabricate Comparison Terms

Never invent:

- Premium
- Limits
- Deductibles
- Retentions
- Sublimits
- Endorsements
- Exclusions
- Exposures
- Rate changes
- Carrier explanations

---

## Do Not Call Premium Change a Rate Change Without Evidence

Premium may change because of:

- Exposure
- Rate
- Coverage
- Structure
- Carrier
- Multiple factors

---

## Do Not Guarantee Coverage

Never state:

- Renewal coverage definitely applies
- A claim will be covered
- An exclusion definitely applies

without appropriate authoritative support.

---

## Do Not Hide Reduced Protection

If the renewal:

- Raises deductibles
- Reduces limits
- Adds exclusions
- Reduces sublimits
- Increases retentions
- Narrows coverage

state the impact clearly.

---

## Do Not Treat Lower Premium as Automatically Better

A lower premium may result from:

- Lower limits
- Higher deductibles
- Narrower coverage
- Greater retained risk

Explain the trade-off.

---

## Do Not Treat Higher Premium as Automatically Worse

A higher premium may provide materially stronger protection.

Evaluate the complete decision.

---

## No Legal Advice

Legal, contractual, or regulatory implications may be identified.

Do not provide unsupported legal conclusions.

---

## Protect Confidential Information

Use only information necessary for the renewal analysis.

Do not unnecessarily expose:

- Claimant details
- Employee-sensitive information
- Personally identifiable information
- Financial account information
- Proprietary internal agency information

---

## Preserve Human Accountability

This Skill supports the insurance professional.

The authorized insurance professional remains responsible for:

- Policy comparison
- Coverage recommendations
- Client communication
- Negotiation
- Carrier interaction
- Binding decisions
- Compliance
- Professional judgment

### Your people make the decisions. Your AI Teammates do the work.

---

# Professional Tone Standard

Write like an experienced commercial insurance advisor walking a business owner through renewal.

The tone should be:

- Clear
- Concise
- Practical
- Analytical
- Decision-oriented
- Client-friendly
- Transparent

Avoid:

- Technical overload
- Carrier jargon
- Long form-by-form commentary
- Fear-based language
- Unsupported certainty
- Excessive disclaimers
- Treating premium as the only decision factor

The client should understand exactly what changed and why it matters.

---

# Example

## Example Request

```text
Expiring:

Carrier: Carrier A
Premium: $420,000
Property Deductible: $10,000
Umbrella: $5,000,000
Business Income: $2,000,000
Cyber: $1,000,000
Property TIV: $18,000,000

Renewal:

Carrier: Carrier A
Premium: $486,000
Property Deductible: $25,000
Umbrella: $5,000,000
Business Income: $2,000,000
Cyber: $1,000,000
Property TIV: $20,000,000
New wind/hail deductible: 2%
```

---

## Example Output Excerpt

### Executive Renewal Perspective

The renewal premium increased from $420,000 to $486,000, an increase of $66,000 or approximately 15.7%.

However, not all of that increase should automatically be viewed as rate deterioration.

Reported property values increased from $18 million to $20 million, or approximately 11.1%, meaning part of the premium increase is exposure-driven.

At the same time, the renewal shifts more property risk back to the client through two changes:

- The standard property deductible increases from $10,000 to $25,000.
- A new 2% wind/hail deductible is being introduced.

The $5 million umbrella and $1 million cyber limit remain unchanged.

The most important renewal issue is therefore not only the 15.7% premium increase—it is that the client is paying more while also accepting more retained property risk.

---

### Key Changes

| Area | Expiring | Renewal | Change | Client Impact |
|---|---|---|---|---|
| Premium | $420,000 | $486,000 | +15.7% | Higher annual cost |
| Property TIV | $18M | $20M | +11.1% | More insured exposure |
| Property Deductible | $10,000 | $25,000 | Increased | Client retains additional first-dollar property loss |
| Wind/Hail Deductible | Not shown | 2% | New restriction | Potentially material retained catastrophe loss |
| Umbrella | $5M | $5M | Unchanged | Catastrophic liability protection unchanged |
| Cyber | $1M | $1M | Unchanged | Cyber limit unchanged despite renewal cost increase |

---

### Risk Impact

#### Risks Introduced

**Higher retained property risk**

The client will absorb more of a routine property loss before coverage begins.

**Percentage wind/hail deductible**

The financial impact may be materially larger than a flat deductible depending on how the percentage is applied under the policy.

The exact wording should be reviewed.

#### Risks Unchanged

The umbrella and cyber limits remain unchanged.

That does not necessarily mean those limits are adequate; it only means the renewal did not change them.

---

### Recommended Actions

1. Request an alternative with the expiring $10,000 property deductible.
2. Obtain the exact 2% wind/hail deductible wording and calculation basis.
3. Ask the carrier to separate the impact of increased property values from underlying rate change.
4. Evaluate whether the additional retained property risk produces meaningful premium savings.
5. Reconfirm whether $5 million umbrella and $1 million cyber limits still align with current exposures.

---

# Original Prompt

The original Apeironix AI Insurance Automation Guide prompt that inspired this Skill:

> You are a commercial insurance advisor helping a client understand the differences between their expiring policy and renewal terms. Your goal is to provide a clear, decision-ready comparison that highlights meaningful changes and their impact.
>
> Review the information below and focus on what has changed and why it matters.
>
> Expiring:
> [PASTE]
>
> Renewal:
> [PASTE]
>
> Evaluate the comparison as if you are presenting it to a client who wants clarity, not technical detail.
>
> Structure your response as:
>
> - Key changes between expiring and renewal coverage
> - Cost differences and what is driving those changes
> - Coverage impact, including improvements or reductions in protection
> - Risks that have been introduced, reduced, or remain unchanged
> - Recommended actions or considerations for the client
>
> Be specific and practical. Prioritize clarity and decision-making over technical explanation.

---

# Evolution From Prompt to Skill

The original prompt established the goal of comparing expiring and renewal terms in a client-friendly way.

This Skill expands that prompt into a reusable Renewal Intelligence workflow by adding:

- Required inputs
- Recommended inputs
- Preferred source documents
- Source hierarchy
- Comparison Basis Standard
- Evidence classification
- Exposure reconciliation
- Exposure Change Standard
- Premium-change calculations
- Calculation Integrity Standard
- Limit comparison
- Deductible and retention comparison
- Coverage enhancement analysis
- Coverage reduction analysis
- Exclusion and limitation review
- Program-structure analysis
- Cost-driver analysis
- Controllable vs. external driver classification
- Protection Impact Standard
- Risk-introduced / reduced / unchanged framework
- Decision-critical change prioritization
- Negotiation opportunities
- Client decision options
- Comparison-readiness framework
- Trade-Off Transparency Standard
- Quality-control checklist
- Failure conditions
- Insurance-specific guardrails
- Example implementation

The purpose is to transform a renewal comparison prompt into a reusable **Renewal Comparison Intelligence Skill**.

---

# Related Skills

Related Apeironix Skills include:

- [Commercial Insurance Coverage Gap Analysis](../03-coverage-gap-analysis/SKILL.md)
- [Commercial Insurance Renewal Strategy Builder](../04-renewal-strategy-builder/SKILL.md)
- [Commercial Insurance Executive Proposal Summary](../06-executive-proposal-summary/SKILL.md)
- [Commercial Insurance Exposure Summary Builder](../08-exposure-summary-builder/SKILL.md)
- [Commercial Insurance Policy Explanation in Plain English](../11-policy-explanation-plain-english/SKILL.md)
- [Commercial Insurance Coverage Explanation](../12-coverage-explanation/SKILL.md)
- Policy Comparison
- Renewal Coverage Change Summary
- Premium Change Analysis
- Coverage Recommendation Summary
- Client Renewal Presentation

Links should be added as those Skills are published.

---

# Suggested Invocation

```text
Perform a Commercial Insurance Renewal Comparison.

Client:
[OPTIONAL]

Renewal Date:
[OPTIONAL]

Expiring:
[PASTE]

Renewal:
[PASTE]

Client Priorities:
[OPTIONAL]

Known Exposure Changes:
[OPTIONAL]

Known Carrier Explanation:
[OPTIONAL]
```

---

# Minimum Viable Invocation

```text
Expiring:
[PASTE]

Renewal:
[PASTE]
```

---

# Version History

## 1.0.0

Initial public release.

Enhancements from the original Prompt #13 include:

- Comparison Basis Standard
- Source hierarchy
- Evidence classification
- Exposure reconciliation
- Exposure Change Standard
- Premium vs. rate distinction
- Calculation Integrity Standard
- Limit and retention comparison
- Coverage enhancement/reduction framework
- Program-structure analysis
- Cost-driver classification
- Protection Impact Standard
- Risk-introduced/reduced/unchanged analysis
- Decision-critical prioritization
- Negotiation framework
- Client decision options
- Comparison-readiness classification
- Trade-Off Transparency Standard
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
- Renewal analysis
- Coverage comparison
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
