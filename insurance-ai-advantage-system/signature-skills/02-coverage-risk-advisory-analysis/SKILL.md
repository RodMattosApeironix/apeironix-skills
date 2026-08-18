---
name: coverage-risk-advisory-analysis
title: Commercial Insurance Coverage & Risk Advisory Analysis
collection: insurance-ai-advantage-system-signature-skills
system: insurance-ai-advantage-system
skill_tier: signature
signature_skill_number: 2
category: commercial-pc
capability: coverage-intelligence
flywheel_stage: advisory
orchestration_role: coverage-risk-analysis
primary_role: commercial-insurance-coverage-analyst
secondary_roles:
  - commercial-insurance-producer
  - commercial-account-executive
  - commercial-account-manager
  - risk-advisor
  - agency-principal
template_version: 2.2
version: 1.0.0
maintainer: Apeironix
license: Apache-2.0
status: public
---

# Commercial Insurance Coverage & Risk Advisory Analysis

## Signature Skill

**Insurance AI Advantage System — Signature Skill #2**

This is a fully engineered Apeironix Signature Skill designed to operate as part of the Insurance AI Advantage System.

Unlike a single-purpose coverage-review prompt, this Skill combines:

- Operational exposure analysis
- Policy and program interpretation
- Coverage-gap detection
- Limit adequacy review
- Exclusion and restriction analysis
- Materiality ranking
- Advisory prioritization
- Evidence classification
- Decision readiness
- Client-conversation preparation
- Human review
- Downstream workflow handoff

The objective is not simply to identify more potential coverage gaps.

The objective is to identify the **right issues**, rank them by real-world impact, and convert them into practical advisory opportunities.

---

# Purpose

Evaluate how well a client's current commercial insurance program aligns with the client's actual operations, exposures, contractual obligations, growth, and loss profile.

This Skill is designed to help the insurance professional:

- Understand how the business actually creates risk
- Compare operational exposures against the current insurance program
- Identify material coverage gaps
- Identify structural weaknesses
- Identify potentially inadequate limits
- Identify meaningful exclusions or restrictions
- Distinguish real concerns from theoretical deficiencies
- Prioritize the issues most likely to matter financially or operationally
- Translate technical insurance findings into business-owner implications
- Prepare producers and advisors for high-value client discussions
- Develop practical program-improvement options
- Identify where risk reduction may be more appropriate than simply buying more insurance
- Strengthen advisory positioning through evidence-based recommendations

The objective is **not** to prove that the client has an inadequate program.

The objective is to answer:

> Where does the client's real-world risk profile appear misaligned with the protection currently in place, and what should we discuss with the client first?

---

# Core Outcome

A successful execution should allow a producer or advisor to quickly understand:

1. How the existing insurance program is structured
2. How the client's actual operations create risk
3. Which exposures appear well addressed
4. Which exposures may not be addressed adequately
5. Where coverage may be absent or uncertain
6. Where limits may be insufficient
7. Which exclusions or restrictions could materially affect a claim
8. Which issues are most important
9. What assumptions or information gaps remain
10. What practical actions should be discussed with the client
11. What requires policy-form review before a definitive conclusion

The final output should support a meaningful advisory conversation rather than become a list of theoretical insurance defects.

---

# Role in the Insurance AI Advantage System

This Signature Skill operates primarily within the **Coverage Intelligence and Advisory** stage of the Insurance AI Advantage System.

## Upstream Inputs May Include

- Prospect Intelligence
- Exposure Intelligence
- Business Classification Analysis
- Policy Extraction
- Policy Explanation
- Loss Run Analysis
- Client Discovery Notes
- Contract Requirements
- Claims History
- Renewal Intelligence
- Current Program Data

## Primary Function

Compare the client's real-world risk profile to the protection currently in place and identify material advisory priorities.

## Downstream Workflows May Include

- Client Meeting Strategy
- Coverage Recommendation
- Renewal Strategy
- Quote Strategy
- Carrier Placement Strategy
- Proposal Development
- Executive Proposal Summary
- Client Communication
- Risk-Control Planning
- Program Restructuring
- Policy Comparison

The output should therefore produce reusable structured intelligence rather than a one-time narrative.

---

# Best Used For

Use this Skill for:

- Existing-client coverage reviews
- Pre-renewal strategy
- New-client discovery
- BOR transition review
- Coverage audits
- Program restructuring
- Cross-sell analysis
- Claims-driven coverage review
- Acquisition / growth review
- Contract-driven coverage review
- Multi-line commercial accounts
- Complex commercial accounts
- Contractor programs
- Manufacturing
- Transportation
- Technology
- Professional services
- Healthcare
- Mining
- Hospitality
- Real estate
- Distribution
- Retail
- Other commercial industries

It is especially useful where the current insurance program may no longer reflect:

- Growth
- New operations
- New locations
- New contracts
- New vehicles
- New products
- New employees
- New technology
- New liability exposure
- Changed property values
- Changed business-interruption exposure

---

# Do Not Use This Skill As

This Skill is not a substitute for:

- Full policy-form review
- Legal advice
- Formal coverage opinion
- Carrier coverage determination
- Claims determination
- Contract interpretation by legal counsel
- Actuarial limit analysis
- Binding authority
- Regulatory advice
- Formal valuation analysis

This is a **coverage intelligence and advisory decision-support Skill**.

---

# Intended Users

Primary users:

- Commercial Insurance Coverage Analysts
- Commercial Insurance Producers
- Risk Advisors

Secondary users:

- Commercial Account Executives
- Commercial Account Managers
- Agency Principals
- Coverage Specialists
- Renewal Strategists
- Placement Specialists

---

# Required Inputs

At minimum:

```text
Client Industry:
[INSERT]

Operations Summary:
[INSERT]

Current Insurance Program:
[INSERT]

Additional Context:
[INSERT IF AVAILABLE]
```

The current program may include:

- Policy summaries
- Declarations
- Coverage schedules
- Limits
- Deductibles
- Endorsements
- Proposal data
- AMS data
- Current policy details

If the program information is incomplete, the Skill must state that limitation.

---

# Recommended Inputs

Where available, provide:

```text
Client Name:
[INSERT]

Industry:
[INSERT]

Operations:
[INSERT]

Revenue:
[INSERT]

Payroll:
[INSERT]

Employee Count:
[INSERT]

Locations:
[INSERT]

Property Values:
[INSERT]

Vehicle Count:
[INSERT]

Products / Services:
[INSERT]

Customer Types:
[INSERT]

Subcontractor Usage:
[INSERT]

Contractual Requirements:
[INSERT]

Current Policies:
[INSERT]

Limits:
[INSERT]

Deductibles / Retentions:
[INSERT]

Endorsements:
[INSERT]

Exclusions:
[INSERT]

Sublimits:
[INSERT]

Loss History:
[INSERT]

Open Claims:
[INSERT]

Known Risk Concerns:
[INSERT]

Growth / Changes:
[INSERT]

Client Priorities:
[INSERT]

Renewal Date:
[INSERT]

Current Premium:
[INSERT]
```

