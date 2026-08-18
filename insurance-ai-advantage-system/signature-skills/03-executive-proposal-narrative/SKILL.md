---
name: executive-proposal-narrative
title: Commercial Insurance Executive Proposal Narrative
collection: insurance-ai-advantage-system-signature-skills
system: insurance-ai-advantage-system
skill_tier: signature
signature_skill_number: 3
category: commercial-pc
capability: proposal-intelligence
flywheel_stage: decision
orchestration_role: proposal-recommendation
primary_role: commercial-insurance-advisor
secondary_roles:
  - commercial-insurance-producer
  - commercial-account-executive
  - commercial-account-manager
  - risk-advisor
  - proposal-specialist
  - agency-principal
template_version: 2.2
version: 1.0.0
maintainer: Apeironix
license: Apache-2.0
status: public
---

# Commercial Insurance Executive Proposal Narrative

## Signature Skill

**Insurance AI Advantage System — Signature Skill #3**

This is a fully engineered Apeironix Signature Skill designed to operate as part of the Insurance AI Advantage System.

Unlike a basic proposal-writing prompt, this Skill combines:

- Current-state analysis
- Option normalization
- Like-for-like comparison
- Coverage and cost interpretation
- Recommendation logic
- Trade-off transparency
- Client-priority alignment
- Decision readiness
- Plain-language translation
- Executive communication
- Human review
- Downstream implementation handoff

The objective is not simply to create a polished proposal.

The objective is to convert technical insurance alternatives into a clear business decision that a client can understand, evaluate, and act on confidently.

---

# Purpose

Transform current-program information, competing insurance options, pricing, coverage differences, and advisor recommendations into a concise, client-ready executive proposal narrative.

This Skill is designed to help the insurance professional:

- Explain the client's current situation clearly
- Identify the business implications of the current program
- Simplify competing insurance options
- Normalize materially different alternatives
- Translate technical insurance differences into real-world impact
- Explain cost differences without reducing the decision to price
- Make a clear recommendation
- Explain why the recommendation fits the client's risk and priorities
- Disclose meaningful trade-offs
- Identify residual risk
- Clarify what requires client decision
- Define the next implementation step
- Build trust through transparent reasoning

The objective is **not** to overwhelm the client with every quote detail.

The objective is to answer:

> What are our real options, what changes between them, which one makes the most sense for this business, and why?

---

# Core Outcome

A successful execution should allow the client to quickly understand:

1. Where the current insurance program stands
2. What business or coverage issues are driving the decision
3. What realistic options are available
4. How the options differ
5. What the pricing differences actually represent
6. What the client gains and gives up with each option
7. Which solution is recommended
8. Why that recommendation best aligns with the client's risks and priorities
9. What risk remains after the recommendation
10. What the client must decide
11. What happens next

The finished narrative should make the decision **easier**, not merely make the proposal look better.

---

# Role in the Insurance AI Advantage System

This Signature Skill operates primarily within the **Decision and Proposal Intelligence** stage of the Insurance AI Advantage System.

## Upstream Inputs May Include

- Coverage & Risk Advisory Analysis
- Renewal Comparison Analysis
- Quote Intelligence
- Carrier Placement Strategy
- Carrier Quotes
- Current Policy Data
- Exposure Intelligence
- Claims Intelligence
- Client Priorities
- Renewal Strategy
- Underwriter Feedback

## Primary Function

Convert insurance alternatives into a clear, business-owner-level recommendation.

## Downstream Workflows May Include

- Client Proposal Presentation
- Executive Decision Meeting
- Coverage Selection
- Binding Instructions
- Implementation
- Client Communication
- Policy Issuance
- Renewal Documentation
- Client Decision Record
- Carrier Placement Outcome
- Carrier Behavior Intelligence

The output should therefore support both client communication and structured downstream execution.

---

# Best Used For

Use this Skill for:

- Commercial insurance proposals
- Renewal proposals
- New-business proposals
- Multi-carrier quote presentations
- Incumbent-vs-alternative comparisons
- Program restructuring proposals
- Deductible alternatives
- Limit alternatives
- Coverage enhancement proposals
- Package restructuring
- Alternative funding decisions where applicable
- Executive insurance reviews
- CFO / owner presentations
- Multi-line commercial programs
- Complex account decisions

It is especially useful where the client must weigh:

- Cost
- Coverage
- Retention
- Carrier quality
- Program structure
- Risk tolerance
- Contract requirements
- Operational impact

---

# Do Not Use This Skill As

This Skill is not a substitute for:

- Full quote comparison
- Policy-form review
- Formal coverage opinion
- Binding instructions
- Carrier confirmation
- Legal advice
- Actuarial analysis
- Client authorization
- Financial advice
- Formal contract interpretation

This is a **proposal intelligence and client decision-support Skill**.

---

# Intended Users

Primary users:

- Commercial Insurance Advisors
- Commercial Insurance Producers
- Account Executives

Secondary users:

- Account Managers
- Risk Advisors
- Proposal Specialists
- Agency Principals
- Placement Specialists
- Coverage Analysts

---

# Required Inputs

At minimum:

```text
Client Name:
[INSERT]

Industry:
[INSERT]

Current Situation:
[INSERT]

Quotes / Options:
[INSERT]

Key Differences:
[INSERT]

Recommendation:
[INSERT]
```

If the recommendation is not supplied, the Skill may develop a recommendation only when enough evidence exists to support one.

---

# Recommended Inputs

Where available, provide:

```text
Client Priorities:
[INSERT]

Current Carrier:
[INSERT]

Current Premium:
[INSERT]

Renewal Premium:
[INSERT]

Current Limits:
[INSERT]

Current Deductibles:
[INSERT]

Current Exclusions:
[INSERT]

Alternative Carriers:
[INSERT]

Quoted Premiums:
[INSERT]

Quoted Limits:
[INSERT]

Quoted Deductibles:
[INSERT]

Coverage Enhancements:
[INSERT]

Coverage Reductions:
[INSERT]

Carrier Differences:
[INSERT]

Claims History:
[INSERT]

Contract Requirements:
[INSERT]

Risk Concerns:
[INSERT]

Client Risk Tolerance:
[INSERT]

Budget Constraints:
[INSERT]

Implementation Timing:
[INSERT]

Advisor Recommendation:
[INSERT]

Recommendation Rationale:
[INSERT]
```

---

# Optional Intelligence Sources

Where authorized and relevant:

- Current policy
- Renewal terms
- Alternative quotes
- Coverage comparison
- Exposure analysis
- Coverage gap analysis
- Loss runs
- Carrier proposals
- Carrier financial-strength information
- Contract requirements
- Client meeting notes
- Risk-control information
- Current premium schedules
- Prior renewal decisions
- AMS
- CRM
- Proposal system

Do not supplement missing quote terms with assumptions unless clearly labeled.

---

# Preferred Source Documents

Prioritize:

1. Current carrier quote or renewal
2. Alternative carrier quotes
3. Current policy and endorsements
4. Current coverage comparison
5. Current exposure information
6. Client-confirmed priorities
7. Contract requirements
8. Claims information
9. Agency analysis
10. Historical proposals
11. Professional inference

---

# Document Completeness Standard

Classify the proposal source set as:

### Complete Enough for Executive Recommendation

The available current and alternative terms reasonably support a decision-ready comparison.

### Partially Complete

A useful proposal can be prepared, but important differences require confirmation.

### Fragmentary

The available terms are insufficient for a reliable recommendation.

Do not hide incomplete quote information behind confident writing.

---

# Document Interaction / Override Standard

When quotes or policies contain:

- Endorsements
- Subjectivities
- Coverage schedules
- Deductible endorsements
- Exclusion changes
- Sublimits
- Carrier-specific forms

consider their interaction before describing the option.

Do not summarize only the declarations or headline premium when an endorsement materially changes protection.

---

# Source Hierarchy

When option information conflicts:

1. Current carrier-issued quote / proposal
2. Current endorsements / terms
3. Current policy wording
4. Carrier clarification
5. Agency comparison
6. Client-confirmed information
7. Historical information
8. Professional inference

Do not select the version that makes the preferred recommendation appear more favorable.

---

# Evidence Classification

Classify material proposal statements as:

## Documented Program Fact

Directly supported by the current or proposed program.

## Calculated Difference

Derived from documented values.

## Coverage Impact Observation

A practical conclusion based on program differences.

## Client Priority

Confirmed client concern or objective.

## Recommendation

Advisor conclusion based on available evidence.

## Assumption

Used provisionally because information is incomplete.

## Requires Confirmation

Material term or impact remains unresolved.

---

# Authority vs. Inference Standard

Distinguish:

### Carrier Terms

What the carrier is actually offering.

### Agency Analysis

How those terms compare.

### Advisor Recommendation

What the advisor believes best fits the client.

### Client Decision

The client's authority to select an option.

### Carrier / Binding Authority

The carrier or authorized insurance professional controls final placement.

AI may support recommendation logic.

It does not bind coverage or make the client's decision.

---

# Scope-of-Explanation Standard

Distinguish between:

### General Insurance Concept

Example:

> A higher deductible generally means the client retains more of each loss.

and:

### Specific Quote Difference

Example:

> Option B increases the property deductible from $10,000 to $25,000.

Do not use general insurance principles as a substitute for quote-specific facts.

---

# Core Principle

## Explain the Decision, Not Just the Insurance

A strong proposal should help the client understand:

- What changed
- Why it matters
- What the alternatives are
- What each option costs
- What each option protects
- What each option gives up
- Why one path is recommended

Do not make the client interpret insurance tables without context.

---

# Executive Clarity Standard

The core proposal narrative should allow a business owner to understand the recommended direction in approximately three minutes.

Prioritize:

1. Situation
2. Problem
3. Options
4. Recommendation
5. Why
6. Trade-offs
7. Expected outcome
8. Decision required

Technical detail should support the decision, not dominate it.

---

# Execution Readiness Standard

Before presenting a client recommendation, classify:

### Decision Ready

Enough information exists to compare the options responsibly and make a recommendation.

### Conditionally Decision Ready

The general direction is supportable, but one or more material terms require confirmation.

### Not Decision Ready

Critical quote, coverage, pricing, or client-priority information is missing.

Do not force a recommendation where the data does not support one.

---

# Comparison Basis / Like-for-Like Standard

Before comparing options, normalize:

- Coverage period
- Named insureds
- Locations
- Exposure basis
- Limits
- Deductibles
- Retentions
- Sublimits
- Exclusions
- Valuation
- Carrier structure
- Umbrella attachment
- Business income
- Optional coverages

Do not compare premium without evaluating whether the underlying protection is equivalent.

---

# Option Normalization Standard

Classify differences as:

### Pricing Difference

Pure cost difference where terms are substantially comparable.

### Coverage Difference

Protection changes materially.

### Retention Difference

Client retains more or less risk.

### Structural Difference

Carrier, program architecture, layering, or policy structure changes.

### Exposure Difference

Quoted exposure basis differs.

### Unknown Difference

Not enough information exists to determine comparability.

This prevents misleading side-by-side comparisons.