---

# Optional Intelligence Sources

Where authorized and relevant:

- Current policies
- Endorsements
- Declarations
- Applications
- Exposure schedules
- Contracts
- Loss runs
- Claims summaries
- Property valuations
- Fleet schedules
- Payroll records
- Revenue data
- Business-interruption worksheets
- Risk-control reports
- Client website
- Public business information
- Carrier forms
- Current regulatory guidance
- Agency CRM
- Agency Management System

General industry knowledge may support exposure hypotheses but must not silently substitute for client-specific facts.

---

# Preferred Source Documents

Prioritize:

1. Current complete policy forms
2. Current endorsements
3. Current declarations
4. Current schedules
5. Current client-confirmed exposure data
6. Current applications
7. Current contracts
8. Current loss history
9. Current valuations
10. Agency-verified data
11. Historical policies
12. General industry inference

---

# Document Completeness Standard

Classify the supplied insurance documentation as:

### Complete Enough for Coverage Analysis

The available documentation reasonably supports specific coverage conclusions.

### Partially Complete

Useful analysis is possible, but some findings require policy-form review.

### Fragmentary

Only high-level exposure observations can be made reliably.

Do not treat:

- A declaration page
- A proposal
- An AMS summary
- A coverage spreadsheet

as equivalent to a complete policy.

When documentation is incomplete:

- Identify exactly what was reviewed
- Identify what appears missing
- Limit conclusions accordingly
- Use `Requires Policy-Form Review` where necessary

---

# Document Interaction / Override Standard

Coverage analysis must consider whether:

- Endorsements modify base forms
- Schedules modify limits
- Manuscript endorsements override standard wording
- Exclusions are amended
- Additional-insured endorsements alter status
- Deductible endorsements modify declarations
- State-specific forms apply
- Umbrella forms differ from underlying forms

Never interpret a base form without considering known modifying endorsements.

When documents interact:

1. Identify the base provision
2. Identify the modifying endorsement
3. Identify effective date
4. Explain the practical effect
5. Flag unresolved conflicts

---

# Source Hierarchy

When information conflicts:

1. Current controlling policy wording
2. Current endorsements
3. Current declarations / schedules
4. Current client-confirmed operations
5. Current applications
6. Current contract requirements
7. Agency-verified information
8. Historical information
9. General industry inference

Do not silently choose the version that supports the stronger advisory recommendation.

---

# Jurisdiction / Governing Authority Standard

Where coverage depends on:

- State
- Jurisdiction
- Carrier form
- Policy form
- Contract
- Rating authority
- Regulation

identify the governing authority before reaching a definitive conclusion.

A general coverage principle does not override the client's actual policy.

---

# Authority vs. Inference Standard

Distinguish clearly between:

### Documented Policy Fact

Supported by the actual policy or endorsement.

### Documented Client Exposure

Supported by client-confirmed operational information.

### Analytical Concern

A reasonable mismatch identified by the Skill.

### Industry Exposure Hypothesis

A likely exposure based on industry norms that requires confirmation.

### Advisory Recommendation

A proposed action.

### Decision Authority

The client, authorized insurance professional, carrier, claims professional, or legal counsel as applicable.

The Skill may identify concern.

It does not make a formal carrier coverage determination.

---

# Evidence Classification

Every material finding should be classified internally as one of:

## Documented Finding

Supported directly by policy or program documentation.

## Confirmed Exposure

Supported by client information.

## Likely Concern

Reasonably supported by the program and exposure data.

## Exposure-Dependent Concern

Potentially material but depends on a fact that remains unconfirmed.

## Requires Policy-Form Review

Cannot be resolved reliably from the supplied documents.

## Requires Client Confirmation

Depends on operational facts not yet confirmed.

## Requires Contract Review

Depends on contractual requirements.

Never present an exposure hypothesis as a confirmed coverage gap.

---

# Confidence Classification

Where useful:

### High Confidence

Strongly supported by complete policy and exposure information.

### Moderate Confidence

Reasonably supported but one or more meaningful variables remain unresolved.

### Low Confidence

Based on incomplete documentation, inference, or ambiguous wording.

---

# Scope-of-Explanation Standard

Determine whether the analysis concerns:

### General Coverage Concept

Example:

> Cyber liability commonly addresses certain privacy and network-security events.

or:

### Specific Policy Coverage

Example:

> The supplied policy includes a $1 million cyber limit subject to the listed retention and exclusions.

Do not substitute a general explanation for policy-specific analysis.

---

# Neutral Narrative / Attribution Standard

When the analysis involves:

- Claims
- Coverage disputes
- Prior denials
- Contractual allegations
- Loss causation

preserve attribution.

Example:

> The insured reports that the prior water loss resulted from subcontractor work.

not:

> The subcontractor caused the loss.

unless formally established.

---

# Core Principle

## Identify Real Exposure, Not Theoretical Defects

A strong coverage review should focus on:

- Financially meaningful exposure
- Operationally realistic loss scenarios
- Contractual requirements
- Evidence from losses
- Material structural weaknesses

Avoid creating a long list of hypothetical concerns that have little relevance to the client's actual business.

---

# Client Value Standard

Every material issue should answer:

> Why should the business owner care?

Translate insurance findings into consequences such as:

- Uninsured financial loss
- Increased retention
- Contract breach
- Business interruption
- Out-of-pocket defense cost
- Reduced recovery
- Balance-sheet exposure
- Operational disruption

Do not stop at technical policy terminology.

---

# Execution Readiness Standard

Before producing a client-ready advisory analysis, classify:

### Advisory Ready

Enough information exists to support meaningful client discussion.

### Conditionally Advisory Ready

Useful discussion is possible, but material findings require further confirmation.

### Not Advisory Ready

The source information is too incomplete to support responsible client-facing conclusions.

A polished report does not equal reliable advice.

---

# Workflow State Standard

Relevant states may include:

1. Intake Received
2. Exposure Validation
3. Policy Review
4. Coverage Mapping
5. Gap Analysis
6. Limit Review
7. Priority Ranking
8. Internal Review
9. Advisory Ready
10. Client Discussion
11. Recommendation Accepted
12. Recommendation Declined
13. Quote / Placement Requested
14. Program Updated

Use only states relevant to the workflow.

---

# Workflow

## Step 1 — Understand the Business

Determine:

- What the company actually does
- What generates revenue
- Where work occurs
- Who performs the work
- Who customers are
- What assets are critical
- What liabilities could arise
- What could interrupt operations