---

# Calculation Integrity Standard

Where calculations are used:

```text
Premium Change = Proposed Premium - Current Premium
```

```text
Premium Change % =
(Proposed Premium - Current Premium) / Current Premium
```

Where comparing options:

```text
Option Difference =
Option B Premium - Option A Premium
```

Do not:

- Call premium change a rate change without support
- Calculate percentages from incomplete totals
- Ignore fees or taxes when materially relevant
- Compare different exposure bases without disclosure

---

# Trade-Off Transparency Standard

Every material option should explain:

### What the Client Gains

Examples:

- Broader protection
- Higher limits
- Better carrier fit
- Lower deductible
- Better contract alignment
- Reduced volatility

### What the Client Gives Up

Examples:

- Higher premium
- Higher deductible
- Narrower term
- Carrier change
- More administrative burden

### What Risk Remains

No insurance option removes all risk.

### What Assumptions Support the Comparison

Material assumptions must remain visible.

---

# Recommendation Integrity Standard

A recommendation should be based on a documented rationale.

Possible factors include:

- Risk alignment
- Coverage quality
- Cost
- Deductible
- Limits
- Claims experience
- Contract requirements
- Carrier fit
- Client risk tolerance
- Client priorities
- Operational stability

Do not recommend an option simply because:

- It is cheapest
- It is the incumbent
- It pays more commission
- It is easiest to place

---

# Workflow State Standard

Relevant states may include:

1. Options Received
2. Comparison Validation
3. Data Gaps Identified
4. Options Normalized
5. Recommendation Developed
6. Internal Review
7. Decision Ready
8. Client Presentation
9. Client Questions
10. Client Decision Pending
11. Option Selected
12. Binding Authorized
13. Implementation
14. Completed

Do not confuse:

> Recommendation prepared

with:

> Client approved.

---

# Workflow

## Step 1 — Understand the Client's Current Situation

Summarize:

- Current carrier
- Current structure
- Current premium
- Known issues
- Renewal pressure
- Coverage concerns
- Operational changes
- Client priorities

Do not begin with alternatives.

Begin with why a decision is necessary.

---

## Step 2 — Identify the Client's Decision Criteria

Determine what matters most.

Potential priorities:

- Cost stability
- Coverage breadth
- Contract compliance
- Claims service
- Retention
- Carrier relationship
- Limit protection
- Cash flow
- Ease of administration
- Long-term program stability

Where priorities are unknown, identify them as questions.

---

## Step 3 — Validate Available Options

For each option, capture:

- Carrier
- Premium
- Limits
- Deductibles
- Retentions
- Coverage
- Sublimits
- Exclusions
- Subjectivities
- Special conditions
- Binding requirements

Do not compare incomplete headline numbers.

---

## Step 4 — Normalize the Options

Identify which differences result from:

- Exposure
- Limits
- Deductible
- Coverage
- Carrier
- Structure

Where possible, create a like-for-like basis.

Where not possible, disclose the mismatch.

---

## Step 5 — Identify Current Program Challenges

Focus on meaningful issues such as:

- Cost increase
- Limit misalignment
- Restrictive exclusion
- Contract mismatch
- Deductible issue
- Coverage gap
- Carrier fit
- Claims concern
- Operational change

Do not manufacture dissatisfaction where none exists.

---

## Step 6 — Identify Meaningful Improvements

For each alternative, identify improvements such as:

- Broader coverage
- Better limits
- Lower cost
- Better deductible
- Improved carrier fit
- Better business income
- Reduced restriction
- Contract compliance
- Better program structure

---

## Step 7 — Identify Meaningful Reductions

Also identify:

- Reduced limits
- Higher deductibles
- New exclusions
- Lower sublimits
- Changed valuation
- Removed coverages
- Narrower terms

Do not hide reductions because an option is preferred.

---

## Step 8 — Evaluate Cost

Compare:

- Current premium
- Renewal premium
- Alternative premium
- Fees
- Taxes
- Financing implications where known

Translate cost into business terms.

---

## Step 9 — Evaluate Retained Risk

Consider:

- Deductible
- Retention
- Aggregate retention
- Self-insured exposure
- Claim frequency
- Client liquidity

A cheaper option may create more retained risk.

---

## Step 10 — Evaluate Protection

Consider:

- Limits
- Coverage breadth
- Key exclusions
- Sublimits
- Policy structure
- Contract compliance

A higher-priced option may provide materially better protection.

---

## Step 11 — Evaluate Carrier and Structural Differences

Where relevant:

- Carrier strength
- Market fit
- Claims handling
- Program structure
- Admitted / non-admitted status
- Layering
- Umbrella structure
- Specialty program

Only include supported considerations.

---

## Step 12 — Identify Residual Risk

For the preferred option, explain:

> What still is not solved?

Examples:

- High deductible
- Remaining exclusion
- Limit ceiling
- Contract uncertainty
- Cyber exposure
- Property valuation uncertainty

No recommendation should imply perfect protection.

---

## Step 13 — Develop the Recommendation

The recommendation should answer:

1. Which option?
2. Why?
3. Which client priorities does it address?
4. What meaningful improvement results?
5. What trade-offs exist?
6. What risk remains?

---

# Recommendation Rationale Standard

Use:

**Client Priority → Risk Issue → Option Difference → Recommendation**

Example:

> Because the client's primary concern is protecting against large liability losses while meeting new contract requirements, Option B's higher umbrella limit and broader completed-operations structure outweigh the additional premium.

Avoid:

> Option B is the best option.

without explanation.

---

## Step 14 — Identify Alternative Path

Where useful, explain the second-best path.