Do not begin with policy terms.

Begin with the business.

---

## Step 2 — Identify Material Operations

Capture:

- Primary operations
- Secondary operations
- Products
- Services
- Installation
- Manufacturing
- Transportation
- Field work
- Professional services
- Subcontracting
- Cyber dependence
- Property dependence

Include only operations that materially affect risk.

---

## Step 3 — Build the Exposure Architecture

Map real-world risk across relevant categories.

### Property

- Buildings
- Business personal property
- Equipment
- Stock
- Valuation
- CAT
- Business interruption

### General Liability

- Premises
- Operations
- Products
- Completed operations
- Contractual liability
- Third-party bodily injury
- Third-party property damage

### Auto

- Fleet
- Drivers
- Radius
- Hired auto
- Non-owned auto
- Heavy vehicles

### Workers' Compensation

- Employee duties
- Payroll
- Hazardous work
- Field exposure
- Travel
- Height
- Machinery

### Professional / Management

- E&O
- D&O
- EPLI
- Fiduciary

### Cyber

- Privacy
- Network security
- Business interruption
- Funds transfer
- Ransomware

### Specialty

- Pollution
- Crime
- Inland marine
- Equipment breakdown
- Product recall
- Kidnap / ransom
- Other material exposures

Do not force irrelevant categories.

---

## Step 4 — Map Existing Coverage to Exposure

For each material exposure, identify:

- Policy / coverage
- Limit
- Deductible / retention
- Sublimit
- Exclusion
- Condition
- Endorsement
- Unknown

Recommended structure:

| Exposure | Current Coverage | Limit | Key Restriction | Initial Alignment |
|---|---|---:|---|---|
| [Exposure] | [Coverage] | [$] | [Restriction] | Aligned / Concern / Unknown |

---

## Step 5 — Identify Missing Coverage

Ask:

> Is there a material operational exposure with no apparent coverage?

Examples:

- Cyber
- EPLI
- Pollution
- Professional liability
- Hired / non-owned auto
- Equipment breakdown
- Flood
- Earthquake
- Inland marine
- Crime

Only identify a gap when the exposure actually exists or is reasonably likely.

---

## Step 6 — Identify Structural Coverage Gaps

Coverage may exist but still be misaligned.

Examples:

- Wrong named insured
- Missing entity
- Missing location
- Inadequate business income period
- Inappropriate deductible
- Missing blanket feature
- Missing scheduled property
- Inadequate umbrella attachment
- Wrong valuation
- Claims-made continuity issue
- Insufficient additional-insured structure

These can be more important than simply missing a coverage line.

---

# Structural Gap Standard

Classify findings as:

### Missing Coverage

No apparent coverage for a material exposure.

### Structural Weakness

Coverage exists but program design may not align with exposure.

### Limit Concern

Coverage exists but available limit may be insufficient.

### Restriction Concern

Exclusion, condition, or sublimit may materially reduce protection.

### Documentation Concern

Coverage cannot be determined reliably from the supplied material.

---

## Step 7 — Evaluate Policy Limits

Review whether limits appear reasonable relative to:

- Property values
- Revenue
- Payroll
- Fleet
- Contract requirements
- Business-interruption exposure
- Maximum foreseeable severity
- Customer concentration
- Claim history

Do not claim a limit is definitely inadequate without support.

---

# Limit Adequacy Standard

Classify:

### Appears Reasonable

Available information suggests the limit is reasonably aligned.

### Potentially Low

Exposure suggests a meaningful possibility of inadequate limit.

### Material Concern

Known exposure or contractual requirement materially exceeds the available limit.

### Unable to Determine

Insufficient information exists.

Limit analysis should explain the basis.

---

## Step 8 — Evaluate Deductibles and Retentions

Consider:

- Client liquidity
- Claim frequency
- Severity
- Risk tolerance
- Contract requirements
- Premium trade-off
- Operational burden

Do not treat lower deductible as automatically better.

---

## Step 9 — Identify Meaningful Exclusions

Review only exclusions relevant to actual operations.

Potential examples:

- Residential work
- Roofing
- Height
- Design / professional services
- Pollution
- Cyber
- Assault and battery
- Habitational
- Product
- Abuse / molestation
- Subsidence
- Wildfire
- Flood
- Earthquake

Avoid generic exclusion dumping.

---

# Exclusion Relevance Standard

For each exclusion:

1. Does the excluded activity exist?
2. How material is that activity?
3. What real claim scenario could trigger the exclusion?
4. Is alternative coverage available?
5. Does the exclusion create a contractual conflict?

Only material exclusions should be elevated.

---

## Step 10 — Identify Sublimit Concerns

Review:

- Water damage
- Cyber
- Equipment
- Ordinance or law
- Debris removal
- Business income
- Valuable papers
- Crime
- Utility interruption
- Contingent BI
- Spoilage
- Pollution

Do not assume the headline policy limit applies equally to all exposures.

---

## Step 11 — Review Contractual Requirements

Where contracts are available, compare requirements involving:

- Limits
- Additional insured
- Primary / noncontributory
- Waiver of subrogation
- Completed operations
- Auto
- Umbrella
- Professional liability
- Cyber
- Pollution

Do not provide legal contract interpretation.

Flag insurance requirements that appear inconsistent with the current program.

---

## Step 12 — Review Loss History

Ask:

- What types of claims have occurred?
- Do those claims reveal structural weaknesses?
- Is frequency concentrated?
- Did losses expose deductible burden?
- Did coverage respond as expected?
- Are there repeat causes?

Claims may reveal advisory priorities more clearly than theoretical exposure analysis.

---

# Loss-to-Coverage Learning Standard

When a prior loss is relevant, consider:

**Loss Event → Coverage Response → Client Impact → Program Lesson**

Do not assume a prior covered claim proves the program is adequate.

Do not assume a prior denied claim proves the same future result.

---

## Step 13 — Identify Change / Drift

Determine whether the business changed since the program was designed.

Potential changes:

- Revenue growth
- Payroll growth
- New states
- New locations
- New product
- New service
- New contracts
- New vehicles
- New property values
- New technology
- New employees
- Acquisition
- Ownership change

Coverage drift often occurs gradually.

---

## Step 14 — Identify Frequency Risk

Potential frequency exposures:

- Auto
- Employee injury
- Slip and fall
- Minor property damage
- Repetitive product claims
- Cyber events

Determine whether the current program structure supports frequent-loss management.

---

## Step 15 — Identify Severity Risk

Potential severity exposures:

- Catastrophic liability
- Major property loss
- Business interruption
- Severe auto accident
- Product injury
- Cyber shutdown
- Environmental event