Example:

> If minimizing upfront premium is the overriding priority, Option A remains viable, but the client would accept the higher property deductible and lower umbrella limit.

This helps the client make a real decision.

---

## Step 15 — Translate Technical Terms

Examples:

Technical:

> Per-location aggregate endorsement.

Plain language:

> The liability limit can reset by location rather than being shared across all locations.

Technical:

> Replacement cost valuation.

Plain language:

> Covered property is generally valued based on the cost to replace it rather than its depreciated value, subject to policy terms.

Translate only what matters to the decision.

---

## Step 16 — Prepare Executive Summary

The Executive Summary should explain:

- Current situation
- Main challenge
- Recommended direction
- Core reason

Keep it concise.

---

## Step 17 — Explain Current Program Challenges

Focus on the 2–5 issues that actually drive the decision.

---

## Step 18 — Present Options

Simplify.

Avoid reproducing every quote detail.

Use:

- Option
- Cost
- Main strengths
- Main trade-offs
- Best fit

---

## Step 19 — Present the Recommended Solution

Be clear.

Use:

> We recommend...

when the evidence supports the recommendation.

Avoid vague language such as:

> You may want to consider possibly...

---

## Step 20 — Explain Why

Connect recommendation to:

- Exposure
- Client priorities
- Coverage
- Cost
- Retained risk
- Contract needs
- Long-term strategy

---

## Step 21 — Explain Expected Outcome

Describe expected benefits without guaranteeing claim results.

Examples:

- Better alignment with operations
- Improved liability protection
- Improved contract compliance
- Lower retained risk
- More predictable renewal structure
- Reduced premium

Avoid:

> This eliminates the risk.

---

## Step 22 — Define Client Decision

State what must be decided.

Example:

> The primary decision is whether the additional $18,000 annual premium is justified by the higher umbrella limit and broader property protection.

---

# Decision Conversion Standard

This Signature Skill should convert analysis into an explicit decision structure.

For each material decision, identify:

1. Decision required
2. Decision owner
3. Recommended option
4. Evidence supporting recommendation
5. Key trade-off
6. Residual risk
7. Deadline
8. Downstream action

Recommended structure:

| Decision | Owner | Recommendation | Evidence | Trade-Off | Deadline | Next Workflow |
|---|---|---|---|---|---|---|
| [Decision] | Client | [Option] | [Basis] | [Trade-Off] | [Date] | Binding / Quote Revision / Other |

The Skill should not stop at:

> Here are the options.

It should help the authorized human decide what happens next.

---

# Obligation Extraction Standard

Where options or contracts create requirements, capture:

| Requirement | Owner | Trigger | Deadline | Evidence | Source |
|---|---|---|---|---|---|
| [Requirement] | [Owner] | [Trigger] | [Timing] | [Evidence] | [Source] |

Examples:

- Signed application
- Updated values
- Risk-control completion
- Contract limit requirement
- Subjectivity satisfaction

Do not invent deadlines or consequences.

---

# Ownership Standard

Assign ownership for each next action.

Example:

| Action | Owner |
|---|---|
| Select option | Client |
| Confirm subjectivities | Account Executive |
| Request quote revision | Marketing |
| Issue binding instructions | Producer / Authorized Client |
| Update AMS | Account Manager |

---

# Handoff Integrity Standard

When the client selects an option, the handoff to implementation should include:

- Client
- Selected carrier / option
- Selected limits
- Selected deductible / retention
- Effective date
- Binding authorization
- Required subjectivities
- Outstanding documents
- Decision rationale
- Responsible owner

Recommended structure:

```text
Client:
[NAME]

Selected Option:
[OPTION]

Effective Date:
[DATE]

Client Authorization:
[CONFIRMED / PENDING]

Outstanding Requirements:
[LIST]

Implementation Owner:
[ROLE]

Current State:
Decision Made / Binding Pending / Implementation
```

A client decision should not disappear inside meeting notes.

---

# System-of-Record Standard

Where proposal decisions span systems:

| Data | System of Record |
|---|---|
| Current policy | AMS |
| Quotes | Placement / Document Repository |
| Proposal analysis | Proposal / CRM |
| Client decision | CRM / AMS |
| Binding instruction | AMS / Carrier Workflow |
| Final policy | AMS |

Do not allow email alone to become the final record of a material client decision.

---

# Transaction Lineage / Audit Trail Standard

Preserve:

```text
Current Program
    ↓
Carrier Quotes
    ↓
Normalized Comparison
    ↓
Advisor Recommendation
    ↓
Client Decision
    ↓
Binding Instruction
    ↓
Final Policy
```

The final placement should remain traceable to:

- Options presented
- Recommendation
- Client authorization
- Final selected terms

---

# Dynamic Reassessment / Monitoring Trigger Standard

Reassess the proposal if:

- Carrier revises premium
- Coverage terms change
- New exclusion appears
- Client priorities change
- Exposure changes
- New claim occurs
- Quote expires
- Contract requirement changes
- Carrier withdraws terms
- Subjectivity cannot be satisfied

A recommendation based on old terms may no longer be valid.

---

# Governance / Conflict Prevention Standard

Before implementation, check for:

- Quote expiration
- Pending carrier revision
- Duplicate binding instruction
- Existing coverage
- Conflicting client direction
- Missing authorization
- Pending cancellation
- Finance issue
- Carrier subjectivity
- Market-access conflict

Do not implement from an outdated or superseded proposal.

---

# Stop Rules

Stop and escalate when:

- Material quote terms are missing
- Options cannot be normalized
- Recommendation depends on unknown coverage
- Client priorities are unclear
- Quote expired
- Carrier changed terms
- Recommendation requires legal or coverage interpretation beyond authority
- Binding authorization is ambiguous
- Major policy differences have not been reviewed

Do not force certainty where the comparison is incomplete.

---

# Completion Criteria Standard

Proposal analysis is complete when:

1. Current situation is understood
2. Client priorities are identified
3. Options are validated
4. Options are normalized
5. Cost differences are understood
6. Coverage differences are understood
7. Retained-risk differences are understood
8. Trade-offs are disclosed
9. Recommendation is supported
10. Residual risk is identified
11. Client decision is defined
12. Assumptions are disclosed
13. Human review is complete where required
14. Implementation handoff is defined

The broader workflow is complete only when the client decision has been appropriately implemented.

---

# Human Review Escalation Standard

Require elevated human review when:

- Material coverage reduction exists
- Material exclusion exists
- Significant limit reduction exists
- Large premium increase exists
- High deductible / retention exists
- Client would be materially underinsured
- Contract requirement may not be met
- Active claim affects the decision
- Carrier terms are ambiguous
- Recommendation includes major program restructuring
- Client decision could create significant financial harm

AI may prepare the analysis.

Authorized insurance professionals remain responsible for the recommendation.

---

# Internal vs. External Information Boundary Standard

Internal proposal analysis may include:

- Carrier strategy
- Commission
- Market ranking
- Negotiation leverage
- Internal sales strategy
- E&O concerns
- Internal scoring

Client-facing proposal should include only what improves the client's decision.

Do not expose internal strategy without a legitimate reason.

---

# Client Communication Standard

Write for:

- Business owner
- CEO
- CFO
- Executive team

Use:

- Plain language
- Business impact
- Decision framing
- Clear recommendations

Avoid:

- Dense insurance terminology
- Policy-form citations unless necessary
- Carrier jargon
- Long quote-detail dumps

---

# Decision Rules

## Decision Clarity Over Quote Completeness

The client does not need every technical detail in the executive narrative.

---

## Normalize Before Comparing

A cheaper option may simply provide less.

---

## Premium Is One Variable

Do not let cost dominate coverage, risk, or client priorities automatically.

---

## Recommendation Requires Rationale

Explain why.

---

## Trade-Offs Must Be Visible

Do not hide disadvantages of the preferred option.

---

## Residual Risk Must Be Visible

Do not imply perfect protection.

---

## Client Priorities Matter

The same option may not be right for every client.

---

## Avoid Fake Neutrality

If one option is clearly better based on the evidence, recommend it.

---

# Materiality / Prioritization Framework

Evaluate options using:

| Factor | Question |
|---|---|
| Coverage Alignment | How well does the option address material exposure? |
| Financial Impact | What is the premium impact? |
| Retained Risk | What does the client retain? |
| Severity Protection | How well does it address catastrophic exposure? |
| Contract Alignment | Does it satisfy material requirements? |
| Carrier Fit | Is the carrier/program appropriate? |
| Operational Impact | Does the structure create administrative burden? |
| Client Priority | Does the option fit stated objectives? |
| Trade-Off | What is sacrificed? |
| Confidence | How complete and reliable are the terms? |

---

# Output Requirements

Use the following structure unless another format is requested.

# Commercial Insurance Executive Proposal

## 1. Decision Readiness

**Status:** Decision Ready / Conditionally Decision Ready / Not Decision Ready

**Client:** [Client Name]  
**Industry:** [Industry]  
**Decision:** [Primary decision]

### Material Items Requiring Confirmation

- [Item]
- [Item]

---

# 2. Executive Summary

Provide a concise executive-level overview.

Recommended structure:

- Current situation
- Primary challenge
- Recommended direction
- Core reason

Target approximately 100–175 words unless complexity requires more.

---

# 3. Current Program Challenges

Identify 2–5 material issues.

For each:

### [Challenge]

**Current situation:**  
[Fact]

**Why it matters:**  
[Business impact]

---

# 4. Options Overview

| Option | Premium | Primary Strength | Main Trade-Off | Best Fit |
|---|---:|---|---|---|
| Option A | [$] | [Strength] | [Trade-Off] | [Fit] |
| Option B | [$] | [Strength] | [Trade-Off] | [Fit] |

Use only meaningful differences.

---

# 5. Key Differences

| Area | Current / Option A | Option B | Practical Impact |
|---|---|---|---|
| Premium | [ ] | [ ] | [Impact] |
| Limit | [ ] | [ ] | [Impact] |
| Deductible | [ ] | [ ] | [Impact] |
| Coverage | [ ] | [ ] | [Impact] |

---

# 6. Recommended Solution

State the recommendation clearly.

> We recommend [OPTION].

Then summarize the recommended:

- Carrier
- Program
- Limits
- Deductible / retention
- Key coverage structure

---

# 7. Why This Recommendation

Explain the recommendation using:

### Risk Alignment

[Why it fits exposure]

### Client Priorities

[Why it fits objectives]

### Financial Logic

[Why cost is justified]

### Coverage Logic

[Why protection is appropriate]

### Long-Term Consideration

[If relevant]

---

# 8. Recommendation Trade-Offs

### What You Gain

- [Gain]
- [Gain]

### What You Give Up

- [Trade-Off]
- [Trade-Off]

### What Risk Remains

- [Residual risk]

---

# 9. Expected Outcome

Explain what the client should reasonably expect if implemented.

Examples:

- Better alignment with operations
- Improved limit protection
- Better contract compliance
- Reduced retained risk
- Lower premium
- More stable program structure

Do not guarantee claim outcomes.

---