Severity should heavily influence priority ranking.

---

## Step 16 — Develop Real-World Scenarios

For material issues, create simple client-relevant examples.

Example:

> If a service technician causes a serious accident while driving a personally owned vehicle for company business, the issue is whether the current program adequately addresses non-owned auto liability.

Do not imply guaranteed claim outcomes.

---

# Example Integrity Standard

Scenarios must:

- Remain hypothetical
- Stay within known exposure
- Avoid guaranteeing coverage
- Avoid inventing policy response
- Identify what policy language would need confirmation

---

## Step 17 — Rank Coverage Concerns

Use:

### Priority 1 — Critical

Potentially severe uninsured or materially underinsured exposure requiring prompt attention.

### Priority 2 — High

Meaningful exposure that should be addressed during current renewal or advisory cycle.

### Priority 3 — Moderate

Relevant issue worth review but not immediately significant.

### Priority 4 — Informational

Useful awareness without clear need for action.

Do not make every issue Priority 1.

---

# Materiality Scoring Factors

Consider:

- Severity
- Frequency
- Financial impact
- Coverage certainty
- Contractual impact
- Operational impact
- Claims evidence
- Client risk tolerance
- Urgency
- Evidence strength

---

## Step 18 — Identify Advisory Opportunities

For each material concern, determine whether the best response is:

### Coverage Improvement

Add or broaden coverage.

### Limit Adjustment

Increase or restructure limits.

### Deductible / Retention Strategy

Adjust risk retention.

### Policy Form Improvement

Modify restrictive wording.

### Risk Control

Reduce the underlying exposure.

### Contractual Improvement

Improve transfer or insurance requirements.

### Data / Valuation Improvement

Improve the accuracy of insured values or exposure data.

### Client Acceptance

Client understands and intentionally retains the risk.

Advisory quality is not measured by how many policies are sold.

---

# Advisory Opportunity Standard

Every recommendation should answer:

1. What exposure exists?
2. What is the current program issue?
3. What could happen?
4. What improvement is available?
5. What trade-off accompanies the improvement?
6. What requires confirmation?

---

# Trade-Off Transparency Standard

For material recommendations, explain:

### Gain

What improves?

### Give-Up

What additional premium, retention, restriction, or complexity may result?

### Remaining Risk

What remains even after improvement?

### Assumption

What fact supports the recommendation?

Example:

> Increasing umbrella limits may improve protection against catastrophic liability exposure, but will increase premium and still will not address exposures excluded by the underlying policies.

---

## Step 19 — Determine Advisory Readiness

Classify:

- Advisory Ready
- Conditionally Advisory Ready
- Not Advisory Ready

Identify what must be confirmed before client discussion.

---

## Step 20 — Prepare the Client Conversation

For each Priority 1 or Priority 2 concern, prepare:

### Business Risk

What could happen?

### Current Program

How does the program appear to address it?

### Concern

Where might protection fall short?

### Recommendation

What should be considered?

### Question

What should the advisor ask the client?

This converts analysis into advisory execution.

---

# Client Conversation Standard

Lead with:

> Business risk

not:

> Insurance product.

Preferred:

> A major shutdown at this location could materially affect revenue. We should confirm whether the current business-income structure reflects the actual recovery period.

Avoid:

> You need more business-income insurance.

---

# Data Integrity Standard

Review for:

- Conflicting limits
- Conflicting deductibles
- Different policy periods
- Missing endorsements
- Missing locations
- Stale property values
- Conflicting revenue
- Conflicting payroll
- Missing entities

Do not silently resolve material inconsistencies.

---

# Calculation Integrity Standard

Where calculations are used:

- Identify source data
- Identify denominator
- Identify period
- Avoid unsupported precision

Potential calculations:

- Property value concentration
- Revenue concentration
- Payroll concentration
- Limit-to-exposure relationship
- Deductible relative to cash flow
- Vehicle exposure

Do not present a rough heuristic as an actuarial conclusion.

---

# Comparison Basis / Like-for-Like Standard

When comparing:

- Current vs. prior program
- Current vs. proposed program
- Policy alternatives

ensure comparability of:

- Limits
- Deductibles
- Retentions
- Exposure
- Policy period
- Coverage form
- Geography
- Entities
- Sublimits

---

# Change / Drift Detection Standard

Reassess coverage alignment when:

- Revenue changes materially
- Payroll changes materially
- Property values change
- New operation begins
- New state is entered
- New contract is signed
- Fleet changes
- New technology is introduced
- Significant claim occurs
- Client acquisition occurs

Coverage alignment is not static.

---

# Obligation Extraction Standard

Where client contracts or carrier requirements create obligations, capture:

| Obligation | Owner | Trigger | Deadline | Evidence | Source |
|---|---|---|---|---|---|
| [Requirement] | [Owner] | [Trigger] | [Timing] | [Evidence] | [Document] |

Do not convert general recommendations into contractual requirements.

---

# Ownership Standard

Assign each advisory action.

Example:

| Action | Owner |
|---|---|
| Confirm property values | Client / Account Manager |
| Review umbrella limit | Producer |
| Obtain cyber quote | Marketing |
| Confirm endorsement wording | Coverage Analyst |
| Review contract | Client / Legal Counsel |

---

# Handoff Integrity Standard

When coverage analysis moves into the advisory workflow, handoff should include:

- Client
- Exposure
- Coverage finding
- Priority
- Evidence
- Assumption
- Recommended action
- Owner
- Required confirmation

Recommended structure:

```text
Client:
[NAME]

Priority Concern:
[ISSUE]

Exposure:
[EXPOSURE]

Current Coverage:
[CURRENT STATE]

Evidence:
[SOURCE]

Recommended Action:
[ACTION]

Owner:
[ROLE]

Client Discussion Needed:
[YES / NO]
```

---

# System-of-Record Standard

Where coverage intelligence is stored across systems:

| Data | System of Record |
|---|---|
| Current policy | AMS |
| Client exposure data | AMS / CRM |
| Coverage analysis | Advisory / CRM record |
| Recommendations | CRM / Renewal workflow |
| Final client decision | CRM / AMS note |
| Updated policy | AMS |

Do not allow coverage recommendations to remain only in personal notes or email.

---

# Transaction Lineage / Audit Trail Standard

Preserve:

```text
Client Exposure
    ↓
Current Policy / Coverage
    ↓
Coverage Finding
    ↓
Advisory Recommendation
    ↓
Client Decision
    ↓
Quote / Endorsement / Program Change
    ↓
Final Policy
```

The final program change should remain traceable to:

- Exposure
- Original concern
- Recommendation
- Client decision

Do not erase the history of advisory decisions.

---

# Dynamic Reassessment / Monitoring Trigger Standard

Reassess coverage alignment when:

- New loss occurs
- New entity is formed
- Acquisition occurs
- New contract is signed
- Revenue materially changes
- Payroll materially changes
- Property values change
- Fleet expands
- New location opens
- Client enters new state
- New operation begins
- Policy wording changes
- Carrier adds exclusion

The advisory analysis is a snapshot.

It should not be treated as permanently current.

---

# Governance / Conflict Prevention Standard

Before recommending changes, check for:

- Existing pending endorsement
- Current renewal negotiation
- Existing quote
- Client instruction
- Contract requirement
- Coverage already purchased elsewhere
- Existing umbrella attachment
- Duplicate coverage
- Carrier limitation

Do not create conflicting coverage transactions.

---

# Stop Rules

Stop and escalate when:

- Complete policy wording is required
- Material endorsement is missing
- Policy versions conflict
- Coverage issue involves active litigation
- Active claim coverage is disputed
- Contract interpretation is required
- Regulatory issue exists
- Client exposure cannot be confirmed
- Recommendation would require unsupported coverage representation

Do not solve uncertainty by sounding more confident.

---

# Completion Criteria Standard

Coverage analysis is complete when:

1. Client operations are understood
2. Material exposures are identified
3. Current program structure is mapped
4. Missing coverage is considered
5. Structural weaknesses are considered
6. Limits are reviewed
7. Relevant exclusions are reviewed
8. Material sublimits are considered
9. Contract requirements are considered where available
10. Loss history is incorporated
11. Risk drift is considered
12. Findings are prioritized
13. Advisory opportunities are developed
14. Assumptions are disclosed
15. Policy-form-review items are identified
16. Human review is completed where required
17. Client discussion priorities are prepared

The workflow is not complete simply because gaps were listed.

---

# Human Review Escalation Standard

Require elevated human review when:

- Potential uninsured major loss exists
- Active claim may be affected
- Coverage denial is involved
- Legal dispute exists
- Material E&O concern exists
- Policy wording is ambiguous
- Contractual requirements materially conflict with the program
- Cancellation / non-renewal is involved
- High-limit recommendation is being made
- Major client financial harm is possible

AI may identify and organize the concern.

Authorized insurance professionals remain responsible for advisory recommendations.

---

# Internal vs. External Information Boundary Standard

The internal analysis may contain:

- Coverage hypotheses
- Policy-form-review items
- E&O concerns
- Sales opportunities
- Cross-sell possibilities
- Carrier strategy
- Internal scoring

Client-facing output should contain only information appropriate for advisory discussion.

Do not expose:

- Internal sales strategy
- Revenue opportunity
- Carrier criticism
- Unsupported speculation
- E&O commentary

without human judgment.

---

# Decision Rules

## Exposure Before Coverage

Understand the business first.

---

## Materiality Over Volume

Prioritize meaningful concerns.

---

## Specific Policy Over General Knowledge

The actual policy controls.

---

## Missing Coverage Requires Real Exposure

Do not recommend coverage simply because it exists in the marketplace.

---

## Unchanged Coverage Does Not Mean Adequate Coverage

Exposure may have changed.

---

## Limits Require Context

Do not call a limit inadequate without explaining why.

---

## Exclusions Require Relevance

Ignore theoretical exclusions unrelated to operations.

---

## Advisory Opportunity Does Not Always Mean Buy More Insurance

Risk control or risk retention may sometimes be appropriate.

---

## Client Decision Matters

The goal is informed decision-making, not forced coverage expansion.

---

# Materiality / Prioritization Framework

Use:

| Factor | Question |
|---|---|
| Severity | Could the loss be financially significant? |
| Frequency | How often could the exposure occur? |
| Coverage Certainty | Is protection clearly available? |
| Financial Impact | What could the client retain? |
| Operational Impact | Could operations be disrupted? |
| Contractual Impact | Could a contract requirement be violated? |
| Claims Evidence | Has the exposure already produced losses? |
| Urgency | Does this need action now? |
| Evidence Strength | How well supported is the finding? |
| Client Priority | Does the issue matter to the client's objectives? |

---

# Output Requirements

Use the following structure unless another format is requested.

# Commercial Insurance Coverage & Risk Advisory Analysis

## 1. Advisory Readiness

**Status:** Advisory Ready / Conditionally Advisory Ready / Not Advisory Ready

**Client Industry:** [Industry]  
**Operations:** [Short summary]  
**Documentation Reviewed:** [Sources]

### Material Information Gaps

- [Item]
- [Item]

---

# 2. Coverage Overview

Provide a concise summary of the current program.

Example:

| Coverage | Carrier | Limit | Deductible / Retention | Key Notes |
|---|---|---:|---:|---|
| General Liability | [Carrier] | [$] | [$] | [Notes] |
| Auto | [Carrier] | [$] | [$] | [Notes] |

Do not invent missing information.

---

# 3. Exposure Analysis

## Primary Operational Exposures

### [Exposure]

**How the exposure arises:**  
[Explanation]

**Potential impact:**  
[Business consequence]

**Current protection:**  
[Coverage]

**Alignment:**  
Aligned / Concern / Unknown

Repeat for material exposures.

---

# 4. Identified Coverage Gaps

| Priority | Exposure | Current Program | Gap / Concern | Potential Impact | Evidence |
|---|---|---|---|---|---|
| 1 | [Exposure] | [Coverage] | [Concern] | [Impact] | Documented / Likely / Requires Review |

Include only meaningful gaps.

---

# 5. Policy Limit Concerns

| Coverage | Current Limit | Exposure Basis | Assessment | Recommendation |
|---|---:|---|---|---|
| [Coverage] | [$] | [Basis] | Reasonable / Potentially Low / Material Concern / Unknown | [Action] |

---

# 6. Exclusions & Restrictions

| Exclusion / Restriction | Relevant Exposure | Practical Impact | Priority | Required Review |
|---|---|---|---|---|
| [Item] | [Exposure] | [Impact] | High / Moderate / Low | [Action] |

Do not list immaterial exclusions.

---

# 7. Priority Risk Areas

## Priority 1 — [Concern]

**Business Exposure:**  
[Risk]

**Current Program Issue:**  
[Concern]

**Potential Impact:**  
[Impact]

**Evidence:**  
[Source]

**Recommended Discussion:**  
[Action]

---

## Priority 2 — [Concern]

Repeat as needed.

Avoid excessive Priority 1 findings.

---

# 8. Advisory Opportunities

| Opportunity | Business Rationale | Recommended Action | Trade-Off | Owner |
|---|---|---|---|---|
| [Opportunity] | [Reason] | [Action] | [Trade-Off] | [Owner] |

---

# 9. Client Conversation Priorities

For the highest-priority issues:

### Discussion #1 — [Topic]

**Business Risk:**  
[What could happen]

**Current Program:**  
[Current state]

**Concern:**  
[Potential misalignment]

**Recommended Consideration:**  
[Action]

**Question for Client:**  
[Discovery / decision question]

---

# 10. Items Requiring Policy-Form Review

| Issue | Why Review Is Needed | Document Needed | Owner |
|---|---|---|---|
| [Issue] | [Reason] | [Document] | [Owner] |

---

# 11. Assumptions & Items Requiring Confirmation

| Assumption / Unknown | Basis | Confidence | Confirmation Needed |
|---|---|---|---|
| [Item] | [Reason] | High / Moderate / Low | [Action] |

---

# 12. Recommended Next Steps

| Priority | Action | Owner | Timing | Completion Criteria |
|---|---|---|---|---|
| 1 | [Action] | [Owner] | [Timing] | [Criteria] |

---

# Executive Advisory Snapshot

When requested, also provide:

```text
Client:
[NAME]

Industry:
[INDUSTRY]

Top Exposure:
[EXPOSURE]

Top Coverage Concern:
[CONCERN]

Highest-Priority Limit Issue:
[ISSUE]

Most Material Exclusion:
[EXCLUSION]

Primary Advisory Opportunity:
[OPPORTUNITY]

Policy Review Required:
[YES / NO]

Advisory Readiness:
[STATUS]
```

---

# Machine-Readable Coverage Intelligence

When requested, also output fields such as:

```text
client_name
industry
operations_summary
coverage_line
carrier
policy_number
policy_limit
deductible
retention
sublimit
exposure_type
exposure_description
coverage_alignment
gap_type
coverage_gap
limit_concern
restriction
exclusion
materiality
priority
evidence_type
confidence
policy_review_required
recommended_action
tradeoff
owner
client_discussion_required
```

Do not populate unsupported fields.

---

# Quality Checks

Before finalizing, verify:

- [ ] Client operations are understood
- [ ] Analysis begins with exposure rather than insurance products
- [ ] Current program is accurately represented
- [ ] Policy-document completeness is considered
- [ ] Endorsements and overrides are considered
- [ ] Missing coverage findings are tied to actual exposure
- [ ] Structural coverage weaknesses are considered
- [ ] Limits are analyzed with context
- [ ] Deductibles / retentions are considered where relevant
- [ ] Exclusions are materially relevant
- [ ] Sublimits are considered where relevant
- [ ] Contractual requirements are considered where available
- [ ] Loss history informs the analysis
- [ ] Business changes / drift are considered
- [ ] Findings distinguish fact from inference
- [ ] Assumptions are visible
- [ ] Findings are prioritized
- [ ] Priority 1 is used sparingly
- [ ] Recommendations include trade-offs
- [ ] Policy-form-review items are clearly flagged
- [ ] Client implications are explained in plain language
- [ ] Client conversation priorities are prepared
- [ ] Internal strategy is separated from external advice
- [ ] Human review occurs where required
- [ ] No unsupported coverage guarantees are made

---

# Failure Conditions

The Skill should not be considered complete if:

- The output is only a policy summary
- The output begins with products instead of exposures
- Generic industry exposures are presented as client facts
- The analysis creates theoretical gaps with little practical relevance
- Limits are called inadequate without a stated basis
- Every exclusion is treated as material
- Full-policy conclusions are made from declarations only
- Endorsements are ignored
- Claims evidence is ignored
- Client growth or operational changes are ignored
- Recommendations lack prioritization
- Recommendations lack trade-off explanation
- Assumptions are hidden
- Policy-form-review items are stated as definitive gaps
- The client-facing discussion would overwhelm rather than clarify
- The output reads like a sales opportunity list instead of risk advice

If any failure condition exists, revise or escalate.

---

# Guardrails

## Do Not Fabricate Coverage

Never invent:

- Limits
- Deductibles
- Retentions
- Sublimits
- Endorsements
- Exclusions
- Policy provisions
- Carrier terms

---

## Do Not Manufacture Exposure

General industry risk may create a hypothesis.

It does not establish client-specific exposure.

---

## Do Not Guarantee Claim Outcomes

Never state:

- This loss would definitely be covered
- This claim would be denied
- The carrier must pay

without authoritative determination.

---

## Do Not Treat a Summary as the Policy

Where documentation is incomplete:

> Requires Policy-Form Review.

---

## Do Not Overstate Limit Adequacy

Limit analysis is advisory unless supported by formal valuation or contractual requirement.

---

## Do Not Create Fear-Based Recommendations

Use:

- Evidence
- Severity
- Business impact
- Client priorities

not fear.

---

## Do Not Hide Trade-Offs

Every meaningful recommendation may involve:

- Premium
- Deductible
- Restriction
- Administrative burden
- Coverage complexity

Disclose material trade-offs.

---

## No Legal Advice

Contractual or legal issues should be referred to appropriate counsel where necessary.

---

## Protect Confidential Information

Do not unnecessarily expose:

- Proprietary client data
- Claims-sensitive information
- Employee information
- Internal agency strategy
- Credentials
- Financial account information

---

## Preserve Human Accountability

This Skill supports the insurance professional.

The authorized producer, coverage analyst, account executive, risk advisor, carrier, claims professional, or legal counsel remains responsible for:

- Final coverage recommendations
- Policy interpretation
- Client communication
- Contract advice
- Coverage placement
- Binding
- Professional judgment

### Your people make the decisions. Your AI Teammates do the work.

---

# Professional Tone Standard

Write like a senior commercial insurance coverage analyst preparing an advisor for a meaningful business-owner conversation.

The tone should be:

- Analytical
- Practical
- Clear
- Specific
- Client-centered
- Commercially aware
- Non-alarmist
- Evidence-based
- Actionable

Avoid:

- Generic coverage lists
- Product dumping
- Fear-based language
- Excessive technical terminology
- Unsupported certainty
- Long theoretical issue lists
- Sales clichés
- Generic AI language

The analysis should create confidence because it demonstrates understanding of the business.

---

# Example

## Example Request

```text
Client Industry:
Commercial Landscaping Contractor

Operations Summary:
Approximately $12M revenue. Performs landscape construction, maintenance, irrigation installation, tree trimming, and limited snow-removal services. Fleet of 38 vehicles. Approximately 120 employees. Uses subcontractors for about 10% of annual work.

Current Insurance Program:
GL: $1M occurrence / $2M aggregate
Auto: $1M CSL
Workers' Compensation: statutory
Umbrella: $2M
Property: $1.8M equipment and business personal property
Cyber: None
Pollution: None shown

Additional Context:
Client recently began municipal contracts requiring $5M total liability limits. Revenue increased from $7M to $12M over three years. Equipment values have increased materially. One $480K commercial auto claim occurred two years ago.
```