# 10. Client Decision

### Decision Required

[Decision]

### Recommended Choice

[Option]

### Decision Deadline

[Date if known]

### If You Choose the Recommended Option

[Next steps]

### If You Choose the Alternative

[Trade-off / alternative path]

---

# 11. Implementation Requirements

| Requirement | Owner | Timing | Status |
|---|---|---|---|
| [Requirement] | [Owner] | [Timing] | Open / Complete |

---

# 12. Next Steps

| Priority | Action | Owner | Timing | Completion Criteria |
|---|---|---|---|---|
| 1 | [Action] | [Owner] | [Timing] | [Criteria] |

---

# Executive Decision Snapshot

When requested, also provide:

```text
Client:
[NAME]

Current Program:
[CURRENT]

Recommended Option:
[OPTION]

Premium:
[$]

Primary Improvement:
[IMPROVEMENT]

Main Trade-Off:
[TRADE-OFF]

Residual Risk:
[RISK]

Why Recommended:
[REASON]

Decision Required:
[DECISION]

Decision Deadline:
[DATE]

Next Step:
[ACTION]
```

---

# Presentation Version

When requested, provide a presentation-ready version using:

### Where You Are Today

[Current situation]

### What Changed

[Important changes]

### Your Options

[Concise options]

### Our Recommendation

[Recommendation]

### Why

[Reasoning]

### What This Means for Your Business

[Expected outcome]

### Decision

[Required action]

---

# Machine-Readable Proposal Intelligence

When requested, also output fields such as:

```text
client_name
industry
current_carrier
current_premium
current_limit
current_deductible
option_name
option_carrier
option_premium
option_limit
option_deductible
coverage_improvement
coverage_reduction
pricing_difference
retained_risk_difference
option_strength
option_tradeoff
recommended_option
recommendation_reason
client_priority
residual_risk
decision_required
decision_owner
decision_deadline
implementation_action
implementation_owner
decision_readiness
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

- [ ] Current situation is accurately described
- [ ] Client priorities are identified
- [ ] Options are based on current terms
- [ ] Quotes are sufficiently complete
- [ ] Options are normalized
- [ ] Premium comparisons are like-for-like where possible
- [ ] Premium changes are not mislabeled as rate changes
- [ ] Coverage improvements are identified
- [ ] Coverage reductions are identified
- [ ] Deductible / retention differences are identified
- [ ] Material exclusions / restrictions are considered
- [ ] Recommendation has a clear rationale
- [ ] Recommendation aligns with client priorities
- [ ] Trade-offs are disclosed
- [ ] Residual risk is disclosed
- [ ] Assumptions are visible
- [ ] Client decision is explicit
- [ ] Decision owner is clear
- [ ] Implementation handoff is defined
- [ ] Internal strategy is excluded from client output
- [ ] Human review occurs where required
- [ ] No claim or coverage outcome is guaranteed

---

# Failure Conditions

The Skill should not be considered complete if:

- The proposal is primarily a quote dump
- The recommendation is unsupported
- The cheapest option is automatically preferred
- Important coverage reductions are omitted
- Premiums are compared without considering coverage
- Client priorities are ignored
- Trade-offs are hidden
- Residual risk is omitted
- Technical language is not translated
- Options are materially non-comparable without disclosure
- The client decision is unclear
- The next step is undefined
- The proposal reads like marketing copy instead of advisory guidance
- Internal sales strategy appears in the client-facing output
- Binding is implied without authorization

If any failure condition exists, revise or escalate.

---

# Guardrails

## Do Not Fabricate Quote Terms

Never invent:

- Premium
- Limits
- Deductibles
- Retentions
- Coverage
- Endorsements
- Exclusions
- Sublimits
- Carrier terms
- Subjectivities

---

## Do Not Hide Unfavorable Terms

Transparency builds trust.

---

## Do Not Recommend Based Solely on Price

Consider the entire program.

---

## Do Not Guarantee Outcomes

Avoid:

- This will eliminate your risk
- This claim would definitely be covered
- This carrier will definitely pay

---

## Do Not Imply Binding

A recommendation is not binding authority.

---

## Preserve Decision History

Material client decisions should remain traceable.

---

## No Legal Advice

Contract issues may require legal review.

---

## Protect Confidential Information

Do not unnecessarily expose:

- Internal commissions
- Carrier strategy
- Producer compensation
- Negotiation notes
- E&O concerns
- Proprietary agency information
- Confidential client information

---

## Preserve Human Accountability

This Skill supports the insurance professional.

The authorized producer, account executive, coverage analyst, risk advisor, carrier, or client remains responsible for:

- Final recommendation
- Client communication
- Coverage selection
- Binding
- Contract interpretation
- Program implementation
- Professional judgment

### Your people make the decisions. Your AI Teammates do the work.

---

# Professional Tone Standard

Write like a senior commercial insurance advisor presenting directly to a business owner.

The tone should be:

- Clear
- Confident
- Practical
- Executive-level
- Client-centered
- Evidence-based
- Non-technical
- Decision-oriented

Avoid:

- Dense policy language
- Insurance jargon
- Promotional language
- Generic AI wording
- Excessive caveats
- Long detail dumps
- Fake neutrality
- Unsupported certainty

The client should understand both **what** is recommended and **why**.

---

# Example

## Example Request

```text
Client Name:
Northwest Industrial Fabrication

Industry:
Metal Fabrication

Current Situation:
Current program renews at $286,000, up from $248,000. Current umbrella is $2M. Property deductible is $10,000. A new customer contract requires $5M total liability limits.

Quotes / Options:

Option A — Incumbent
Premium: $286,000
GL: $1M / $2M
Auto: $1M
Umbrella: $2M
Property deductible: $10,000

Option B — Alternative Carrier
Premium: $301,500
GL: $1M / $2M
Auto: $1M
Umbrella: $5M
Property deductible: $25,000
Includes broader equipment breakdown coverage.

Key Differences:
Option B costs $15,500 more, provides $3M more umbrella protection and broader equipment breakdown, but increases property deductible by $15,000.

Recommendation:
Option B
```

---

## Example Output

# Commercial Insurance Executive Proposal

## 1. Decision Readiness

**Status:** Decision Ready

**Client:** Northwest Industrial Fabrication  
**Industry:** Metal Fabrication  
**Decision:** Remain with the incumbent program or move to the alternative carrier with higher liability limits and broader property protection.

---

# 2. Executive Summary

Northwest Industrial Fabrication's current program is renewing at $286,000, an increase of approximately $38,000 from the prior year. More importantly, the current $2 million umbrella does not appear to satisfy the company's newly reported customer requirement for $5 million of total liability protection.

We recommend moving to Option B at an annual premium of $301,500.

The alternative costs $15,500 more than the incumbent renewal, but provides a $5 million umbrella, broader equipment breakdown protection, and better alignment with the company's current contractual needs.

The primary trade-off is a higher property deductible, increasing from $10,000 to $25,000.

---

# 3. Current Program Challenges

### Liability Limit Alignment

The current program includes a $2 million umbrella.

The new customer contract reportedly requires $5 million of total liability protection.

That creates a potential mismatch between the current program and the company's contractual obligations.

### Renewal Cost

The incumbent renewal increased from approximately $248,000 to $286,000.

Although Option A is less expensive than Option B, the difference should be evaluated against the protection provided.

---

# 4. Options Overview

| Option | Premium | Primary Strength | Main Trade-Off | Best Fit |
|---|---:|---|---|---|
| Option A — Incumbent | $286,000 | Lower premium and lower property deductible | Only $2M umbrella | Lowest immediate cost |
| Option B — Alternative | $301,500 | $5M umbrella + broader equipment breakdown | $25K property deductible | Stronger liability / contract alignment |

---

# 5. Recommended Solution

**We recommend Option B.**

The additional $15,500 in annual premium provides:

- $3 million of additional umbrella protection
- Better alignment with the reported customer contract
- Broader equipment breakdown protection

The principal trade-off is the increase in the property deductible from $10,000 to $25,000.

---

# 6. Why This Recommendation

### Contract Alignment

The strongest reason for the recommendation is the increased umbrella limit.

If the client's contract does require $5 million of total liability protection, the incumbent structure may not satisfy that requirement.

### Severity Protection

Metal fabrication creates the potential for significant liability losses. The additional umbrella limit provides more protection against severe events.

### Cost Logic

Option B costs approximately 5.4% more than Option A.

That additional cost purchases materially higher liability protection and broader equipment breakdown coverage.

### Retained Risk

The client does retain more property risk because of the higher deductible.

That trade-off should be evaluated against the company's ability to absorb an additional $15,000 on a property claim.

---

# 7. Recommendation Trade-Offs

### What You Gain

- $3M additional umbrella limit
- Better alignment with reported customer requirements
- Broader equipment breakdown protection

### What You Give Up

- $15,500 additional annual premium
- $15,000 higher property deductible

### What Risk Remains

The $5 million umbrella does not remove all catastrophic liability exposure, and the higher property deductible increases the amount the company would retain on certain property claims.

---

# 8. Expected Outcome

If implemented, Option B should provide a program that is better aligned with the company's current contractual requirements and large-loss exposure while preserving a manageable overall insurance structure.

The trade-off is a modestly higher annual insurance cost and greater retained property risk.

---

# 9. Client Decision

### Decision Required

Whether the additional liability protection and broader equipment coverage justify:

- $15,500 of additional annual premium
- A $15,000 increase in the property deductible

### Recommended Choice

**Option B**

### Next Step

Upon client approval, confirm outstanding carrier requirements and issue authorized binding instructions for the selected program.

---

# Original Signature Prompt

The original Insurance AI Advantage System Signature Prompt that inspired this Skill:

> You are a senior commercial insurance advisor preparing a proposal for a client. Your objective is to translate technical insurance information into a clear, structured narrative that helps the client understand their situation, evaluate options, and confidently move forward with a recommendation.
>
> Approach this as if you are presenting directly to a business owner. Focus on clarity, decision-making, and trust—not technical detail. Where needed, translate insurance concepts into plain language that reflects real-world impact.
>
> INPUT DATA:
>
> Client Name: [INSERT]
> Industry: [INSERT]
> Current Situation: [INSERT – current program, issues, concerns]
> Quotes / Options: [PASTE OPTIONS OR SUMMARIZE]
> Key Differences: [INSERT – pricing, coverage, structure]
> Recommendation: [INSERT]
>
> OUTPUT REQUIREMENTS:
>
> Create a structured proposal narrative that allows the client to quickly understand their options and feel confident in the recommended approach.
>
> Organize the response into the following sections:
>
> Executive Summary — a concise overview of the situation and the recommended direction
> Current Program Challenges — key issues or limitations with the existing coverage
> Options Overview — a clear, simplified explanation of available options without unnecessary detail
> Recommended Solution — the proposed approach, presented clearly and confidently
> Why This Recommendation — the reasoning behind the recommendation, tied to the client’s risks and priorities
> Expected Outcome — what the client should expect if the recommendation is implemented
>
> GUIDELINES:
>
> Write for a business owner, not an insurance professional
> Keep language simple, clear, and structured
> Avoid jargon unless it is explained in plain terms
> Emphasize clarity over completeness
> Present the recommendation with confidence, supported by logic and context
> Ensure the client can quickly understand not just what is being proposed, but why it makes sense
>
> EXPECTED OUTCOME:
>
> A clear, compelling proposal narrative that simplifies decision-making, builds trust, and positions the recommended solution as the most logical path forward.

---

# Evolution From Signature Prompt to Signature Skill

The original Signature Prompt already established a strong executive proposal framework.

This Signature Skill advances it by adding:

- Insurance AI Advantage System positioning
- Flywheel-stage metadata
- Orchestration-role metadata
- Upstream and downstream workflow relationships
- Document Completeness Standard
- Document Interaction / Override Standard
- Source hierarchy
- Evidence classification
- Authority vs. Inference Standard
- Executive Clarity Standard
- Decision readiness
- Like-for-like comparison
- Option Normalization Standard
- Calculation Integrity Standard
- Trade-Off Transparency Standard
- Recommendation Integrity Standard
- Workflow states
- Current-program analysis
- Client-priority analysis
- Coverage / cost / retention normalization
- Residual-risk analysis
- Recommendation Rationale Standard
- Alternative-path framing
- Plain-language translation
- Decision Conversion Standard
- Obligation Extraction Standard
- Ownership
- Handoff Integrity
- System-of-Record Standard
- Transaction Lineage
- Dynamic Reassessment
- Governance / Conflict Prevention
- Stop rules
- Completion criteria
- Human Review Escalation
- Internal / External Information Boundary Standard
- Machine-readable proposal intelligence

The progression is:

**Signature Prompt → Signature Skill → Proposal AI Teammate → Decision AI Workforce**

---

# Related Signature Skills

- [Commercial Insurance Underwriter Submission Narrative](../01-underwriter-submission-narrative/SKILL.md)
- [Commercial Insurance Coverage & Risk Advisory Analysis](../02-coverage-risk-advisory-analysis/SKILL.md)
- Renewal Decision Intelligence
- Quote Comparison Intelligence
- Client Executive Presentation
- Binding & Implementation Intelligence

Add live links as Signature Skills are published.

---

# Related Foundational Skills

This Signature Skill may consume or orchestrate output from:

- [Commercial Insurance Coverage Gap Analysis](../../../ai-insurance-automation-guide/03-coverage-gap-analysis/SKILL.md)
- [Commercial Insurance Renewal Strategy Builder](../../../ai-insurance-automation-guide/04-renewal-strategy-builder/SKILL.md)
- [Commercial Insurance Executive Proposal Summary](../../../ai-insurance-automation-guide/06-executive-proposal-summary/SKILL.md)
- [Commercial Insurance Carrier Placement Strategy](../../../ai-insurance-automation-guide/09-carrier-placement-strategy/SKILL.md)
- [Commercial Insurance Renewal Comparison Analysis](../../../ai-insurance-automation-guide/13-renewal-comparison-analysis/SKILL.md)
- [Commercial Insurance Carrier Behavior & Placement Intelligence](../../../ai-insurance-automation-guide/21-carrier-behavior-intelligence/SKILL.md)

---

# Suggested Invocation

```text
Run Signature Skill #3 — Commercial Insurance Executive Proposal Narrative.