---

## Example Output

# Commercial Insurance Coverage & Risk Advisory Analysis

## 1. Advisory Readiness

**Status:** Conditionally Advisory Ready

**Client Industry:** Commercial Landscaping Contractor

**Primary Operations:** Landscape construction, maintenance, irrigation, tree trimming and limited snow removal

**Documentation Reviewed:** High-level program summary only

### Material Information Gaps

- Full policy forms and endorsements
- Current equipment schedule
- Municipal contract insurance requirements
- Umbrella attachment details
- Pollution exclusions / endorsements
- Hired and non-owned auto status

Specific policy conclusions therefore require further policy-form review.

---

# 2. Coverage Overview

| Coverage | Current Limit | Key Observation |
|---|---:|---|
| General Liability | $1M / $2M | Standard primary structure based on supplied summary |
| Commercial Auto | $1M CSL | Material fleet exposure and prior severe auto claim |
| Workers' Compensation | Statutory | 120 employees with field operations |
| Umbrella | $2M | May not satisfy newly reported $5M contractual requirement |
| Property / Equipment | $1.8M | Current values should be validated due to growth |
| Cyber | None shown | Exposure requires client confirmation |
| Pollution | None shown | Operational exposure should be evaluated |

---

# 3. Exposure Analysis

## Commercial Auto

The company operates approximately 38 vehicles and has experienced a reported $480,000 auto claim.

This creates meaningful both frequency and severity potential.

The current $1 million auto liability limit should therefore be evaluated together with the umbrella structure rather than in isolation.

---

## Tree-Trimming Operations

Tree trimming creates potentially significant:

- Third-party property damage
- Bodily injury
- Workers' compensation severity
- Height-related liability

Full policy review is needed to determine whether any height, arborist, or related operational restrictions apply.

---

## Pollution / Environmental Exposure

Irrigation work, equipment use, fuel, fertilizers, herbicides, and other landscaping activities may create environmental exposure depending on the client's actual operations.

No pollution coverage is shown in the supplied summary.

This should be treated as an **Exposure-Dependent Concern**, not a confirmed coverage gap, until operations and policy wording are reviewed.

---

# 4. Identified Coverage Gaps

| Priority | Exposure | Current Program | Gap / Concern | Potential Impact | Evidence |
|---|---|---|---|---|---|
| 1 | Contractual Liability Limits | $1M primary + $2M umbrella | Reported municipal contracts require $5M total limits | Contract noncompliance and insufficient limit | Client context |
| 2 | Equipment / Property | $1.8M limit | Values may not reflect rapid business growth | Underinsurance after major loss | Client growth |
| 2 | Pollution | None shown | Relevant exposure may exist | Environmental cleanup / third-party liability | Exposure-dependent |
| 3 | Cyber | None shown | Business dependency needs confirmation | Funds-transfer or operational cyber loss | Requires client confirmation |

---

# 5. Policy Limit Concerns

| Coverage | Current Limit | Exposure Basis | Assessment | Recommendation |
|---|---:|---|---|---|
| Umbrella | $2M | Municipal contracts reportedly require $5M total liability | Material Concern | Confirm contract requirement and model additional limit |
| Auto Liability | $1M underlying | 38 vehicles + prior $480K loss | Requires broader program review | Evaluate umbrella adequacy |
| Equipment | $1.8M | Significant revenue growth and increased equipment | Potentially Low | Obtain current equipment values |

---

# 6. Exclusions & Restrictions

Full exclusions cannot be evaluated from the supplied program summary.

Priority policy-form review should focus on:

- Tree-trimming / height restrictions
- Pollution exclusions
- Snow-removal restrictions
- Hired / non-owned auto
- Contractual liability
- Umbrella underlying coverage requirements

---

# 7. Priority Risk Areas

## Priority 1 — Liability Limit / Contract Alignment

**Business Exposure:**  
The client has reportedly begun municipal work requiring $5 million of total liability protection.

**Current Program Issue:**  
The supplied structure appears to provide approximately $3 million of combined GL and umbrella limits, subject to policy terms.

**Potential Impact:**  
The client may be unable to satisfy contract requirements and could retain liability above available limits.

**Recommended Discussion:**  
Confirm the exact contract language and evaluate additional umbrella capacity.

---

## Priority 2 — Property / Equipment Valuation

**Business Exposure:**  
Revenue increased from approximately $7 million to $12 million while equipment values also increased.

**Current Program Issue:**  
The current $1.8 million equipment / property amount may reflect an older exposure base.

**Potential Impact:**  
A major loss could expose the client to underinsurance.

**Recommended Discussion:**  
Complete a current equipment and property schedule before renewal.

---

# 8. Advisory Opportunities

| Opportunity | Business Rationale | Recommended Action | Trade-Off |
|---|---|---|---|
| Increase umbrella limits | Align with municipal contracts and severity exposure | Evaluate $5M+ structure | Additional premium |
| Update equipment values | Reflect business growth | Complete current valuation schedule | May increase property premium |
| Evaluate pollution exposure | Landscaping operations may create environmental risk | Confirm operations and obtain coverage options if warranted | Added premium / coverage conditions |
| Review fleet controls | Prior severe auto loss + 38 vehicles | Review telematics, MVRs, training and deductible strategy | Operational effort |

---

# 9. Client Conversation Priorities

### Discussion #1 — Municipal Contract Requirements

**Business Risk:**  
The company may be contractually obligated to maintain liability limits above the current program.

**Current Program:**  
Approximately $1 million primary GL and $2 million umbrella are shown.

**Concern:**  
The reported $5 million requirement may not be satisfied.

**Recommended Consideration:**  
Review actual contracts and model an appropriate umbrella structure.

**Question for Client:**  
Can we review the insurance requirements in the new municipal contracts before renewal?

---

### Discussion #2 — Equipment Values

**Business Risk:**  
A rapidly growing operation may accumulate equipment faster than insured values are updated.

**Concern:**  
Current insured property values may not reflect the company's present equipment base.

**Question for Client:**  
When was the equipment schedule last fully updated?

---

# 10. Items Requiring Policy-Form Review

| Issue | Why Review Is Needed | Document Needed |
|---|---|---|
| Tree trimming | Determine whether height / arborist restrictions exist | GL forms + endorsements |
| Pollution | Determine breadth of pollution exclusion | GL policy |
| Snow removal | Determine operational restrictions | GL / Auto policy |
| Umbrella | Confirm attachment and underlying requirements | Umbrella policy |
| HNOA | Confirm treatment of employee-owned vehicles | Auto policy |

---

# Internal Advisory Notes

The strongest immediate advisory issue is the apparent mismatch between the reported municipal contract requirements and the current umbrella structure.