Client Name:
[INSERT]

Industry:
[INSERT]

Current Situation:
[INSERT]

Client Priorities:
[OPTIONAL]

Quotes / Options:
[INSERT]

Key Differences:
[INSERT]

Recommendation:
[INSERT]

Contract Requirements:
[OPTIONAL]

Claims / Risk Context:
[OPTIONAL]

Decision Deadline:
[OPTIONAL]
```

---

# Minimum Viable Invocation

```text
Client Name:
[INSERT]

Industry:
[INSERT]

Current Situation:
[INSERT]

Quotes / Options:
[INSERT]

Key Differences:
[INSERT]

Recommendation:
[INSERT]
```

---

# Version History

## 1.0.0

Initial public release.

Third Signature Skill published under the Insurance AI Advantage System using the Apeironix Gold Standard Template v2.2.

---

# About the Insurance AI Advantage System

The Insurance AI Advantage System is an operating framework for transforming insurance expertise into connected AI capabilities.

The system is designed around a simple progression:

**Foundational Skills → Signature Skills → AI Teammates → AI Workforce → AI Operating Layer**

### Foundational Skills

Make individual insurance expertise repeatable.

### Signature Skills

Combine multiple reasoning disciplines, workflow controls, structured data, human decision boundaries, and downstream handoffs into fully engineered operational capabilities.

### AI Teammates

Apply those capabilities to specific agency roles and workflows.

### AI Workforce

Coordinates multiple AI Teammates across the agency.

### AI Operating Layer

Connects AI work across CRM, AMS, carrier portals, documents, email, financial systems, and other agency technology.

### Your people make the decisions. Your AI Teammates do the work.

**Keep your systems. Activate an AI Workforce.**

---

# About Apeironix

Apeironix develops AI Teammates and reusable AI Skills designed around real insurance workflows.

Our goal is to give insurance professionals more capacity for:

- Judgment
- Relationships
- Client service
- Proposal strategy
- Coverage advisory
- Decision support
- Risk analysis
- Growth

while AI handles more of the repetitive work surrounding those responsibilities.

Apeironix is building the AI Operating Layer for insurance agencies.

Learn more at [Apeironix.com](https://apeironix.com).

---

# License

This Skill is made available under the Apache License 2.0.

See the repository `LICENSE` file for complete terms.