The second priority should be revalidating equipment values given the client's growth.

Pollution and cyber should be approached as **exposure discovery questions**, not predetermined cross-sell recommendations.

---

# Original Signature Prompt

The original Insurance AI Advantage System Signature Prompt that inspired this Skill:

> You are a senior commercial insurance coverage analyst responsible for evaluating insurance programs and identifying meaningful risk exposure, coverage gaps, and advisory opportunities.
>
> Your objective is to assess how well the current insurance program aligns with the client’s actual operations and risk profile, and to highlight areas where protection may be insufficient, misaligned, or overlooked.
>
> Approach this as if you are preparing for a client-facing advisory discussion. Focus on practical, real-world exposure—not theoretical or overly conservative concerns. Where information is incomplete, make reasonable assumptions based on industry norms and clearly note them.
>
> INPUT DATA:
>
> Client Industry: [INSERT]
> Operations Summary: [INSERT]
> Current Insurance Program: [PASTE POLICY DETAILS, COVERAGES, LIMITS, OR SUMMARY]
> Additional Context: [INSERT – claims history, growth, concerns, contractual requirements, etc.]
>
> OUTPUT REQUIREMENTS:
>
> Produce a structured analysis that allows a producer or advisor to quickly understand risk exposure and confidently guide a client conversation.
>
> Organize the response into the following sections:
>
> Coverage Overview — a concise summary of how the current program is structured
> Identified Coverage Gaps — specific areas where coverage may be missing or incomplete
> Exposure Analysis — key operational risks based on how the business actually operates
> Policy Limit Concerns — areas where limits may be insufficient relative to exposure
> Exclusions & Restrictions — meaningful policy limitations that could impact claims
> Priority Risk Areas — ranked list of the most important concerns based on potential impact
> Advisory Opportunities — specific, practical ways to improve coverage, reduce risk, or strengthen the program
>
> GUIDELINES:
>
> Focus on real-world exposure and practical implications
> Highlight insights that would matter to a business owner, not just an insurance professional
> Avoid generic or overly cautious language
> Clearly state assumptions where information is incomplete
> Prioritize clarity, usefulness, and actionability over volume
> Ensure the output supports a meaningful client conversation—not just internal analysis
>
> EXPECTED OUTCOME:
>
> A clear, structured risk and coverage analysis that identifies actionable gaps, strengthens advisory positioning, and creates opportunities for improved client outcomes.

---

# Evolution From Signature Prompt to Signature Skill

The original Signature Prompt already established a sophisticated coverage-advisory framework.

This Signature Skill advances it by adding:

- Insurance AI Advantage System positioning
- Flywheel-stage metadata
- Orchestration-role metadata
- Upstream and downstream workflow relationships
- Document Completeness Standard
- Document Interaction / Override Standard
- Source hierarchy
- Jurisdiction / Governing Authority Standard
- Authority vs. Inference Standard
- Evidence classification
- Scope-of-Explanation Standard
- Neutral Narrative / Attribution Standard
- Client Value Standard
- Advisory readiness
- Workflow states
- Exposure architecture
- Coverage-to-exposure mapping
- Structural Gap Standard
- Limit Adequacy Standard
- Deductible / retention analysis
- Exclusion Relevance Standard
- Sublimit review
- Contract requirement review
- Loss-to-Coverage Learning Standard
- Change / Drift Detection
- Frequency and severity analysis
- Example Integrity Standard
- Materiality scoring
- Advisory Opportunity Standard
- Trade-Off Transparency Standard
- Client Conversation Standard
- Data Integrity
- Calculation Integrity
- Like-for-like comparison
- Obligation Extraction
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
- Machine-readable coverage intelligence

The progression is:

**Signature Prompt → Signature Skill → Coverage Advisory AI Teammate → Advisory AI Workforce**

---

# Related Signature Skills

- [Commercial Insurance Underwriter Submission Narrative](../01-underwriter-submission-narrative/SKILL.md)
- Renewal Risk Intelligence
- Coverage Recommendation Strategy
- Client Advisory Meeting Strategy
- Program Design Intelligence
- Proposal Intelligence

Add live links as Signature Skills are published.

---

# Related Foundational Skills

This Signature Skill may consume or orchestrate output from:

- [Commercial Prospect Intelligence Brief](../../../ai-insurance-automation-guide/01-prospect-intelligence-brief/SKILL.md)
- [Commercial Insurance Coverage Gap Analysis](../../../ai-insurance-automation-guide/03-coverage-gap-analysis/SKILL.md)
- [Commercial Insurance Exposure Summary Builder](../../../ai-insurance-automation-guide/08-exposure-summary-builder/SKILL.md)
- [Commercial Insurance Business Classification Analysis](../../../ai-insurance-automation-guide/10-business-classification-analysis/SKILL.md)
- [Commercial Insurance Policy Explanation in Plain English](../../../ai-insurance-automation-guide/11-policy-explanation-plain-english/SKILL.md)
- [Commercial Insurance Coverage Explanation](../../../ai-insurance-automation-guide/12-coverage-explanation/SKILL.md)
- [Commercial Insurance Renewal Comparison Analysis](../../../ai-insurance-automation-guide/13-renewal-comparison-analysis/SKILL.md)
- [Insurance Document Intelligence & Decision Impact Analysis](../../../ai-insurance-automation-guide/19-insurance-document-intelligence/SKILL.md)

---

# Suggested Invocation

```text
Run Signature Skill #2 — Commercial Insurance Coverage & Risk Advisory Analysis.

Client Name:
[OPTIONAL]

Client Industry:
[INSERT]

Operations Summary:
[INSERT]

Current Insurance Program:
[PASTE COVERAGE / LIMITS / POLICY INFORMATION]

Claims History:
[OPTIONAL]

Contractual Requirements:
[OPTIONAL]

Growth / Operational Changes:
[OPTIONAL]

Client Concerns:
[OPTIONAL]

Supporting Documents:
[OPTIONAL]
```

---

# Minimum Viable Invocation

```text
Client Industry:
[INSERT]

Operations Summary:
[INSERT]

Current Insurance Program:
[INSERT]

Additional Context:
[OPTIONAL]
```

---

# Version History

## 1.0.0

Initial public release.

Second Signature Skill published under the Insurance AI Advantage System using the Apeironix Gold Standard Template v2.2.

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
- Coverage advisory
- Risk analysis
- Program design
- Placement strategy
- Growth

while AI handles more of the repetitive work surrounding those responsibilities.

Apeironix is building the AI Operating Layer for insurance agencies.

Learn more at [Apeironix.com](https://apeironix.com).

---

# License

This Skill is made available under the Apache License 2.0.

See the repository `LICENSE` file for complete terms.
